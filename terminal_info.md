# <span style="color:lightblue">Комманды в терминале</span>

***
# <span style="color:orange">Directory Navigation (<span style="color:green">Навигация по каталогу</span>)</span>

<span style="color:yellow">  

* **cd ..**   <span style="color:lightblue">  - _**move up one level in the directory tree structure**_ (*перейти на один уровень вверх в структуре дерева каталогов*) </span>
* **cd** <span style="color:lightblue">  - _**change directory to $HOME**_ (*сменить каталог на $HOME*) </span>
* **cd/chosen/directory** <span style="color:lightblue">  - _**change to specified directory**_ (*перейти в указанный каталог*) </span>

</span>

***
# <span style="color:orange">File Commands (<span style="color:green">Файловые команды</span>)</span>

<span style="color:yellow">

* **ls** <span style="color:lightblue">  - _**list files in directory**_ (*список файлов в директории*) </span>
* **ls -a** <span style="color:lightblue">  - _**list all files, including hidden**_ (*список всех файлов, включая скрытые*) </span>
* **pwd** <span style="color:lightblue">  - _**show the directory currently working in**_ (*показать каталог, в котором в данный момент работает*) </span>
* **mkdir [directory]** <span style="color:lightblue">  - _**create a new directory**_ (*создать новый каталог*) </span>
* **rm [file_name]** <span style="color:lightblue">  - _**remove a file**_ (*удалить файл*) </span>
* **rm -r [directory_name]** <span style="color:lightblue">  - _**remove a directory recursively**_ (*удалить каталог рекурсивно*) </span>
* **rm -rf [directory_name]** <span style="color:lightblue">  - _**remove a directory recursively without requiring confirmation**_ (*удалить каталог рекурсивно, не требуя подтверждения*) </span>
* **cp [file_name1] [file_name2]** <span style="color:lightblue">  - _**copy the contents of the first file to the second file**_ (*скопировать содержимое первого файла во второй файл*) </span>
* **cp -r [directory_name1] [directory_name2]** <span style="color:lightblue">  - _**recursively copy the contents of the first directory into the second directory**_ (*рекурсивно скопировать содержимое первого каталога во второй каталог*) </span>
* **mv [file_name1] [file_name2]** <span style="color:lightblue">  - _**rename file_name1 to file_name2**_ (*переименовать имя_файла1 в имя_файла2*) </span>
* **ln -s /path/to[file_name] [link_name]** <span style="color:lightblue">  - _**create a symbolic link to a file**_ (*создать символическую ссылку на файл*) </span>
* **touch [file_name]** <span style="color:lightblue">  - _**create a new file**_ (*создать новый файл*) </span>
* **more [file_name]** <span style="color:lightblue">  - _**show the contents of a file**_ (*показать содержимое файла*) </span>
* **head [file_name]** <span style="color:lightblue">  - _**show the first 10 lines of a file**_ (*показать первые 10 строк файла*) </span>
* **tail [file_name]** <span style="color:lightblue">  - **show the last 10 lines of a file** (*показать последние 10 строк файла*) </span>
* **gpg -c [file_name]** <span style="color:lightblue">  - _**encrypt a file**_ (*зашифровать файл*) </span>
* **gpg [file_name.gpg]** <span style="color:lightblue">  - _**decrypt a file**_ (*расшифровать файл*) </span>
* **wc** <span style="color:lightblue">  - _**print the numberof words, lines, and bytes in file**_ (*вывести количество слов, строк и байтов в файле*) </span>

</span>

***
# <span style="color:orange">Users (<span style="color:green">Пользователи</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - _**show**_ (*показать*) </span>

</span>

***
# <span style="color:orange">Searching (<span style="color:green">Поиск</span>)</span>

<span style="color:yellow">

* **grep [pattern] [file_name]** <span style="color:lightblue">  - _**search for a specific pattern in a file**_ (*поиск определенного шаблона в файле*) </span>
* **grep -r [pattern] [directory_name]** <span style="color:lightblue">  - _**search recursively for a specific pattern in a directory**_ (*рекурсивный поиск определенного шаблона в каталоге*) </span>
* **locate [name]** <span style="color:lightblue">  - _**find a files and directories by a specific name**_ (*найти файлы и каталоги по определенному имени*) </span>
* **find [/folder/location] -name [a]** <span style="color:lightblue">  - _**list names that begin with [a] in [/folder/location]**_ (*список имен, начинающихся с [a] в [/папка/расположение]*) </span>
* **find [/folder/location] -size [+100M]** <span style="color:lightblue">  - _**list files larger than 100M in a particular folder**_ (*список файлов размером более 100M в определенной папке*) </span>

</span>

***
# <span style="color:orange">File Transfer (<span style="color:green">Передача файлов</span>)</span>
<span style="color:yellow">

* **scp [file_name.txt] [server/tmp]** <span style="color:lightblue">  - _**securely copy a specific file to a server directory**_ (*безопасно скопировать определенный файл в каталог сервера*) </span>
* **rsync -a [your/directory] [/backup/]** <span style="color:lightblue">  - _**synchronize the contents of a specific directory with a backup directory**_ (*синхронизировать содержимое определенного каталога с резервным каталогом*) </span>

</span>

***
# <span style="color:orange">Network (<span style="color:green">Сеть</span>)</span>

<span style="color:yellow">

