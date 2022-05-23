**Задать имя пользователя и адрес электронной почты**

git config --global user.name "user"

git config --global user.email "email@example.com"

**Инициализация репозитория**
git init

**Добаление файлов и директорий**

git add [file name]

git add .

**Проверка статуса**

git status

**Создание коммита с сообщением**

git commit -m "massage"

**Промотр истории коммитов**

git log 

git log -p /более подробно

**Просмотр списка изменений для конкретного коммита**

git show хэш коммита

**Просмотр изменений до коммита**

git diff

git diff --staged /более подробно

git diff file_name /для просмора изменений в конкретном файле

**Удаление отслеживаемых файлов и директорий**

git rm [file-name]

git rm -r [dir-name]

git rm dirname/*.html для удаления всех файлов по критерию

**Переименование и перемещение файлов**

Необходимо указать папку источник и папку назанчение

git mv dir1/file_name dir2

