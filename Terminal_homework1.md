Первая часть первого  ДЗ  ))
Linux terminal (GitBash) commands

1) Посмотреть где я
```
pwd
```
2) Создать папку
```
mkdir terminal_hw1
```
3) Зайти в папку
```
cd  terminal_hw1
```
4) Создать 3 папки
```
mkdir folder1 
mkdir folder2
mkdir folder3
```
5) Зайти в любоую папку
```
cd folder1
```
6) Создать 5 файлов (3 txt, 2 json)
```
touch file1.txt
touch file2.txt
touch file3.txt
touch file_1.json
touch file_2.json
```
7) Создать 3 папки
```
mkdir prefolder_1
mkdir prefolder_2
mkdir prefolder_3
 ```
8) Вывести список содержимого папки
```
ls -la
```
9)  Открыть любой txt файл
```
cat > file1.txt
or
nano ~/qa/terminal_hw1/folder1/file1.txt
 ```
10) написать туда что-нибудь, любой текст.
```
Dubchak
Lesia
Prokopivna
Maksym
```
11) сохранить и выйти.
```
Ctrl+C
or
Ctrl+x
```
12) Выйти из папки на уровень выше
```
cd ..
```
13) переместить любые 2 файла, которые вы создали, в любую другую папку.
```
 mv -t prefolder_1/ file1.txt file2.txt
```
14) скопировать любые 2 файла, которые вы создали, в любую другую папку.
```
 cp folder1/{file_1.json,file_2.json} folder3
```
15) Найти файл по имени
```
find -name file3.txt
```
16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает.
``` 
 tail -f folder1/file3.txt
```
17) вывести несколько первых строк из текстового файла
```
head -n 4 folder1/file3.txt
```
18) вывести несколько последних строк из текстового файла
```
tail -n 4 folder1/file3.txt
```
19) просмотреть содержимое длинного файла (команда less) изучите как она работает.
```
less folder1/file3.txt
```
20) вывести дату и время
```
date
```
=========

Задание *
1) Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request
 ```
 curl http://162.55.220.72:5005/terminal-hw-request
```
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13
```
 nano script.sh
 bash script.sh

```
