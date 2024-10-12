# Полезные команды

## 1. Навигация по файловой системе
- `pwd` — вывести путь к текущей папке.
- `cd /c/...` — смена папки по указанному пути.
- `cd .` — перейти в текущую папку.
- `cd ..` — переход во внешнюю папку.
- `ls` — вывести содержимое папки.
- `ls -a` — вывести скрытые файлы и папки.
- `ls ~` — вывести файлы домашней директории.
- `ls ..` — вывести файлы внешней папки.

## 2. Создание файлов и папок
- `touch file.txt` — создать файл.
- `touch ../folder/filename.txt` — создать файл по указанному пути.
- `touch ~/folder/filename.txt` — создать файл в домашней директории.
- `mkdir folder_name` — создать папку.
- `mkdir -p fold1/fold2/fold3/...` — создать вложенные папки.
- `mkdir ../folder/filename.txt` — создать папку по указанному пути.
- `mkdir ~/folder/filename.txt` — создать папку в домашней директории.

## 3. Копирование, перемещение и удаление
- `cp copied_file1.txt copied_file2.txt to_folder` — копирование файлов.
- `mv file.txt ./folder_name` — перемещение файлов и папок.
- `rm file.txt` — удалить файл.
- `rmdir folder` — удалить папку.
- `rm -r` — рекурсивное удаление файлов и папок.
- `rm -rf .git` — удаление подпапки `.git`.

## 4. Чтение файлов
- `cat filename.txt` — чтение содержимого файла.

## 5. Комбинирование команд
- `&&` — разделение между командами, позволяет выполнять несколько команд в одной строке.

## 6. Git команды
- `git init` — создание репозитория в текущей папке.
- `git status` — проверка состояния репозитория.
- `git add filename.txt` — подготовка файла к коммиту.
- `git add -all` — подготовка всех файлов к коммиту.
- `git add .` — подготовка всех файлов из текущей папки к коммиту.
- `git commit -m 'сообщение'` — создание коммита с сообщением.
- `git log` — просмотр истории коммитов.
- `git push` — отправка изменений на удалённый сервер.
- `git push -u origin main` — первая отправка изменений на удалённый сервер с указанием ветки.

## 7. Работа с SSH
- `ssh-keygen` — генерация SSH-ключа.
- `clip` — скопировать содержимое файла (например, публичный SSH-ключ).
