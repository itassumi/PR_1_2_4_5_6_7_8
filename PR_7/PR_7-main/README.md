# Практично-лабораторне заняття №7
Інтеграція клієнтської частини з RESTful API

## Мета
Підключити користувацький інтерфейс до реального серверного API. Ознайомитися з підходами до організації HTTP-запитів через Axios, зберігання токенів доступу, обробки помилок, роботи з .env-змінними. Забезпечити повноцінну взаємодію клієнтської частини з бекендом.

## Завдання
Використовуючи реалізовану у попередньому завданні клієнтську частину (інтерфейс для роботи з сутністю Post), внести такі зміни:

### 1. Налаштування змінних оточення:
- У корені проєкту створити файл `.env`
- Додати до нього такі змінні:
```env
VITE_API_BASE_URL=http://localhost:4000/v1
VITE_API_AUTH_TOKEN=your_jwt_token_here
```
![image](https://github.com/user-attachments/assets/7937a51a-2161-42b8-829b-0be2799446b2)

Реалізувати використання цих змінних у конфігурації Axios

### 2. Створити конфігурацію Axios:
- Створити окремий файл (наприклад, `src/api/axios.ts`)
- Налаштувати базовий `baseURL`, заголовок `Content-Type`, токен авторизації:
![image](https://github.com/user-attachments/assets/537e27a9-e420-4d30-978b-8fa19c386af7)

- Реалізувати обробку помилок через інтерцептор (наприклад, логування у консоль або показ повідомлення)
![image](https://github.com/user-attachments/assets/bc8ccd68-3c6b-4133-bad0-f64d02b8e3db)

### 3. Замінити мок-функції на реальні HTTP-запити:
У файлі з API-функціями (`src/api/posts.ts` або аналогічному) замінити реалізацію:
- `getAllEntities()` → `GET /posts`
- `getEntityById(id)` → `GET /posts/:id`
- `createEntity(data)` → `POST /posts`
- `updateEntity(id, data)` → `PUT /posts/:id`
- `deleteEntity(id)` → `DELETE /posts/:id`

Повернення типізованих відповідей із Axios бажане
![image](https://github.com/user-attachments/assets/c5d78d1d-040f-45cf-91c9-5d2cf91ffcce)
![image](https://github.com/user-attachments/assets/19ddbf5f-4d63-4480-90c2-334842813e5e)
![image](https://github.com/user-attachments/assets/76f5d928-6111-4d27-9419-2cb4a3848d5f)

