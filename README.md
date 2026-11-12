# Cloud Lab — облачное веб-приложение
## Назначение
Учебное веб-приложение для изучения GitHub Codespaces и работы с HTTP API.
## Использованные технологии
Node.js
Express.js
JavaScript
GitHub Codespaces
Linux, Git
## Установка и запуск
Установка зависимостей:
bash
npm install
Запуск сервера:
bash
npm start
Адрес приложения: `http://localhost:3000`
## HTTP-маршруты
Метод  Маршрут Описание 
GET  `/`  Главная страница 
GET  `/api/status` Состояние сервера
GET | `/api/services`Список сервисов
GET | `/api/services/:id`Получение сервиса по ID
GET | `/api/hello`Приветствие (по умолчанию «Гость»)
GET | `/api/hello?name=Anna` | Приветствие по имени
POST | `/api/services`Добавление нового сервиса