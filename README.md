# LayoutTest

This project was generated using [Angular CLI](https://github.com/angular/angular-cli) version 19.2.10.

## Development server

To start a local development server, run:

```bash
ng serve
```

Once the server is running, open your browser and navigate to `http://localhost:4200/`. The application will automatically reload whenever you modify any of the source files.

## Code scaffolding

Angular CLI includes powerful code scaffolding tools. To generate a new component, run:

```bash
ng generate component component-name
```

For a complete list of available schematics (such as `components`, `directives`, or `pipes`), run:

```bash
ng generate --help
```

## Building

To build the project run:

```bash
ng build
```

This will compile your project and store the build artifacts in the `dist/` directory. By default, the production build optimizes your application for performance and speed.

## Running unit tests

To execute unit tests with the [Karma](https://karma-runner.github.io) test runner, use the following command:

```bash
ng test
```

## Running end-to-end tests

For end-to-end (e2e) testing, run:

```bash
ng e2e
```

Angular CLI does not come with an end-to-end testing framework by default. You can choose one that suits your needs.

## Additional Resources

For more information on using the Angular CLI, including detailed command references, visit the [Angular CLI Overview and Command Reference](https://angular.dev/tools/cli) page.

# Товарная карточка (Product Card UI)

Этот проект — адаптация интерфейса товарной карточки под мобильное отображение по готовому макету. Реализовано с использованием HTML, CSS и JavaScript без дополнительных библиотек и фреймворков.

## 📦 Структура проекта

```
layout-test/
├── index.html             # Основной HTML-файл
├── styles.css             # Все стили проекта
├── img.png                # Изображение товара
├── arrow-left_big.png     # Иконка "назад"
├── logo-motodetal.png     # Логотип бренда
├── icon-coin.png          # Иконка бонусов
├── Button.png             # Кнопка "В корзину"
├── catalog.png            # Нижняя навигация: Каталог
├── Zakazy.png             # Заказы
├── novosty.png            # Новости
├── korzina.png            # Корзина
└── profil.png             # Профиль
```

## 🧩 Функциональность

- Отображение информации о товаре: название, цена, бонусы, наличие, дата поставки.
- Переключение вкладок: **Описание / Характеристики**.
- Блоки с разными городами (Москва / Ростов) с уникальными действиями:
  - Москва: кликабельная кнопка «В корзину».
  - Ростов: выбор количества через кнопки "+" / "−".
- Нижняя навигация с иконками (Каталог, Заказы, Новости, Корзина, Профиль).
- Иконка «назад» с интерактивным курсором.

## 💻 Установка и запуск

1. Склонируй или скачай репозиторий:
   ```bash
   git clone https://github.com/your-username/your-repo.git
   ```

2. Открой `index.html` в браузере:
   ```bash
   open index.html
   ```
   или просто дважды кликни на файле.

## ✨ Технологии

- HTML5
- CSS3 (без препроцессоров)
- JavaScript (Vanilla)
- Шрифты: [Inter](https://fonts.google.com/specimen/Inter)

## 📌 Заметки

- Проект полностью адаптирован под мобильную ширину (максимум `360px`).
- Без подключения к серверу или базе данных.
- Все действия реализованы на клиенте.



**Разработано как тестовое задание.**