* **ip addr show** <span style="color:lightblue">  - _**show IP addresses and network interface**_ (*показать IP-адреса и сетевой интерфейс*) </span>
* **ip address add [IP_address]** <span style="color:lightblue">  - _**assign an IP addresses to interface eth0**_ (*назначить IP-адреса интерфейсу eth0*) </span>
* **ifconfig** <span style="color:lightblue">  - _**show IP addresses of all network interfaces**_ (*показать IP-адреса всех сетевых интерфейсов
*) </span>
* **netstat -pnltu** <span style="color:lightblue">  - _**show active (listening) posts**_ (*показывать активные (слушающие) посты*) </span>
* **netstat -nutlp** <span style="color:lightblue">  - _**show tcp and udp ports and their programs **_ (*покажи tcp и udp порты и их программы*) </span>
* **whois [domain]** <span style="color:lightblue">  - _**show more information about a domain**_ (*показать больше информации о домене*) </span>
* **dig [domain]** <span style="color:lightblue">  - _**show DNS information about a domain**_ (*показать информацию DNS о домене*) </span>
* **dig -x host** <span style="color:lightblue">  - _**reverse lookup on domain**_ (*обратный поиск в домене*) </span>
* **dig -x [ip_address]** <span style="color:lightblue">  - **reverse lookup of an IP address** (*обратный поиск IP-адреса*) </span>
* **host [domain]** <span style="color:lightblue">  - _**do an IP lookup for a domain**_ (*выполнить поиск IP для домена*) </span>
* **hostname -l** <span style="color:lightblue">  - _**show the local IP address**_ (*показать локальный IP-адрес*) </span>
* **wget [file_name]** <span style="color:lightblue">  - _**download a file from a domain**_ (*скачать файл с домена*) </span>

</span>

***
# <span style="color:orange">Hardware Information (<span style="color:green">Информация об оборудовании</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - _**show**_ (*показать*) </span>

</span>

***
# <span style="color:orange">File Compression (<span style="color:green">Сжатие файлов</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - _**show**_ (*показать*) </span>

</span>

***
# <span style="color:orange">Package Installation (<span style="color:green">поиск</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - _**show**_ (*показать*) </span>

</span>

***
# <span style="color:orange">Process Related (<span style="color:green">Связанный с процессом</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - _**show**_ (*показать*) </span>

</span>

***
# <span style="color:orange">Disk Usage (<span style="color:green">Использование диска</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - _**show**_ (*показать*) </span>

</span>

***
# <span style="color:orange">Keyboard Shortcuts (<span style="color:green">Горячие клавиши</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - _**show**_ (*показать*) </span>

</span>

***
# <span style="color:orange">System Information (<span style="color:green">Системная информация</span>)</span>

<span style="color:yellow"> 

* **uname -r** <span style="color:lightblue">  - _**show system information**_ (*показать системную информацию*) </span>
* **uname -a** <span style="color:lightblue">  - _**show kernel release information**_ (*показать информацию о выпуске ядра*) </span>
* **uptime** <span style="color:lightblue">  - _**show how long the system has been running, including load averege**_ (*показать, как долго работает система, включая среднюю загрузку*) </span>
* **hostname** <span style="color:lightblue">  - _**show system hostname**_ (*показать системное имя хоста*) </span>
* **host name -i** <span style="color:lightblue">  - _**show the IP adress of the system**_ (*показать IP-адрес системы*) </span>
* **last reboot** <span style="color:lightblue">  - _**show system reboot history**_ (показать историю перезагрузки системы) </span>
* **date** <span style="color:lightblue">  - _**show current time and date**_ (*показать текущее время и дату*) </span>
* **timedatectl** <span style="color:lightblue">  - _**query and change the system clock**_ (*запросить и изменить системные часы*) </span>
* **cal** <span style="color:lightblue">  - _**show current calender month and day**_ (*показать текущий календарный месяц и день*) </span>
* **w** <span style="color:lightblue">  - _**show logged in users in the system**_ (*показать зарегистрированных пользователей в системе*) </span>
* **whoami** <span style="color:lightblue">  - _**show user you are using**_ (*показать пользователя, которого вы используете*) </span>
* **finger[username]** <span style="color:lightblue">  - _**show information about a user**_ (*показать информацию о пользователе*) </span>

</span>

***
# <span style="color:orange">SSH Login (<span style="color:green">Вход по SSH</span>)</span>

<span style="color:yellow">

* **ssh user@host** <span style="color:lightblue">  - _**connect to host as user**_ (*подключиться к хосту как пользователь*) </span>
* **ssh host** <span style="color:lightblue">  - _**securely connect to host via SSH default port 22**_ (*безопасно подключаться к хосту через порт SSH по умолчанию 22*) </span>
* **ssh -p [port] user@host** <span style="color:lightblue">  - _**connect to host using a particular port**_ (*подключиться к хосту, используя определенный порт*) </span>
* **telnet host** <span style="color:lightblue">  - _**connect to host via telnet default port 23**_ (*подключиться к хосту через порт telnet по умолчанию 23*) </span>

</span>

***
# <span style="color:orange">File Permission (<span style="color:green">Разрешение на файл</span>)</span>

<span style="color:yellow">

* **chmod 777[file_name]** <span style="color:lightblue">  - _**give read, write, and execute permission to everyone**_ (*дать всем разрешение на чтение, запись и выполнение*) </span>
* **chmod 755[file_name]** <span style="color:lightblue">  - _**give full permission to owner, and read and execute permission to group and others**_ (*дать полное разрешение владельцу, а также разрешение на чтение и выполнение для группы и других*) </span>
* **chmod 766[file_name]** <span style="color:lightblue">  - _**give full permission to owner, and read and write permission to group and others**_ (*дать полное разрешение владельцу, а также разрешение на чтение и запись для группы и других*) </span>
* **chown [user] [file_name]** <span style="color:lightblue">  - _**change the file ownership**_ (*изменить владельца файла*) </span>
* **chown [user]: [group] [file_name]** <span style="color:lightblue">  - _**change the owner and group ownership of a file**_ (*изменить владельца и группу владения файлом*) </span>

</span>