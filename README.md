<h1 align="center">💬 Chat App (Python Socket Tutorial)</h1>
<p align="center">
  Простое консольное чат-приложение на Python, реализованное с использованием сокетов и многопоточности.
</p>

<p align="center">
  <img src="https://img.shields.io/github/languages/top/MuratOfficial/chat-app-with-tutorial?style=flat-square" />
  <img src="https://img.shields.io/github/license/MuratOfficial/chat-app-with-tutorial?style=flat-square" />
  <img src="https://img.shields.io/github/stars/MuratOfficial/chat-app-with-tutorial?style=flat-square" />
</p>

---

## 🚀 О проекте

Этот проект демонстрирует, как создать чат-сервер и клиента на Python с помощью стандартных библиотек `socket` и `threading`. Подходит для обучения сетевому программированию и основам многопоточности.

---

## 🧰 Стек технологий

- **Язык**: Python 3  
- **Сеть**: `socket`  
- **Параллельность**: `threading`  
- **Среда запуска**: Терминал / Консоль

---

## ⚙️ Функциональность

- ✅ Много пользователей могут подключаться к серверу  
- ✅ Передача сообщений между клиентами  
- ✅ Многопоточность для параллельной обработки клиентов  
- ✅ Логирование событий на стороне сервера  
- ⏳ В планах: графический интерфейс (GUI), авторизация, шифрование

---

## 📦 Установка и запуск

```bash
# 1. Клонировать репозиторий
git clone https://github.com/MuratOfficial/chat-app-with-tutorial.git
cd chat-app-with-tutorial

# 2. Убедитесь, что установлен Python 3
python --version

# 3. Запуск сервера (в одном терминале)
python server.py

# 4. Запуск клиента (в другом терминале)
python client.py
```

*Повторите шаг 4 в новых терминалах для подключения дополнительных клиентов.*

## 📁 Структура проекта

`text
chat-app-with-tutorial/
│
├── server.py      # Сервер чата
├── client.py      # Клиент чата
└── README.md
`

## 📌 Планы на будущее

* Поддержка GUI (например, с Tkinter или PyQt)
* Авторизация пользователей
* Шифрование сообщений
* Сохранение истории чата
* Веб-версия (Flask / FastAPI + WebSocket)

## 🤝 Вклад

Буду рад, если ты внесёшь свой вклад! Открыты любые pull request'ы и идеи:

```bash
# Форкни репозиторий
# Создай новую ветку
git checkout -b feature/my-feature

# Внеси изменения и закоммить
git commit -m "Добавил новую фичу"

# Запушь и создай Pull Request
git push origin feature/my-feature
```

## 📄 Лицензия
Проект распространяется под лицензией MIT. Подробнее см. в LICENSE.

<p align="center"><b>Сделано с ❤️ by <a href="https://github.com/MuratOfficial">MuratOfficial</a></b></p>
