# <span style="color:lightblue">Комманды в терминале</span>

***
# <span style="color:orange">Directory Navigation (<span style="color:green">Навигация по каталогу</span>)</span>

<span style="color:yellow">  

* **cd ..**   <span style="color:lightblue">  - **move up one level in the directory tree structure** (*перейти на один уровень вверх в структуре дерева каталогов*) </span>
* **cd** <span style="color:lightblue">  - **change directory to $HOME** (*сменить каталог на $HOME*) </span>
* **cd/chosen/directory** <span style="color:lightblue">  - **change to specified directory** (*перейти в указанный каталог*) </span>

</span>

***
# <span style="color:orange">File Commands (<span style="color:green">Файловые команды</span>)</span>

<span style="color:yellow">

* **ls** <span style="color:lightblue">  - **list files in directory** (*список файлов в директории*) </span>
* **ls -a** <span style="color:lightblue">  - **list all files, including hidden** (*список всех файлов, включая скрытые*) </span>
* **pwd** <span style="color:lightblue">  - **show the directory currently working in** (*показать каталог, в котором в данный момент работает*) </span>
* **mkdir [directory]** <span style="color:lightblue">  - **create a new directory** (*создать новый каталог*) </span>
* **rm [file_name]** <span style="color:lightblue">  - **remove a file** (*удалить файл*) </span>
* **rm -r [directory_name]** <span style="color:lightblue">  - **remove a directory recursively** (*удалить каталог рекурсивно*) </span>
* **rm -rf [directory_name]** <span style="color:lightblue">  - **remove a directory recursively without requiring confirmation** (*удалить каталог рекурсивно, не требуя подтверждения*) </span>
* **cp [file_name1] [file_name2]** <span style="color:lightblue">  - **copy the contents of the first file to the second file** (*скопировать содержимое первого файла во второй файл*) </span>
* **cp -r [directory_name1] [directory_name2]** <span style="color:lightblue">  - **recursively copy the contents of the first directory into the second directory** (*рекурсивно скопировать содержимое первого каталога во второй каталог*) </span>
* **mv [file_name1] [file_name2]** <span style="color:lightblue">  - **rename file_name1 to file_name2** (*переименовать имя_файла1 в имя_файла2*) </span>
* **ln -s /path/to[file_name] [link_name]** <span style="color:lightblue">  - **create a symbolic link to a file** (*создать символическую ссылку на файл*) </span>
* **touch [file_name]** <span style="color:lightblue">  - **create a new file** (*создать новый файл*) </span>
* **more [file_name]** <span style="color:lightblue">  - **show the contents of a file** (*показать содержимое файла*) </span>
* **head [file_name]** <span style="color:lightblue">  - **show the first 10 lines of a file** (*показать первые 10 строк файла*) </span>
* **tail [file_name]** <span style="color:lightblue">  - **show the last 10 lines of a file** (*показать последние 10 строк файла*) </span>
* **gpg -c [file_name]** <span style="color:lightblue">  - **encrypt a file** (*зашифровать файл*) </span>
* **gpg [file_name.gpg]** <span style="color:lightblue">  - **decrypt a file** (*расшифровать файл*) </span>
* **wc** <span style="color:lightblue">  - **print the numberof words, lines, and bytes in file** (*вывести количество слов, строк и байтов в файле*) </span>

</span>

***
# <span style="color:orange">Users (<span style="color:green">Пользователи</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">Searching (<span style="color:green">Поиск</span>)</span>

<span style="color:yellow">

* **grep [pattern] [file_name]** <span style="color:lightblue">  - **search for a specific pattern in a file** (*поиск определенного шаблона в файле*) </span>
* **grep -r [pattern] [directory_name]** <span style="color:lightblue">  - **search recursively for a specific pattern in a directory** (*рекурсивный поиск определенного шаблона в каталоге*) </span>
* **locate [name]** <span style="color:lightblue">  - **find a files and directories by a specific name** (*найти файлы и каталоги по определенному имени*) </span>
* **find [/folder/location] -name [a]** <span style="color:lightblue">  - **list names that begin with [a] in [/folder/location]** (*список имен, начинающихся с [a] в [/папка/расположение]*) </span>
* **find [/folder/location] -size [+100M]** <span style="color:lightblue">  - **list files larger than 100M in a particular folder** (*список файлов размером более 100M в определенной папке*) </span>

</span>

