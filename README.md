**TERMINAL**
1) Посмотреть где я<br> **->** `pwd`
2) Создать папку<br> **->**`mkdir x-folder`
3) Зайти в папку<br> **->**`cd x-folder`
4) Создать 3 папки<br> **->**`mkdir a-folder b-folder c-folder`
5) Зайти в любоую папку<br> **->** cd a-folder
6) Создать 5 файлов (3 txt, 2 json)<br> **->**`touch a.txt b.txt c.txt d.json e.json`
7) Создать 3 папки<br> **->**`mkdir a1f a2f a3f`
8) Вывести список содержимого папки<br> **->**`ls`
9) Открыть любой txt файл<br> **->**`vim a.txt`
10) Написать туда что-нибудь, любой текст<br> **->**`Tap [i] and input «Hello, world:)»`
11) Сохранить и выйти<br> **->**`Tap [Esc] and input «:wq»`
12) Выйти из папки на уровень выше<br> **->**`cd ..`
13) Переместить любые 2 файла, которые вы создали, в любую другую папку<br> **->**`mv d.json e.json a2f`
14) Скопировать любые 2 файла, которые вы создали, в любую другую папку<br> **->**`cp d.json e.json ~/x-folder/a-folder`
15) Найти файл по имени<br> **->**`mdfind e.json`
16) Просмотреть содержимое в реальном времени (команда grep) изучите как она работает<br> **->**`grep -i -c l a.txt`
17) Вывести несколько первых строк из текстового файла<br> **->**`sed -n '1,2'p a.txt`
18) Вывести несколько последних строк из текстового файла<br> **->**`sed -n '$'p a.txt` 
19) Просмотреть содержимое длинного файла (команда less) изучите как она работает<br> **->**`less a.txt`
20) Вывести дату и время<br> **->**`date`


Задание *
1) Отправить http запрос на сервер http://162.55.220.72:5005/terminal-hw-request<br> **->**`get http://162.55.220.72:5005`
2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13<br> **->**

**#!/bin/bash<br>
#Create folder<br>
mkdir autopapka<br>
#Open folder<br>
cd autopapka<br>
#Create 3 folders in autopapka<br>
mkdir af1 af2 af3<br>
#Open af1<br>
cd af1<br>
#Create 5 file:3txt and 2json<br>
touch 1.txt 2.txt 3.txt x.json y.json<br>
#Create 3 folders<br>
mkdir f1 f2 f3<br>
#Show me your body<br>
ls<br>
#Move 2 json-file in f1<br>
mv x.json y.json f1<br>**

