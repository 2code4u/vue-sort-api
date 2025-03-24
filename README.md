## Таблица данных транзацкий с сортировкой и фильтрацией через локальное API
Основной метод Стора <b>loadList</b> использует тело в качестве фильтрации и сортировки, отправляя данные в локальное Апи - которое играет роль мокковой БД отдающий <b>local.json</b>
Не осталось времени содзать отдельный Node express, но методы запросы были бы такими же где <b>axios</b> бы содержал тело фильтра

## Базовые зависимости Vite Vue3 Pinia TypeSript Vuetify Axios

```sh
npm install
```

### Compile and Hot-Reload for Development

```sh
npm run dev
```

### Type-Check, Compile and Minify for Production

```sh
npm run build
```
