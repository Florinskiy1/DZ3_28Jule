git --version - версия git

git config --global user.name"My name"

git config --global user.email my_mail@example.com

git init - инициализация локального репозитория

git status - получить информацию от git о его текущем состоянии

git add - добавить файл или файлы к следующему коммиту

git add . - добавить все файлы к следующему коммиту

git commit -m"message" - создание коммита

git commit -am"message" добавление отслеживаемого файла и создание коммита

git log - вывод на экран истории всех коммитов с их хеш-кодами

git reflog - вывод на экран истории всех коммитов и переходов между ними

git log --oneline - вывод на экран всех коммитов 

git branch "ветка" - создает ветку

git branch -a  - возвращает список имен всех известных веток

git checkout - переход от одного коммита к другому

git checkout master - вернуться к актуальному состоянию и продолжить работу

git diff - увидеть разницу между текущим файлом и закоммиченным файлом

git merge - копирование ветки

git commit --amend  - вы сможете изменить комментарий к последнему коммиту.

git log --graph

git branch - создать ветку

git branch -D  - удалить ветку 

git reset --hard 

git branch <название_ветки> - создание новой ветки

git checkout -b <название_ветки> - создание новой ветки

git reset  - удаление коммитов

git log --graph - сравнение веток

git remote add origin https://github.com/Florinskiy1/1001.git

git branch -M main

git push -u origin main

git pull - слияние

git push --set-upstream origin vetka1

git push origin --delete <branchName>

git branch -d feature/somefeature1.

https://github.com/TimurIslamgulov/DZ3

git checkout origin main

git fetch origin

git checkout -b <название ветки> origin/<название ветки>

git reset id --hard, где id это идентификатор коммита, который хотите просмотреть. 

# Работа с удаленным репозиторием

## Создаем новую ветку main

git remote add origin https://github.com/name/repozitoriy.git

git branch -M main

git push -u origin main

Чем отличаются команды git push и git pull?
Например, «git push» означает мерж локальных изменений в удаленный репозиторий, а «git pull» — наоборот, мерж изменений из удаленного репозитория в локальный.
## Создаем новую ветку
git branch vetka1

git push --set-upstream origin vetka1

## Работа с другим репозиторием

pull request — предложение изменения кода в чужом репозитории. Вы делаете форк чужого репозитория (который иногда и сам может быть форком) → производите изменения в своём форке → посредством pull request предлагаете изменения владельцам репозитория, чей форк Вы сделали. 
На GitHub pull request в публичный репозиторий может осуществить любая/ой зарегистрированная/ый участница/участник.
git push origin main
