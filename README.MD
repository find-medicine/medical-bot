# Как запустить бота для тестировки
1. Установить python
2. Установить pip
3. Установить [python-telegram-bot](https://github.com/python-telegram-bot/python-telegram-bot)
```console
pip install python-telegram-bot -U --pre
```
4. Установить [python-decouple](https://pypi.org/project/python-decouple/)
5. Создать .env файл в базовой папке проекта и выставить значение API_KEY. Ключ можно получить у BotFather.
```
API_KEY=1234567890:ASD_ASDFGHJK1234567890ASDFGHJKLPOI8
```
## Как получить API Key у BotFather для пятого шага?
Найдите BotFather в телеграме и воспользуйтесь командой /newbot. После нескольких вопросов, вам выдадут ключ. 

[Более подробная инструкция на сайте телеграм](https://core.telegram.org/bots#6-botfather)