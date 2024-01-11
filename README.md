# Мой Кастомный Сборщик на Gulp

![Скриншот сборки](./images/gulp.png)

Этот проект представляет собой кастомный сборщик проекта, созданный с использованием Gulp. Он позволяет автоматизировать различные задачи в процессе разработки, такие как компиляция SASS, сборка JavaScript, обработка изображений и многое другое.

## Описание

Этот кастомный сборщик настроен на выполнение различных задач в процессе разработки веб-приложений. Он использует Gulp и различные Gulp-плагины для выполнения следующих задач:

- Компиляция и сборка стилей из SASS в CSS.
- Сборка и минификация JavaScript.
- Оптимизация изображений.
- Автоматическое обновление браузера при изменении файлов.
- Автоматическое подключение SCSS
- Очистка директории сборки перед каждой новой сборкой.

## Особенности сборщика

- Автоматическая компиляция SASS в CSS.
- Сжатие и минификация JavaScript.
- Оптимизация изображений для улучшения производительности.
- Локальный сервер с функцией автообновления при изменениях файлов.
- Удобные задачи для разработки и сборки проекта.

## Технологии

Кастомный сборщик был разработан с использованием следующих технологий и инструментов:

- **Gulp**: Основной инструмент для автоматизации задач.
- **SASS**: Для компиляции и сборки стилей.
- **Webpack**: Для сборки JavaScript.
- **BrowserSync**: Для локального сервера и автообновления браузера.
- **Gulp-Load-Plugins**: Для удобного подключения Gulp-плагинов.

## Запуск проекта

Для запуска этого кастомного сборщика на своем компьютере выполните следующие шаги:

1. Склонируйте репозиторий на свой локальный компьютер:

   ```bash
   git clone https://github.com/myrzakan/Gulp-Starter.git

   ```

2. Перейдите в директорию проекта:

   ```bash
   cd gulp-starter

   ```

3. Установите зависимости:

   ```bash
   npm install

   ```

4. Запустите сборку:

   ```bash
   npm run dev

   ---

   ## Скрипты для Управления Компилятором Gulp

   Вы можете использовать следующие команды npm для управления компилятором Gulp:
   ```

- `npm start`: Запускает компилятор в режиме разработки. Это позволяет вам выполнять задачи компиляции и автоматически обновлять результаты при изменениях файлов. Используйте эту команду, когда работаете над вашим проектом.

- `npm run build`: Запускает компилятор в режиме сборки. В этом режиме компилятор выполняет оптимизацию и минификацию файлов для готового к развертыванию проекта. Используйте эту команду перед развертыванием вашего проекта на сервере.

- `npm run startPug`: Если ваш проект использует Pug вместо HTML, вы можете использовать эту команду для запуска компилятора в режиме разработки с поддержкой Pug. Это позволит вам использовать Pug для разметки.

- `npm run buildPug`: Если ваш проект использует Pug вместо HTML, вы можете использовать эту команду для запуска компилятора в режиме сборки с поддержкой Pug. В этом режиме Pug-файлы будут скомпилированы и оптимизированы для развертывания на сервере.
