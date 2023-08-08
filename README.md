# EDA_Zomato
Exploratory data analysis of Zomato food delivery app

## Описание датасета
- Датасет: https://www.kaggle.com/datasets/anas123siddiqui/zomato-database?resource=download&select=restaurant.csv
- База данных приложения для доставки еды Zomato представляет собой всеобъемлющий набор таблиц, в которых хранится вся важная информация, связанная с приложением для доставки еды (Учетные данные, такие как имя пользователя, адрес электронной почты, пароль и продажи). База данных содержит информацию о заказах, сделанных пользователями, доступных в приложении продуктах питания, меню различных ресторанов, самих ресторанах и пользователях, зарегистрированных в приложении. Таблицы взаимосвязаны и хранят конкретную информацию, что позволяет эффективно извлекать данные. 
- Таблица orders содержит информацию о заказах, включая дату, количество продаж, сумму продаж, валюту, идентификатор пользователя и идентификатор ресторана. 
- В таблице food хранится информация о продуктах питания, включая их идентификатор, название и вегетарианский или невегетарианский статус. 
- Таблица menu содержит информацию о меню ресторана, включая идентификатор меню, идентификатор ресторана, идентификатор блюда, кухню и цену. 
- В таблице restaurant хранится информация о ресторанах, включая идентификатор, название, рейтинг, количество оценок, стоимость, кухню, номер лицензии, ссылку на веб-сайт, адрес и меню. 
- Таблица users содержит информацию о пользователях приложения, включая их идентификатор, имя, адрес электронной почты, пароль, возраст, пол, семейное положение, профессию, ежемесячный доход, уровень образования и размер семьи.
## Результаты работы
- Предобработка данных (очищение данных от пропусков, изменение типов переменных, уменьшение количества категорий для видов кухонь и блюд - создание более крупных когорт, join таблиц
- Удаление выбросов для суммы заказов и количества блюд в заказе
- Визуализация переменных и описание параметров их распределения
- Проверка статистических гипотез с помощью бакетного преобразования
- Сегментация пользователей по RFM
- Построение линейной регрессии и проверка значимости коэффициентов
- Подсчет продуктовых метрик - DAU, WAU, MAU, sticky factor, конверсия в покупку, retention, 
  




