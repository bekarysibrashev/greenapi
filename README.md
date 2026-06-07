# GREEN-API WhatsApp Control Panel

## 📌 Описание проекта

Этот проект представляет собой веб-интерфейс для работы с GREEN-API WhatsApp Gateway.

Приложение позволяет выполнять основные методы API через удобную HTML-страницу:

- getSettings
- getStateInstance
- sendMessage
- sendFileByUrl

Стили были созданы при помощи ClaudeAI
---

## 🚀 Функционал

### 🔧 Подключение
- Ввод `idInstance`
- Ввод `ApiTokenInstance`

### 📡 Методы API

- **getSettings** - получение настроек инстанса  
- **getStateInstance** - проверка статуса подключения WhatsApp  
- **sendMessage** - отправка текстового сообщения  
- **sendFileByUrl** - отправка файла по URL  

---

## 🧪 Демонстрация работы

### 📌 getSettings
Показ настроек инстанса

![getSettings](images/getSettings.png)

---

### 📌 getStateInstance (AUTHORIZED)
Статус подключения: WhatsApp авторизован

![authorized](images/getStateInstance_authorized.png)

---

### 📌 getStateInstance (UNAUTHORIZED)
Статус подключения: WhatsApp не авторизован

![unauthorized](images/getStateInstance_unauthorized.png)

---

### 📌 sendMessage (успешная отправка)

Сообщение успешно отправлено в WhatsApp

![send success](images/sendMessage_success.png)

---

### 📌 sendMessage (ошибка)

Ошибка при отправке сообщения (неверные данные / невалидный номер)

![send error](images/sendMessage_error.png)

---

### 📌 Сообщение в WhatsApp

Результат отправки сообщения в WhatsApp

![whatsapp](images/message_whatsapp.png)

---

## 🌐 Демо

Онлайн версия проекта:

👉 https://your-netlify-link.com

---

## 🛠 Используемые технологии

- HTML5
- CSS3 (custom UI design)
- JavaScript (Fetch API)
- GREEN-API REST

---

## 📦 Как запустить локально

1. Скачать проект
2. Открыть `index.html` в браузере
3. Ввести:
   - `idInstance`
   - `ApiTokenInstance`
4. Использовать кнопки API

---

## 🎯 Цель проекта

Демонстрация навыков:
- работы с REST API
- обработки JSON ответов
- создания UI панели управления
- интеграции сторонних сервисов (GREEN-API)
- деплоя веб-приложения

---

## 📬 Автор

Telegram: https://t.me/your_username
