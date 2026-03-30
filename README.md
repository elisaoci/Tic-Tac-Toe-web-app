# Tic-Tac-Toe with AI

Веб-игра в крестики-нолики против компьютера. ИИ использует алгоритм Минимакс — проиграть невозможно.

## Возможности

- Игра против непобедимого ИИ
- Несколько независимых игр одновременно
- Красивый веб-интерфейс
- Чистая архитектура (domain, datasource, web, di)

## Технологии

- Python 3.8+, Flask
- HTML, CSS

## Структура

src/
- app.py           # точка входа
- datasource/      # хранение данных
- di/              # внедрение зависимостей
- domain/          # бизнес-логика
- helpers/         # вспомогательные функции
- static/          # CSS
- templates/       # HTML-шаблоны
- web/             # контроллеры

## Запуск

```bash
git clone https://github.com/username/tic-tac-toe.git
cd tic-tac-toe
python -m venv venv
source venv/bin/activate   # Windows: venv\Scripts\activate
pip install -r requirements.txt
python src/app.py

Открыть http://127.0.0.1:5000 и играть.
