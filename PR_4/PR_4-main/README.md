# Практична робота №4

## Тема
**Реалізація нової сутності, створення CRUD-операцій та відповідного RESTful API**

## Мета
Закріпити навички створення повноцінної серверної логіки для роботи з новою сутністю за допомогою **TypeORM**, **Express** та **TypeDI**. Ознайомитися з процедурою створення міграцій, перевірки змін у структурі бази даних та тестування REST API через **Postman**.

---

## ✅ Завдання

### 1. Створення нової сутності `Post`

![Post Entity](https://github.com/user-attachments/assets/3504aa3e-bf7d-4269-bee6-a6dcf41746e0)

---

### 2. Створення та виконання міграції

- Створити міграцію для сутності `Post`
- Виконати міграцію:

![Migration Command](https://github.com/user-attachments/assets/019e3f13-eba5-47ab-81df-a00165471c5d)

- Перевірити результат виконання через IDE:

![DB State](https://github.com/user-attachments/assets/92f422b5-06c7-47fb-ac14-d448b88cde2c)

---

### 3. Реалізація REST API (CRUD для `Post`)

- Створити контролер та сервіси
- Налаштувати маршрути відповідно до REST принципів

![API Screenshot 1](https://github.com/user-attachments/assets/33569abb-74fd-41c2-943e-d03abef9d75d)

![API Screenshot 2](https://github.com/user-attachments/assets/cba1e9e7-e47e-47a8-9ff1-ecfb5e4d4773)

---

### 4. Тестування через Postman

- Додати нові ендпоінти до колекції Postman
- Протестувати всі CRUD-операції:

![Postman](https://github.com/user-attachments/assets/117a9ece-ce57-4236-bb01-219231823238)

---




