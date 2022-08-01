В этом docker-compose используюся сервисы [line-provider](https://github.com/Lepokurov/line-provider) и [bet-maker](https://github.com/Lepokurov/bet-maker)

Для запуска нужно создать image образы этих сервисов

Секреты передаюся через файлы `settings_local.py`

Сервисы используют fastapi, httx, slqalchemy