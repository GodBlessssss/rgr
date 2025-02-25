# Orgtechnika Management System

Проєкт створений для управління містами, магазинами та товарами. Використовує Java Spring Boot та PostgreSQL для розгортання.

## Опис

Ця система дозволяє:
- Додавати, редагувати та видаляти інформацію про міста, магазини та товари.
- Зберігати інформацію про міста, магазини та товари.
- Управляти користувачами (авторизація, ролі).

---

## Функціональність

1. **Міста:**
   - Додавання/видалення/редагування міст.

2. **Магазини:**
   - Додавання/видалення/редагування магазинів.

3. **Товари:**
   - Додавання/видалення/редагування товарів.

4. **Користувачі:**
   - Авторизація (з ролями: Адміністратор, Користувач).

---

## Запуск проєкту

### Використання PostgreSQL та Maven

1. **Встановіть необхідні інструменти**

   - PostgreSQL
   - Maven
   - JDK 21

2. **Налаштуйте змінні середовища**

   Замініть ${LOGIN} і ${PASSWORD} на потрібні значення у файлах: 

   - application.properties

3. **Запакуйте проєкт**

   Використовуйте Maven для створення пакета: mvn package

4. **Запустіть додаток**

   Використовуйте вашу IDE або запустіть програму безпосередньо з папки target.

5. **Відкрийте додаток у браузері**

   Перейдіть за адресою: http://localhost:8080

---

## Ролі та можливості користувачів

- Неавторизований користувач може бачити лише сторінку авторизації.
- Авторизований користувач, який має роль USER, має доступ на перегляд даних.
- Авторизований користувач, який має роль ADMIN, може додавати, оновлювати та видаляти дані.

---

## Технології

- Java 21 (Spring Boot)
- PostgreSQL
- Maven






