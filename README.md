# My Shop

## Описание проекта
**My Shop** — это одностраничное React-приложение, демонстрирующее магазин с карточками товаров. В проекте используется менеджер состояния Redux Toolkit, Material-UI для стилизации, а также mock API на основе json-server. Приложение поддерживает добавление, редактирование и удаление товаров, а также работу с локальным кэшированием данных.

## Используемые технологии
- **React 18+** — библиотека для создания пользовательского интерфейса
- **Redux Toolkit** — управление состоянием приложения
- **Material-UI** — стилизация компонентов
- **Axios** — работа с API
- **React Router** — маршрутизация
- **json-server** — создание mock API
- **Framer Motion** — анимации (опционально)

## Установка и запуск
### Шаг 1: Настройка проекта
1. Клонируйте репозиторий:
   ```sh
   git clone https://github.com/1vanch0s/react-application-shop-for-backend-class-
   cd my-shop
   ```
2. Установите зависимости:
   ```sh
   npm install
   ```
3. Установите дополнительные библиотеки:
   ```sh
   npm install @reduxjs/toolkit react-redux @mui/material @emotion/react @emotion/styled axios react-router-dom
   ```

### Шаг 2: Создание mock API
1. Установите json-server (если не установлен):
   ```sh
   npm install -g json-server
   ```
2. Запустите сервер mock API:
   ```sh
   json-server --watch public/data.json --port 3001
   ```
3. Mock API будет доступен по адресу: [http://localhost:3001/products](http://localhost:3001/products)

### Шаг 3: Запуск приложения
Запустите проект с помощью команды:
```sh
npm run dev
```
Приложение будет доступно по адресу, указанному в консоли (обычно [http://localhost:5173](http://localhost:5173)).

### (Опционально) Добавление анимаций
Чтобы добавить анимации для карточек товаров, установите Framer Motion:
```sh
npm install framer-motion
```


## Дополнительные возможности
- Поддержка **темной/светлой темы**