***
# <span style="color:orange">File Transfer (<span style="color:green">Передача файлов</span>)</span>
<span style="color:yellow">

* **scp [file_name.txt] [server/tmp]** <span style="color:lightblue">  - **securely copy a specific file to a server directory** (*безопасно скопировать определенный файл в каталог сервера*) </span>
* **rsync -a [your/directory] [/backup/]** <span style="color:lightblue">  - **synchronize the contents of a specific directory with a backup directory** (*синхронизировать содержимое определенного каталога с резервным каталогом*) </span>

</span>

***
# <span style="color:orange">Network (<span style="color:green">Сеть</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">Hardware Information (<span style="color:green">Информация об оборудовании</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">File Compression (<span style="color:green">Сжатие файлов</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">Package Installation (<span style="color:green">поиск</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">Process Related (<span style="color:green">Связанный с процессом</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">Disk Usage (<span style="color:green">Использование диска</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">Keyboard Shortcuts (<span style="color:green">Горячие клавиши</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - **show** (*показать*) </span>

</span>

***
# <span style="color:orange">System Information (<span style="color:green">Системная информация</span>)</span>

<span style="color:yellow"> 

* **uname -r** <span style="color:lightblue">  - **show system information** (*показать системную информацию*) </span>
* **uname -a** <span style="color:lightblue">  - **show kernel release information** (*показать информацию о выпуске ядра*) </span>
* **uptime** <span style="color:lightblue">  - **show how long the system has been running, including load averege** (*показать, как долго работает система, включая среднюю загрузку*) </span>
* **hostname** <span style="color:lightblue">  - **show system hostname** (*показать системное имя хоста*) </span>
* **host name -i** <span style="color:lightblue">  - **show the IP adress of the system** (*показать IP-адрес системы*) </span>
* **last reboot** <span style="color:lightblue">  - **show system reboot history** (показать историю перезагрузки системы) </span>
* **date** <span style="color:lightblue">  - **show current time and date** (*показать текущее время и дату*) </span>
* **timedatectl** <span style="color:lightblue">  - **query and change the system clock** (*запросить и изменить системные часы*) </span>
* **cal** <span style="color:lightblue">  - **show current calender month and day** (*показать текущий календарный месяц и день*) </span>
* **w** <span style="color:lightblue">  - **show logged in users in the system** (*показать зарегистрированных пользователей в системе*) </span>
* **whoami** <span style="color:lightblue">  - **show user you are using** (*показать пользователя, которого вы используете*) </span>
* **finger[username]** <span style="color:lightblue">  - **show information about a user** (*показать информацию о пользователе*) </span>

</span>

***
# <span style="color:orange">SSH Login (<span style="color:green">Вход по SSH</span>)</span>

<span style="color:yellow">

* **ssh user@host** <span style="color:lightblue">  - **connect to host as user** (*подключиться к хосту как пользователь*) </span>
* **ssh host** <span style="color:lightblue">  - **securely connect to host via SSH default port 22** (*безопасно подключаться к хосту через порт SSH по умолчанию 22*) </span>
* **ssh -p [port] user@host** <span style="color:lightblue">  - **connect to host using a particular port** (*подключиться к хосту, используя определенный порт*) </span>
* **telnet host** <span style="color:lightblue">  - **connect to host via telnet default port 23** (*подключиться к хосту через порт telnet по умолчанию 23*) </span>

</span>

***
# <span style="color:orange">File Permission (<span style="color:green">Разрешение на файл</span>)</span>

<span style="color:yellow">

* **chmod 777[file_name]** <span style="color:lightblue">  - **give read, write, and execute permission to everyone** (*дать всем разрешение на чтение, запись и выполнение*) </span>
* **chmod 755[file_name]** <span style="color:lightblue">  - **give full permission to owner, and read and execute permission to group and others** (*дать полное разрешение владельцу, а также разрешение на чтение и выполнение для группы и других*) </span>
* **chmod 766[file_name]** <span style="color:lightblue">  - **give full permission to owner, and read and write permission to group and others** (*дать полное разрешение владельцу, а также разрешение на чтение и запись для группы и других*) </span>
* **chown [user] [file_name]** <span style="color:lightblue">  - **change the file ownership** (*изменить владельца файла*) </span>
* **chown [user]: [group] [file_name]** <span style="color:lightblue">  - **change the owner and group ownership of a file** (*изменить владельца и группу владения файлом*) </span>

</span>