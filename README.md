# Code workshop for product designers
[Опубликованный сайт](https://pd-workshop.netlify.app)

Сделано на [11ty](https://1ty.dev) и [Shower](https://shwr.me/).

## Как сделать свою копию
На вашем компьютере должен быть установлен [Node.js](https://nodejs.org/).

1. Скопируйте репозиторий к себе.
    1. Откройте [страницу импорта](https://github.com/new/import).
    2. Вставьте в поле адреса `https://github.com/dontliem1/product-designer-webinar`
    3. Введите имя для своего сайта.
    4. Склонируйте получившийся репозиторий к себе на компьютер.
2. установите зависимости с помощью команды `npm install` и запустите локальный сервер `npm start`.
3. Редактируйте `index.html` и смотрите результат на `http://localhost:8080`.
4. Сервер для внутренних страниц в папке `src` запускается командой `npm run 11ty-serve`.

Как закончите правки, запустите команду:

    npm run bundle

Презентация и внутренние страницы будут лежать в папке `bundled`. Запустив `npm run archive` вы можете получить сразу архив `presentation.zip`, а `npm run pdf` — презентацию в PDF.
