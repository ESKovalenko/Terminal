# Terminal
## Homework_1
1) Посмотреть где я `pwd`
2) Создать папку `mkdir new_1`
3) Зайти в папку `cd new_1`
4) Создать 3 папки `mkdir new_2 new_3 new_4`
5) Зайти в любоую папку `cd new_4`
6) Создать 5 файлов (3 txt, 2 json) `touch Test1.txt Test2.txt Test3.txt Test4.json Test5.json`
7) Создать 3 папки `mkdir dir_1 dir_2 dir_3`
8. Вывести список содержимого папки `ls -la`
9) + Открыть любой txt файл `vim Test1.txt`
10) + написать туда что-нибудь, любой текст.
11) + сохранить и выйти.
12) Выйти из папки на уровень выше `cd .`

13) переместить любые 2 файла, которые вы создали, в любую другую папку.
`mv new_4/Test1.txt new_4/Test2.txt new_2`

14) скопировать любые 2 файла, которые вы создали, в любую другую папку.
`cp new_2/Test1.txt new_2/Test2.txt new_3`

15) Найти файл по имени `find . name Test*.txt`

16) просмотреть содержимое в реальном времени (команда grep) изучите как она работает `tail -f Test1.txt`

17) вывести несколько первых строк из текстового файла `head -n3 Test1.txt`
18) вывести несколько последних строк из текстового файла `tail n3 Test1.txt`
19) просмотреть содержимое длинного файла (команда less) изучите как она работает. `less Test1.txt`
20) вывести дату и время `date`


## Задание *

1) Отправить http запрос на сервер. http://162.55.220.72:5005/terminal-hw-request

`curl http://162.55.220.72:5005/terminal-hw-request`

2) Написать скрипт который выполнит автоматически пункты 3, 4, 5, 6, 7, 8, 13

`touch myscript.sh`

`vim myscript.sh`

`cd new_1`

`mkdir new_2 new_3 new_4`

`cd new_4`

`touch Test1.txt Test2.txt Test3.txt Test4.json Test5.json`

`mkdir dir_1 dir_2 dir_3`

`ls -la`

`mv new_4/Test1.txt new_4/Test2.txt new_2`

`sh myscript.sh`
