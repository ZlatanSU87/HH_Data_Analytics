![](https://www.soutron.com/wp-content/uploads/2022/02/what-is-an-archive-management-system-Soutron.jpeg)
# <center> Анализ резюме из HeadHunter
## <center> Оглавление
1. [Опиcание проекта](#описание-проекта)
2. [Описание данных](#описание-данных)
3.

## Описание проекта
**Дана** [база_1](https://drive.google.com/file/d/1Kb78mAWYKcYlellTGhIjPI-bCcKbGuTn/view?usp=sharing) И [база_2](https://lms-cdn.skillfactory.ru/assets/courseware/v1/15abf80f45a2f3e93c3274101b451c67/asset-v1:SkillFactory+DST-3.0+28FEB2021+type@asset+block/ExchangeRates.zip) резюме, выгруженная с сайта поиска вакансий hh.ru. 
**Проблематика**: часть соискателей не указывает желаемую заработную плату, когда составляет своё резюме.

Компания **HeadHunter** хочет построить модель, которая бы автоматически определяла примерный уровень заработной платы, подходящей пользователю, исходя из информации, которую он указал о себе.

### Данный проект реализует:
* базовый анализ структуры данных
* преобразование данных
* разведывательный анализ
* очистку данных

**О структуре проекта:**
* [plotly](./plotly) - папка с изображениями графиков проекта
* [Project_HH_Data_Analytics.ipynb](./Project_HH_Data_Analytics.ipynb) - jupyter-ноутбук, содержащий основной код проекта, в котором демонстрируются методы и подходы решения задачи

## Описание данных
### Данные представляют из себя таблицу со следующими **признаками**:
 - Пол, возраст	
 - ЗП	
 - Ищет работу на должность:	
 - Город, переезд, командировки	
 - Занятость	
 - График	
 - Опыт работы	
 - Последнее/нынешнее место работы	
 - Последняя/нынешняя должность	
 - Образование и ВУЗ	
 - Обновление резюме	
 - Авто

**Всего 44744 строк и 12 колонн**

## Используемые зависимости
* Python (3.9):
    * [numpy (1.20.3)](https://numpy.org)
    * [pandas (1.3.4)](https://pandas.pydata.org)
    * [matplotlib (3.4.3)](https://matplotlib.org)
    * [seaborn (0.11.2)](https://seaborn.pydata.org)

## Установка проекта

```
git clone https://github.com/SkillfactoryDS/DataCleaningProject
```

## Использование
Вся информация о работе представлена в jupyter-ноутбуке Project-1._Ноутбук-шаблон.ipynb.

## Авторы

* [Sergey](https://t.me/IZ20112022)

## Выводы

По результатам реализации проекта на примере базы данных HH.ru можно разобрать некоторые популярные способы очистки данных, выявить закономерности по ожидаемой пользователем заработной плате, исходя из информации, которую он указал о себе.