![Astro Logo](https://st.timeweb.com/cloud-static/apps-logo/astro.svg)

# Astro

Пример приложения [Astro](https://astro.build/), которое можно развернуть в **Timeweb Cloud Apps** без настройки.

:tada: [Демо]

:rocket: [Создать свой Apps](https://timeweb.cloud/my/apps/create)

:books: [Документация Timeweb Cloud Apps](https://timeweb.cloud/docs/apps)

## Параметры деплоя

Приложение разворачивается как frontend: Astro собирает статический сайт, который отдаёт веб-сервер.

| Параметр          | Значение        |
| ----------------- | --------------- |
| Фреймворк         | Astro           |
| Команда сборки    | `npm run build` |
| Директория сборки | `dist`          |

Пример с серверным рендерингом — [app-example-astro-ssr](https://github.com/timeweb-cloud-apps/app-example-astro-ssr).

## <a name="dev"></a>Локальный запуск проекта

```bash
# установка зависимостей
npm install

# запуск в дев режиме с отслеживанием изменений
npm run dev

# сборка для продакшн с минификацией
npm run build

# локальный просмотр собранной сборки
npm run preview
```

Для работы нужен Node.js 22.12 или новее.
