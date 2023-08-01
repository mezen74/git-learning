# Конспект по курсу обучения работе с Git

## Работа с локальным репозиторием
### Инициализировать репозиторий
1. Перейдите в нужную папку: `cd <папка с репозиторием>`
1. Выполните команду: `git init`
Если вы случайно сделали Git-репозиторем не ту папку, удалите скрытую подпаку `.git`: `rm -rf .git`
### Проверить состояние репозитория
В папке с репозиторием выполните команду: `git status`
### Добавить файлы в репозиторий
1. Подготовьте файлы к сохранению: `git add`
1. Сохраните изменения файлов: `git commit -m 'Комментарий к коммиту'`
### Посмотреть историю коммитов
В папке с репозиторием выполните команду `git log`

## Работа с удаленным репозиторем
### Связать локальный и удаленный репозитории
1. Создайте удаленный репозиторий через веб-интерфейс GitHub;
1. Привяжите удаленный репозиторий к локальному: `git remote add origin git@github.com:%ИМЯ_АККАУНТА%/%ИМЯ_ПРОЕКТА%.git`
1. Убедитесь, что репозитории связаны: `git remote -v`
### Отправить изменения на удаленный репозиторий
1. Отправка изменений в первый раз: `git push -u origin master`
1. Отправка изменений в последующие разы: `git push`
