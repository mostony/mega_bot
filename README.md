# Бот для шифрования/дешифрования

Бот в Telegram, с помощью которого можно шифровтаь/дешифровать текст тремя шифрами (Цезарь, Виженер и Вернам).

Работу выполнил студент ФКН ПМИ 2 курса Мосин Антон

## Как запустить проект

Проект запускается через Docker командой

```
docker-compose up --build -d
```

Перед запуском необходимо заполнить в директории compose/bot файл `.env` по примеру `.env.sample`

В Telegram написать боту `/start`

# Применяемые технологии

- Docker
- Docker-compose
- Python
- AIOgram
- Redis