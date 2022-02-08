# Command for working with git
## Налокальном репозитории
| Описание | Команда |
|---------:|:--------|
| Посмотреть конфигурацию global | git config -l |
| Настроить конфигурацию global | git config --global user.name "NAME"  |
|                               | git config --global user.mail "EMAIL" |
| Проверить стату локального репозитория | git status |
|Добавить файлы в индекс репозиторя | git add FILE (конкретный файл)|
|                                   | git add . (все файлы и папки репозитория)|
|Зафиксироват измерения в репозитории| git commit (сообщени нужно ввести в редакторе)|
|                                   | git commit -m "MESSAGE" (сообщение без редактора)|
|                                   | git commit -am "MESSAGE" (а - добавит все измененные файлы в индекс. add и commit в одной команде)|
|Посмотреть лог коммитов            | git log|
|                                   | git log --oneline|
|                                   | git reflog (расширенный лог и восстановление после reset)|