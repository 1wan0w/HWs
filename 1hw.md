1) Посмотреть где я —> `pwd`
2) Создать папку —> `mkdir x-folder`
3) Зайти в папку —> `cd x-folder`
4) Создать 3 папки —> `mkdir a-folder b-folder c-folder`
5) Зайти в любоую папку —> cd a-folder
6) Создать 5 файлов (3 txt, 2 json) —> `touch a.txt b.txt c.txt d.json e.json`
7) Создать 3 папки —> `mkdir a1f a2f a3f`
8) Вывести список содержимого папки —> `ls`
9) Открыть любой txt файл —> `vim a.txt`
10) Написать туда что-нибудь, любой текст —> `Tap [i] and input «Hello, world:)»`
11) Сохранить и выйти —> `Tap [Esc] and input «:wq»`
12) Выйти из папки на уровень выше —> `cd ..`
13) переместить любые 2 файла, которые вы создали, в любую другую папку —> `mv d.json e.json a2f`
14) скопировать любые 2 файла, которые вы создали, в любую другую папку —> `cp d.json e.json ~/x-folder/a-folder`
15) Найти файл по имени —> `mdfind e.json`
16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает —> `grep -i -c l a.txt`
17) вывести несколько первых строк из текстового файла —> `sed -n '1,2'p a.txt`
18) вывести несколько последних строк из текстового файла —> `sed -n '$'p a.txt` 
19) просмотреть содержимое длинного файла (команда less) изучите как она работает —> `less a.txt`
20) вывести дату и время —> `date`


Задание *
1) Отправить http запрос на сервер.
http://162.55.220.72:5005/terminal-hw-request —> `get http://162.55.220.72:5005`
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

`#!/bin/bash</br>
#Create folder</br>
mkdir autopapka</br>
#Open folder</br>
cd autopapka</br>
#Create 3 folders in autopapka</br>
mkdir af1 af2 af3</br>
#Open af1</br>
cd af1</br>
#Create 5 file:3txt and 2json</br>
touch 1.txt 2.txt 3.txt x.json y.json</br>
#Create 3 folders</br>
mkdir f1 f2 f3</br>
#Show me your body</br>
ls</br>
#Move 2 json-file in f1</br>
mv x.json y.json f1`</br>
