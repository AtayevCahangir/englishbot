# EnglishBot 🇬🇧🤖

**EnglishBot** — это Telegram-бот, написанный на Python, который помогает пользователям изучать английский язык через взаимодействие в чате. Он построен с использованием библиотеки `python-telegram-bot`.

## 📦 Возможности

- Отправка сообщений и команд в Telegram
- Возможность расширения: интеграция переводчиков, заданий, карточек слов и др.
- Простая архитектура, легко дополняется

## 🛠️ Установка и запуск (через Visual Studio Code)

1. **Клонируйте репозиторий:**
   ```bash
   git clone https://github.com/atayevcahangir/englishbot.git
   cd englishbot
Создайте и активируйте виртуальное окружение:

bash
Copy
Edit
python -m venv venv
source venv/bin/activate  # Для Linux/macOS
venv\Scripts\activate     # Для Windows
Установите зависимости:

bash
Copy
Edit
pip install -r requirements.txt
Создайте файл .env (если будете использовать переменные окружения):

Пример:
TOKEN=ваш_бот_токен

Запуск через VS Code:

Откройте папку проекта в VS Code

Убедитесь, что активировано виртуальное окружение

Запустите bot.py или используйте терминал:

bash
Copy
Edit
python bot.py
