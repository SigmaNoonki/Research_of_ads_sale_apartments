# Research_of_ads_sale_apartments
# Исследование объявлений о продаже квартир
## Требуется разобраться:  
- влияет ли площадь, количество комнат и удаленность от центра на стоимость объекта  
- какие прочие параметры могут также оказывать влияние на стоимость объекта

В нашем распоряжении данные сервиса Яндекc Недвижимость — архив объявлений о продаже квартир в Санкт-Петербурге и соседних населённых пунктах за несколько лет. Необходимо научиться определять рыночную стоимость объектов недвижимости. 

*Задача — установить параметры, от которых зависит стоимость объекта.*

По каждой квартире на продажу доступны два вида данных. Первые вписаны пользователем, вторые получены автоматически на основе картографических данных (расстояние до центра, аэропорта, ближайшего парка и водоёма).

**Ход исследования**

Данные об объявлениях содержатся в файле (Путь к файлу: /datasets/real_estate_data.csv). О качестве данных ничего не известно. Поэтому перед проверкой гипотез проведем обзор данных. 

Проверим данные на ошибки и оценим их влияние на исследование. На этапе предобработки исправим самые критичные ошибки данных.
 
Таким образом, исследование содержит три этапа:
 1. Обзор данных.
 2. Предобработка данных.
 3. Проверка гипотез.


Результаты исследования будут учтены при построении автоматизированной системы: она отследит аномалии и мошенническую деятельность.
