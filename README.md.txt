# JSONPlaceholder API Test — Apache JMeter

## Project Overview
Цей проєкт містить тестовий план для перевірки основних HTTP методів (GET, POST, PUT, PATCH, DELETE) публічного REST API [JSONPlaceholder](https://jsonplaceholder.typicode.com).  
Тест створено та виконано в середовищі **Apache JMeter 5.6.3**.

---

## Test Purpose
Мета тестування — перевірити працездатність основних REST-запитів до публічного API та продемонструвати застосування Apache JMeter для функціонального тестування API з використанням Assertions та Listener’ів.

---

## Test Configuration

| Parameter | Value |
|------------|--------|
| Threads (Users) | 1 |
| Loop Count | 3 |
| Duration | 10 seconds |
| Ramp-up Period | 0 |
| Server | jsonplaceholder.typicode.com |
| Protocol | HTTPS |

---

## Endpoints

| Method | Endpoint | Description |
|:-------|:----------|:-------------|
| GET | /posts/1 | Отримання одного поста |
| POST | /posts | Створення нового поста |
| PUT | /posts/1 | Повне оновлення поста |
| PATCH | /posts/1 | Часткове оновлення поста |
| DELETE | /posts/1 | Видалення поста |

---

## Assertions
Кожен запит має три перевірки:
1. **Response Code** — перевірка статусу відповіді  
2. **Response Body / JSON** — перевірка вмісту тіла відповіді  
3. **Response Time** або наявність ключових полів  

---

## Listeners Used
- **View Results Tree** — перегляд запитів та відповідей у реальному часі  
- **Summary Report** — підсумкова статистика по всіх запитах  

---

## Files in Repository
