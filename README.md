# Тестовое задание:

## Реализовать SPA
Использовать VueJS или React, Роутинг и хранилище состояний
При верстке можно использовать Bootstrap, Vuetify и т.д
Для работы с сервером можно использовать json файлы. (Текст статьи, список комментариев, данные о пользователе, чтобы авторизоваться)
* Главная страница
На главной странице есть 2 ссылки: на страницу со статьей и на главную
две кнопки: Авторизация и Регистрация. Если пользователь авторизован вместо кнопок отображать имя пользователя
* Пользователь может авторизоваться либо зарегистрироваться.
При нажатии на кнопку "Авторизации"/"Регистрации" открывается модальное окно для заполнения формы с полями логин и пароль
Во время авторизации эмулировать работу API. Сверять логин пароль с данными на "сервере"
Регистрация проходит без проверки данных
Все данные о пользователе хранить в хранилище состояний.
* Страница со статьей
Выводится небольшая статья(контент не важен) и список комментариев (Статья получается через запрос к "серверу")
* Комментарии
уже существующие комментарии содержат: Имя пользователя, Дата и время комментария, текст комментария
Если пользователь авторизован он может добавить свой комментарий
после всех комментариев есть кнопка "Добавить комментарий".
при нажатии на нее отображается текстовое поле в которое записывается комментарий и
кнопка "Добавить комментарий" она добавляет комментарий к уже существующим

Логин: MrRobot  
Пароль: fsocial

### [Посмотреть демо](https://vigrom.herokuapp.com/)


## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).
