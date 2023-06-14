## Проект по питону: исследуем однокомнатные квартиры и апартаменты в новостройках Москвы с сайта "Циан".
### Участники: Заварзина Екатерина, Ускова Ольга.
### Парсинг: 
Мы собрали данные с "Циана" об однокомнатных квартирах для первичной продажи в Москве. Получился датасет из 8229 наблюдений. Удалось получить как 
категориальные (квартира или апартаменты, район, ближайшая станция метро и т.д.), так и количественные признаки (цена, площадь, этаж и т.д.).
#### Хотим проверить следующие гипотезы: 
1) Для квартир высокого ценового сегмента характеристика "время до ближайшего метро" перестает иметь основополагающее значение.
2) Дисперсия стоимости м² в москвоских новостройках в ЦАО не меньше, чем в ЗАО.
3) Квадратный метр в апартаментах стоит не дешевле квадратного метра в квартире.
4) Цены м² в квартирах и апартаментах, находящихся на последних двух этажах и не находящихся на последних этажах, равны.
#### Планируемое машинное обучение:
Мы хотим обучить модель линейное регрессии предсказывать стоимость м² в москвоских новостройках на основе следующих признаков: этажа, этажности здания, округа, времени до метро (пешком) и типа жилья (апартаменты или квартира).
