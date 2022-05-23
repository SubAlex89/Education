Изучаем гит.

Проверка установки:
	git --version

Базовые настройки:
	задаем имя пользователя
	git config --global user.name "my name"

	задаем адрес электронной почты
	git config -- global user.email "email@example.com"

Создание репозитория:
	git init

Очистка репозитория:
	-d включая директории, -x включая игнорируемые файлы, -f принудительная
	git clean | -dxf

Удаление файлов и директорий:
	git rm [file-name]
	git rm -r [dir-nam]

