# Система Управления Рестораном
    Описание
Этот проект представляет собой систему управления рестораном, реализованную на языке программирования Go с использованием фреймворка Gin для веб-сервера и MongoDB в качестве базы данных. Система позволяет управлять заказами, столиками, меню, пользователями и элементами заказа в ресторане.

    Функциональность
Управление пользователями: регистрация, авторизация, получение информации о пользователе.
Управление меню: добавление, обновление, получение информации о блюдах.
Управление столиками: добавление, обновление, получение информации о столиках.
Управление заказами: создание, обновление, получение информации о заказах.
Управление элементами заказа: создание, обновление, получение информации об элементах заказа.
    Технологии
Язык программирования: Go
Веб-фреймворк: Gin
База данных: MongoDB
Аутентификация: JWT (JSON Web Tokens)
Установка и Запуск
    Требования
Установленный Go (версия 1.15 или выше)
Установленный MongoDB
Шаги для запуска
Клонировать репозиторий:
bash
Copy code
git clone https://github.com/yourusername/golang-restaurant-management.git
Перейти в каталог проекта:
bash
Copy code
cd golang-restaurant-management
Запустить сервер:
bash
Copy code
go run main.go
Использование
После запуска сервера доступ к API осуществляется через http://localhost:8000/. Маршруты API включают:

/users/signup - регистрация пользователя
/users/login - вход пользователя
/menus - управление меню
/tables - управление столиками
/orders - управление заказами
/orderItems - управление элементами заказа
