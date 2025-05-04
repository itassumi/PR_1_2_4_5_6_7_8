# Практична робота №6

## Тема
**Розробка UI для реалізації CRUD-операцій**

## Мета
Створити користувацький інтерфейс для взаємодії з реалізованим RESTful API, що надає можливість **перегляду, створення, редагування та видалення** екземплярів певної сутності.  
Розробка ведеться на базі **React** з використанням **TanStack Router** для реалізації маршрутизації.

---

##  Завдання

На основі boilerplate-проєкту [`vite-react-boilerplate`](https://github.com) реалізувати UI для роботи з сутністю `Post`, яка була створена у попередньому занятті.

---

### 1. Сторінка колекції екземплярів сутності (`/posts`)

- Відображення списку всіх доступних `Post`
- Показ основної інформації для кожного елемента
- Перехід до перегляду конкретного поста: `/posts/:id`
- Кнопка **"Створити новий екземпляр"** → `/posts/new`
- Реалізація **видалення** елементів (із підтвердженням дії)

![UI Posts 1](https://github.com/user-attachments/assets/936ce9fc-cec8-4c13-b17f-e1d28bab476f)
![UI Posts 2](https://github.com/user-attachments/assets/db9c857d-5852-48e8-a99c-afd1647c2cdb)
![UI Posts 3](https://github.com/user-attachments/assets/5574a39d-17ca-4d5c-bcad-f776711a17cc)
![UI Posts 4](https://github.com/user-attachments/assets/633ca7f1-653f-435c-8607-23b05b2709b3)
![UI Posts 5](https://github.com/user-attachments/assets/32b486c1-6c6f-447c-b22a-dff210241030)

---

### 2. Сторінка одного поста (`/posts/:id`) або створення нового (`/posts/new`)

#### `/posts/:id` (перегляд та редагування)

- Повне відображення інформації
- Форма редагування
- Кнопка **Update** для збереження змін

#### `/posts/new` (створення)

- Форма з порожніми полями
- Кнопка **Create** для збереження нового поста

![UI Edit](https://github.com/user-attachments/assets/b10215b0-96f9-43de-b23f-74587b79bb56)
![UI Create](https://github.com/user-attachments/assets/247d645d-b6c7-42cd-8d1c-50737a91ea40)

---

###  Результат

![Result 1](https://github.com/user-attachments/assets/64822311-1c0f-49c9-9f1e-14dfcd12ad23)
![Result 2](https://github.com/user-attachments/assets/34cd28c8-2afe-487d-a876-b1206ad05a5f)
![Result 3](https://github.com/user-attachments/assets/29ed939b-1f20-4453-8ffb-f40d924527a4)
![Result 4](https://github.com/user-attachments/assets/4ddd7de4-db6b-4613-a3f0-2779e311d8f6)
![Result 5](https://github.com/user-attachments/assets/810519cd-9b6f-40d6-bd43-32c6756e0f3f)
![Result 6](https://github.com/user-attachments/assets/dbf1fc80-65f8-4331-9ae5-f8245d5a2856)

---
 
