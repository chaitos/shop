# Интернет-магазин на Django

Учебный проект интернет-магазина на Django.

## Возможности

* каталог товаров;
* категории товаров;
* просмотр страницы товара;
* фильтрация товаров по категориям;
* связанные товары;
* загрузка изображений;
* корзина на основе Django Sessions;
* добавление и удаление товаров из корзины;
* изменение количества товаров;
* автоматический расчёт стоимости корзины.

## Стек

* Python
* Django
* SQLite
* Pillow
* HTML / CSS
* Django Templates

## Структура

* `main` — каталог, категории и товары;
* `cart` — логика корзины;
* `shop` — настройки и конфигурация проекта.

## Запуск

```bash
git clone https://github.com/chaitos/shop.git
cd shop
python -m venv venv
venv\Scripts\activate
pip install -r requirements.txt
python manage.py migrate
python manage.py runserver
```

После запуска проект доступен по адресу:

`http://127.0.0.1:8000/`
