Сайт с базовым функционалом, в качестве бекенда используется Laravel 10, фронтенд сделан на Vue 3 composition api. 

## Используемый стек

- PHP 8.1
- MySQL 8.0
- Redis 7.0
- Laravel 10
- Laravel sanctum
- Vue 3 composition api
- Vue router
- Axios

## Установка
- создайте свой файл env
- composer install
- npm install
- php artisan migrate
- php artisan db:seed
- npm run build
- php artisan queue:work (отправка email уведомлений не будет работать без запуска очереди)

## Реализован функционал: 

- авторизация и регистрация юзеров
- верификация email (реализовано через очереди)
- сброс пароля через email (реализовано через очереди)
- разграничение прав юзеров и админов (сидер создаст обычного юзера и админа)
- возможность редактировать свой профиль для юзеров
- новостной блог
- админ панель для редактирования, создания и удаления новостей
- локализация валидации на русский язык
- авто тесты
  

