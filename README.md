# Git & Bash Guide

## Управление директориям

**cd** перемещение к необходимой директории

**pwd** текущая директория

**~** домашняя

**ls -a** скрытые файлы

**touch** новый файл

**mkdir** создание директории

```
mkdir -p dir1/dir-inside/dir-deeper-inside # -p структура директории
```

*# создали папку dir-deeper-inside в папке dir-inside, которая находится в папке dir1*

**mkdir ~/my-git-projects** создание директории в домашней папке

**touch ../../file.txt** создание файла на 2 уровня выше

**cp index.html src/** что копируем и куда

**cp index.html style.css script.js src/** можно много файлов копировать

**cat** чтение файла (текстовые)

**rm example.txt** удаление файла

**rmdir images** удаление директории (без параметра удаляет только пустые папки)

**rm -r images** (-r удаляет с содержимым) **рекурсивно** удаляет файлы и папки

**&&** несколько команд сразу

**mkdir second-project && cd second-project && touch index.html style.css**

## Работа с локальным Git

```
git config --global [user.name](http://user.name/) "Tarasov Alexander"

git config --global user.email [aleksandrtarasov53@gmail.com](mailto:aleksandrtarasov53@gmail.com)
```

[Шпаргалка. Базовые команды в консоли](https://practicum.yandex.ru/trainer/git-basics/lesson/fe0bcd71-f592-423b-bb81-27c37a6a115b/)

```
git init
git status
git add .
git commit -m “”
git log
```

[Генерация SSH ключа](https://practicum.yandex.ru/trainer/git-basics/lesson/42435683-0922-4231-bfb4-d7d32d61f50a/)

```
git remote add origin git@github.com:tar-alexander/Training-C.git
git branch -M main
git push -u origin main
```

[Гайд по README.md](https://practicum.yandex.ru/trainer/git-basics/lesson/c6b9607c-e8bc-4446-89f9-c74522c3492f/)
