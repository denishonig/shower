# Корпоративная тема 2GIS для Shower HTML presentation engine

## Установка зависимостей

```sh
sudo apt-get install nodejs
```

```sh
# project root folder
npm install
```

Так же можно использовать `bower`.

## Смотрим в действии

- Открываем в браузере index.html
- Видим всю презентацию
- Кликаем на любой слайд и входим в presentation mode
- Навигируемся стрелками клавиатуры
- Жмем `Esc` для выхода из presentation mode

Читаем [Wiki](https://github.com/shower/shower/wiki) если возникли вопросы.

## Экспорт презентации в HTML

```sh
npm install -g grunt-cli
```

Далее смотрим на доступные задачи для Grunt

```sh
grunt --help
```

Для экспорта и создания архива используем `grunt archive`. Для экспорта в папку используем `grunt export`.
