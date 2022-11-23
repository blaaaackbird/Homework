~/Course QA$ pwd -
1) Посмотреть где я
/home/karina/Course QA
~/Course QA$ mkdir group_28
2) Создать папку
~/Course QA$ cd group_28/
3) Зайти в папку
~/Course QA/gr fileup_28$
~/Course QA/group_28$ mkdir qa_1 qa_2 qa_3
4) Создать 3 папки
~/Course QA/group_28$ cd qa_1
5) Зайти в любоую папку
~/Course QA/group_28/qa_1$ touch file.txt
6) Создать 5 файлов (3 txt, 2 json)
~/Course QA/group_28/qa_1$ touch file1.txt
~/Course QA/group_28/qa_1$ touch file2.txt
~/Course QA/group_28/qa_1$ touch file3.json
~/Course QA/group_28/qa_1$ touch file4.json
~/Course QA/group_28/qa_1$ mkdir m1 m2 m3
7) Создать 3 папки
~/Course QA/group_28/qa_1$ ls -la
8. Вывести список содержимого папки
итого 20
drwxrwxr-x 5 karina karina 4096 апр 5 23:09 .
drwxrwxr-x 5 karina karina 4096 апр 5 23:01 ..
-rw-rw-r-- 1 karina karina
0 апр 5 23:06 file1.txt
-rw-rw-r-- 1 karina karina
0 апр 5 23:06 file2.txt
-rw-rw-r-- 1 karina karina
0 апр 5 23:06 file3.json
-rw-rw-r-- 1 karina karina
0 апр 5 23:07 file4.json
-rw-rw-r-- 1 karina karina
0 апр 5 23:05 file.txt
drwxrwxr-x 2 karina karina 4096 апр 5 23:09 m1
drwxrwxr-x 2 karina karina 4096 апр 5 23:09 m2
drwxrwxr-x 2 karina karina 4096 апр 5 23:09 m3
~/Course QA/group_28/qa_1$ cat file1.txt
9) + Открыть любой txt файл
~/Course QA/group_28/qa_1$ cat >file1.txt
10) + написать туда что-нибудь, любой текст.
Hi all!
my name is Karina
I am a student of Software Testing
I am 24 years old
^C
11) + сохранить и выйти.
~/Course QA/group_28/qa_1$ cd ..
12) Выйти из папки на уровень выше
~/Course QA/group_28$
~/Course QA/group_28$ mv qa_1/file1.txt qa_1/m1/file1.txt
13) переместить любые 2 файла, которые вы создали, в любую другую папку
~/Course QA/group_28$ mv qa_1/file2.txt qa_1/m2/file.txt
~/Course QA/group_28$ cp qa_1/file.txt qa_1/m1/file.txt
14) скопировать любые 2 файла, которые вы создали, в любую другую папку.
~/Course QA/group_28$ cp qa_1/file.txt qa_1/m2/file.txt
~/Course QA/group_28/qa_1$ find -name "file.txt"
15) Найти файл по имени
./file.txt
./m2/file.txt
./m1/file.txt
~/Course QA/group_28/qa_1/m1$ tail -f file1.txt
16. Просмотреть содержимое в реальном времени
Hi all!
Can u help me?
my name is Karina
I am a student of Software Testing
I am 24 years old
~/Course QA/group_28/qa_1/m1$ cat -n file1.txt
17. вывести несколько последних строк из текстового файла
1 Hi all!
2 Can u help me?
3 my name is Karina
/Course QA/group_28/qa_1/m1$ tail -n3 file1.txt
18. вывести несколько последних строк из текстового файла
my name is Karina
I am a student of Software Testing
I am 24 years old
~/Course QA/group_28/qa_1/m1$ less file1.txt
19) просмотреть содержимое длинного файла
~/Course QA/group_28/qa_1/m1$ date '+DATE: %m/%d/%y%nTIME: %H:%M:%S' 20. вывести дату и время
DATE: 04/06/22
TIME: 01:01:55
