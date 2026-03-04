# Tgbot
🤖 Мой персональный AI-агент
Telegram бот с памятью, который работает в фоне.
Что умеет
💻 Пишет код через DeepSeek (до 8000+ строк)
🧠 Объясняет темы через Gemini
📚 Запоминает всю историю переписки
📲 Работает в фоне пока ты занят
🔔 Уведомляет когда готово
Команды бота
/start — запустить бота
/memory — посмотреть что агент помнит
/clear — очистить историю
Как задеплоить на Railway
Создай аккаунт на railway.app
Нажми "New Project" → "Deploy from GitHub"
ИЛИ "New Project" → "Empty Service"
Загрузи эти файлы:
bot.py
requirements.txt
Procfile
Railway сам запустит бота!
Файлы проекта
bot.py — основной код бота
requirements.txt — библиотеки
Procfile — инструкция для Railway
memory.json — создаётся автоматически (память бота)
