# <span style="color:lightblue">Комманды в терминале</span>

***
## <span style="color:orange">Directory Navigation (<span style="color:green">Навигация по каталогу</span>)</span>

<span style="color:yellow">  

* **cd ..**   <span style="color:lightblue">  - <ins>_**move up one level in the directory tree structure**_ (*перейти на один уровень вверх в структуре дерева каталогов*)</ins></span>
* **cd** <span style="color:lightblue">  - <ins>_**change directory to $HOME**_ (*сменить каталог на $HOME*)</ins></span>
* **cd/chosen/directory** <span style="color:lightblue">  - <ins>_**change to specified directory**_ (*перейти в указанный каталог*)</ins></span>

</span>

***
## <span style="color:orange">File Commands (<span style="color:green">Файловые команды</span>)</span>

<span style="color:yellow">

* **ls** <span style="color:lightblue">  - <ins>_**list files in directory**_ (*список файлов в директории*)</ins></span>
* **ls -a** <span style="color:lightblue">  - <ins>_**list all files, including hidden**_ (*список всех файлов, включая скрытые*)</ins></span>
* **pwd** <span style="color:lightblue">  - <ins>_**show the directory currently working in**_ (*показать каталог, в котором в данный момент работает*)</ins></span>
* **mkdir [directory]** <span style="color:lightblue">  - <ins>_**create a new directory**_ (*создать новый каталог*)</ins></span>
* **rm [file_name]** <span style="color:lightblue">  - <ins>_**remove a file**_ (*удалить файл*)</ins></span>
* **rm -r [directory_name]** <span style="color:lightblue">  - <ins>_**remove a directory recursively**_ (*удалить каталог рекурсивно*)</ins></span>
* **rm -rf [directory_name]** <span style="color:lightblue">  - <ins>_**remove a directory recursively without requiring confirmation**_ (*удалить каталог рекурсивно, не требуя подтверждения*)</ins></span>
* **cp [file_name1] [file_name2]** <span style="color:lightblue">  - <ins>_**copy the contents of the first file to the second file**_ (*скопировать содержимое первого файла во второй файл*)</ins></span>
* **cp -r [directory_name1] [directory_name2]** <span style="color:lightblue">  - <ins>_**recursively copy the contents of the first directory into the second directory**_ (*рекурсивно скопировать содержимое первого каталога во второй каталог*)</ins></span>
* **mv [file_name1] [file_name2]** <span style="color:lightblue">  - <ins>_**rename file_name1 to file_name2**_ (*переименовать имя_файла1 в имя_файла2*)</ins></span>
* **ln -s /path/to[file_name] [link_name]** <span style="color:lightblue">  - <ins>_**create a symbolic link to a file**_ (*создать символическую ссылку на файл*)</ins></span>
* **touch [file_name]** <span style="color:lightblue">  - <ins>_**create a new file**_ (*создать новый файл*)</ins></span>
* **more [file_name]** <span style="color:lightblue">  - <ins>_**show the contents of a file**_ (*показать содержимое файла*)</ins></span>
* **head [file_name]** <span style="color:lightblue">  - <ins>_**show the first 10 lines of a file**_ (*показать первые 10 строк файла*)</ins></span>
* **tail [file_name]** <span style="color:lightblue">  - <ins>_**show the last 10 lines of a file**_ (*показать последние 10 строк файла*)</ins></span>
* **gpg -c [file_name]** <span style="color:lightblue">  - <ins>_**encrypt a file**_ (*зашифровать файл*)</ins></span>
* **gpg [file_name.gpg]** <span style="color:lightblue">  - <ins>_**decrypt a file**_ (*расшифровать файл*)</ins></span>
* **wc** <span style="color:lightblue">  - <ins>_**print the numberof words, lines, and bytes in file**_ (*вывести количество слов, строк и байтов в файле*)</ins></span>

</span>

***
## <span style="color:orange">Users (<span style="color:green">Пользователи</span>)</span>

<span style="color:yellow">

* **id** <span style="color:lightblue">  - <ins>_**show details of the active user**_ (*показать информацию об активном пользователе*)</ins></span>
* **last** <span style="color:lightblue">  - <ins>_**show the last logins onto the system**_ (*показать последние входы в систему*)</ins></span>
* **who** <span style="color:lightblue">  - <ins>_**show who is logged into the system**_ (*показать, кто вошел в систему*)</ins></span>
* **w** <span style="color:lightblue">  - <ins>_**show who is logged in and their activity**_ (*показать, кто вошел в систему и их активность*)</ins></span>
* **groupadd [group_name]** <span style="color:lightblue">  - <ins>_**add a new group**_ (*добавить новую группу*)</ins></span>
* **adduser [user_name]** <span style="color:lightblue">  - <ins>_**add new user**_ (*добавить нового пользователя*)</ins></span>
* **usermod -aG [group_name] [user_name]** <span style="color:lightblue">  - <ins>_**add a user to a group**_ (*добавить пользователя в группу*)</ins></span>
* **userdel [user_name]** <span style="color:lightblue">  - <ins>_**delete a user**_ (*удалить пользователя*)</ins></span>
* **usermod** <span style="color:lightblue">  - <ins>_**use for changing/modifying user information**_ (*использовать для изменения / модификации информации о пользователе*)</ins></span>

</span>

***
## <span style="color:orange">Searching (<span style="color:green">Поиск</span>)</span>

<span style="color:yellow">

* **grep [pattern] [file_name]** <span style="color:lightblue">  - <ins>_**search for a specific pattern in a file**_ (*поиск определенного шаблона в файле*)</ins></span>
* **grep -r [pattern] [directory_name]** <span style="color:lightblue">  - <ins>_**search recursively for a specific pattern in a directory**_ (*рекурсивный поиск определенного шаблона в каталоге*)</ins></span>
* **locate [name]** <span style="color:lightblue">  - <ins>_**find a files and directories by a specific name**_ (*найти файлы и каталоги по определенному имени*)</ins></span>
* **find [/folder/location] -name [a]** <span style="color:lightblue">  - <ins>_**list names that begin with [a] in [/folder/location]**_ (*список имен, начинающихся с [a] в [/папка/расположение]*)</ins></span>
* **find [/folder/location] -size [+100M]** <span style="color:lightblue">  - <ins>_**list files larger than 100M in a particular folder**_ (*список файлов размером более 100M в определенной папке*)</ins></span>

</span>

***
## <span style="color:orange">File Transfer (<span style="color:green">Передача файлов</span>)</span>
<span style="color:yellow">

* **scp [file_name.txt] [server/tmp]** <span style="color:lightblue">  - <ins>_**securely copy a specific file to a server directory**_ (*безопасно скопировать определенный файл в каталог сервера*)</ins></span>
* **rsync -a [your/directory] [/backup/]** <span style="color:lightblue">  - <ins>_**synchronize the contents of a specific directory with a backup directory**_ (*синхронизировать содержимое определенного каталога с резервным каталогом*)</ins></span>

</span>

***
## <span style="color:orange">Network (<span style="color:green">Сеть</span>)</span>

<span style="color:yellow">

* **ip addr show** <span style="color:lightblue">  - <ins>_**show IP addresses and network interface**_ (*показать IP-адреса и сетевой интерфейс*)</ins></span>
* **ip address add [IP_address]** <span style="color:lightblue">  - <ins>_**assign an IP addresses to interface eth0**_ (*назначить IP-адреса интерфейсу eth0*)</ins></span>
* **ifconfig** <span style="color:lightblue">  - <ins>_**show IP addresses of all network interfaces**_ (*показать IP-адреса всех сетевых интерфейсов
*)</ins></span>
* **netstat -pnltu** <span style="color:lightblue">  - <ins>_**show active (listening) posts**_ (*показывать активные (слушающие) посты*)</ins></span>
* **netstat -nutlp** <span style="color:lightblue">  - <ins>_**show tcp and udp ports and their programs **_ (*покажи tcp и udp порты и их программы*)</ins></span>
* **whois [domain]** <span style="color:lightblue">  - <ins>_**show more information about a domain**_ (*показать больше информации о домене*)</ins></span>
* **dig [domain]** <span style="color:lightblue">  - <ins>_**show DNS information about a domain**_ (*показать информацию DNS о домене*)</ins></span>
* **dig -x host** <span style="color:lightblue">  - <ins>_**reverse lookup on domain**_ (*обратный поиск в домене*)</ins></span>
* **dig -x [ip_address]** <span style="color:lightblue">  - <ins>**reverse lookup of an IP address** (*обратный поиск IP-адреса*)</ins></span>
* **host [domain]** <span style="color:lightblue">  - <ins>_**do an IP lookup for a domain**_ (*выполнить поиск IP для домена*)</ins></span>
* **hostname -l** <span style="color:lightblue">  - <ins>_**show the local IP address**_ (*показать локальный IP-адрес*) </span>
* **wget [file_name]** <span style="color:lightblue">  - <ins>_**download a file from a domain**_ (*скачать файл с домена*)</ins></span>

</span>

***
## <span style="color:orange">Hardware Information (<span style="color:green">Информация об оборудовании</span>)</span>

<span style="color:yellow">

* **dmesg** <span style="color:lightblue">  - <ins>_**show boot messages**_(*показать загрузочные сообщения*)</ins></span>
* **cat/proc/cpuinfo** <span style="color:lightblue">  - <ins>_**show CPU information**_(*показать информацию о процессоре*)</ins></span>
* **free -h** <span style="color:lightblue">  - <ins>_**show free and used memory (-m flag indicates memory in MB)**_(*показать свободную и используемую память (флаг -m указывает память в МБ)*)</ins></span>
* **lshw** <span style="color:lightblue">  - <ins>_**list information about hardware configuration**_(*вывести информацию о конфигурации оборудования*)</ins></span>
* **lsblk** <span style="color:lightblue">  - <ins>_**list information about block devices**_(*вывести информацию о блочных устройствах*)</ins></span>
* **lspci -tv** <span style="color:lightblue">  - <ins>_**show PCI devices in a tree-like diagram**_(*показать устройства PCI в виде древовидной схемы*)</ins></span>
* **lsusb -tv** <span style="color:lightblue">  - <ins>_**show USB devices in tree-like diagram**_(*показать USB-устройства в древовидной диаграмме*)</ins></span>
* **dmidecode** <span style="color:lightblue">  - <ins>_**show hardware information from the BIOS**_(*показать информацию об оборудовании из BIOS*)</ins></span>
* **hdparm -i/dev/[disk]** <span style="color:lightblue">  - <ins>_**show information about disk data**_(*показать информацию о данных диска*)</ins></span>
* **hdparm -tT/dev/[disk]* <span style="color:lightblue">  - <ins>_**conduct a read speed test on disk**_(*провести тест скорости чтения на диске*)</ins></span>
* **badblocks -s/dev/[disk]** <span style="color:lightblue">  - <ins>_**test for unreadable blocks on disk**_(*тест на наличие нечитаемых блоков на диске*)</ins></span>

</span>

***
## <span style="color:orange">File Compression (<span style="color:green">Сжатие файлов</span>)</span>

<span style="color:yellow">

* **tar cf [compressed_file.tar][file_name]** <span style="color:lightblue">  - <ins>_**create an archived file from a file**_ (*создать архивный файл из файла*)</ins></span>
* **tar xf [compressed_file.tar]** <span style="color:lightblue">  - <ins>_**extrackt arhived file**_ (*извлечь файл из архива*)</ins></span>
* **tar czf [compressed_file.gz]** <span style="color:lightblue">  - <ins>_**create a gzip compressed tar file**_ (*создать сжатый tar-файл gzip*)</ins></span>
* **gzip [file_name]** <span style="color:lightblue">  - <ins>_**compress a file with the .gz extension**_ (*сжать файл с расширением .gz*)</ins></span>

</span>

***
## <span style="color:orange">Package Installation (<span style="color:green">поиск</span>)</span>

<span style="color:yellow">

* **yum search [keyword]** <span style="color:lightblue">  - <ins>_**find a package by a related keyword**_ (*найти пакет по родственному ключевому слову*)</ins></span>
* **yum info [package_name]** <span style="color:lightblue">  - <ins>_**show package information and summary**_ (*показать информацию о пакете и сводку*)</ins></span>
* **yum install [package_name.rmp]** <span style="color:lightblue">  - <ins>_**install a package usin the YUM package manager**_ (*установить пакет с помощью менеджера пакетов YUM*)</ins></span>

* **dnf install [package_name.rmp]** <span style="color:lightblue">  - <ins>_**install a package using the DNF package manager**_ (*установить пакет с помощью менеджера пакетов DNF*)</ins></span>
* **rpm -i [package_name.rmp]** <span style="color:lightblue">  - <ins>_**install an rpm from a local file**_ (*установить rpm из локального файла*)</ins></span>
* **rpm -e [package_name.rmp]** <span style="color:lightblue">  - <ins>_**remove an rmp package**_ (*удалить пакет rmp*)</ins></span>
* **tar zxvf [source_code.tar.gz] cd [source_code]./configure make make install** <span style="color:lightblue">  - <ins>_**install software from source code**_ (*установить программу из исходного кода*)</ins></span>

</span>

***
## <span style="color:orange">Process Related (<span style="color:green">Связанный с процессом</span>)</span>

<span style="color:yellow">

* **ps** <span style="color:lightblue">  - <ins>_**show a snapshot of active processes**_ (*показать снимок активных процессов*)</ins></span>
* **pstree** <span style="color:lightblue">  - <ins>_**show processes as a tree**_ (*показать процессы в виде дерева*)</ins></span>
* **pmap** <span style="color:lightblue">  - <ins>_**shows a memory usage map of processes**_ (*показывает карту использования памяти процессов*)</ins></span>
* **top** <span style="color:lightblue">  - <ins>_**show all running processes**_ (*показать все запущенные процессы*)</ins></span>
* **kill [process_id]** <span style="color:lightblue">  - <ins>_**kill a process under a given ID**_ (*убить процесс под заданным ID*)</ins></span>
* **pkill [proc_name]* <span style="color:lightblue">  - <ins>_**kill a processes under the specified name**_ (*убить процессы под указанным именем*)</ins></span>
* **killall [proc_name]** <span style="color:lightblue">  - <ins>_**kill all processes labelled proc**_ (*убить все процессы с пометкой proc*)</ins></span>
* **bg** <span style="color:lightblue">  - <ins>_**list and resume stopped jobs in the background**_ (*список и возобновление остановленных заданий в фоновом режиме*)</ins></span>
* **fg** <span style="color:lightblue">  - <ins>_**bring the most recent suspended jop to the foreground**_ (*вывести на передний план самый последний приостановленный прыжок*)</ins></span>
* **fg [job]** <span style="color:lightblue">  - <ins>_**bring a particular job to the foreground**_ (*вывести конкретную работу на передний план*)</ins></span>
* **lsof** <span style="color:lightblue">  - <ins>_**list files opened by processes**_ (*список файлов, открытых процессами*)</ins></span>

</span>

***
## <span style="color:orange">Disk Usage (<span style="color:green">Использование диска</span>)</span>

<span style="color:yellow">

* **finger** <span style="color:lightblue">  - <ins>_**show**_ (*показать*)</ins></span>
* **df -h** <span style="color:lightblue">  - <ins>_**show free and used space on mounted systems**_ (*показать свободное и занятое пространство на смонтированных системах*)</ins></span>
* **df -i** <span style="color:lightblue">  - <ins>_**show free inodes on mounted filesystems**_ (*показать свободные индексы в смонтированных файловых системах*)</ins></span>
* **fdisk -l** <span style="color:lightblue">  - <ins>_**show disk partitions, sizes, and types**_ (*показать разделы диска, размеры и типы*)</ins></span>
* **du -ah** <span style="color:lightblue">  - <ins>_**show disk usage for all files and directory**_ (*показать использование диска для всех файлов и каталогов*)</ins></span>
* **du -sh** <span style="color:lightblue">  - <ins>_**show disk usage of current directory**_ (*показать использование диска в текущем каталоге*)</ins></span>
* **findmnt** <span style="color:lightblue">  - <ins>_**show target mount point for all filesystem**_ (*показать целевую точку монтирования для всей файловой системы*)</ins></span>
* **mount [devices_path] [mouth_point]** <span style="color:lightblue">  - <ins>_**mount a device**_ (*смонтировать устройство*)</ins></span>


</span>

***
## <span style="color:orange">Keyboard Shortcuts (<span style="color:green">Горячие клавиши</span>)</span>

<span style="color:yellow">

* **Ctrl + C** <span style="color:lightblue">  - <ins>_**kill current process running in the terminal**_ (*убить текущий процесс, запущенный в терминале*)</ins></span>
* **Ctrl + Z** <span style="color:lightblue">  - <ins>_**stop current process (can be resumed in the foreground with fg or in the backround with bg**_ (*остановить текущий процесс (можно возобновить на переднем плане с помощью fg или в фоновом режиме с помощью bg*)</ins></span>
* **Ctrl + W** <span style="color:lightblue">  - <ins>_**cut one word before the cursor and add it to clipboar**_ (*вырезать одно слово перед курсором и добавить его в буфер обмена*)</ins></span>
* **Ctrl + U** <span style="color:lightblue">  - <ins>_**cut part of the line before the cursor and add it to clipboard**_ (*вырезать часть строки перед курсором и добавить в буфер обмена*)</ins></span>
* **Ctrl + K** <span style="color:lightblue">  - <ins>_**cut part of the line after the cursor and add it to clipboard**_ (*вырезать часть строки после курсора и добавить в буфер обмена*)</ins></span>
* **Ctrl + Y** <span style="color:lightblue">  - <ins>_**past from clipboard**_ (*прошлое из буфера обмена*)</ins></span>
* **Ctrl + R** <span style="color:lightblue">  - <ins>_**recall last command that matches the provided characters**_ (*вызвать последнюю команду, которая соответствует предоставленным символам
*)</ins></span>
* **Ctrl + O** <span style="color:lightblue">  - <ins>_**run the previously recalled command**_ (*запустить ранее вызванную команду*)</ins></span>
* **Ctrl + G** <span style="color:lightblue">  - <ins>_**show**_ (*показать*)</ins></span>
* **!!** <span style="color:lightblue">  - <ins>_**repat the last command**_ (*повторить последнюю команду*)</ins></span>
* **exit** <span style="color:lightblue">  - <ins>_**log out of current session**_ (*выйти из текущей сессии*)</ins></span>


</span>

***
## <span style="color:orange">System Information (<span style="color:green">Системная информация</span>)</span>

<span style="color:yellow"> 

* **uname -r** <span style="color:lightblue">  - <ins>_**show system information**_ (*показать системную информацию*)</ins></span>
* **uname -a** <span style="color:lightblue">  - <ins>_**show kernel release information**_ (*показать информацию о выпуске ядра*)</ins></span>
* **uptime** <span style="color:lightblue">  - <ins>_**show how long the system has been running, including load averege**_ (*показать, как долго работает система, включая среднюю загрузку*)</ins></span>
* **hostname** <span style="color:lightblue">  - <ins>_**show system hostname**_ (*показать системное имя хоста*)</ins></span>
* **host name -i** <span style="color:lightblue">  - <ins>_**show the IP adress of the system**_ (*показать IP-адрес системы*)</ins></span>
* **last reboot** <span style="color:lightblue">  - <ins>_**show system reboot history**_ (показать историю перезагрузки системы)</ins></span>
* **date** <span style="color:lightblue">  - <ins>_**show current time and date**_ (*показать текущее время и дату*)</ins></span>
* **timedatectl** <span style="color:lightblue">  - <ins>_**query and change the system clock**_ (*запросить и изменить системные часы*)</ins></span>
* **cal** <span style="color:lightblue">  - <ins>_**show current calender month and day**_ (*показать текущий календарный месяц и день*)</ins></span>
* **w** <span style="color:lightblue">  - <ins>_**show logged in users in the system**_ (*показать зарегистрированных пользователей в системе*)</ins></span>
* **whoami** <span style="color:lightblue">  - <ins>_**show user you are using**_ (*показать пользователя, которого вы используете*)</ins></span>
* **finger[username]** <span style="color:lightblue">  - <ins>_**show information about a user**_ (*показать информацию о пользователе*)</ins></span>

</span>

***
## <span style="color:orange">SSH Login (<span style="color:green">Вход по SSH</span>)</span>

<span style="color:yellow">

* **ssh user@host** <span style="color:lightblue">  - <ins>_**connect to host as user**_ (*подключиться к хосту как пользователь*)</ins></span>
* **ssh host** <span style="color:lightblue">  - <ins>_**securely connect to host via SSH default port 22**_ (*безопасно подключаться к хосту через порт SSH по умолчанию 22*)</ins></span>
* **ssh -p [port] user@host** <span style="color:lightblue">  - <ins>_**connect to host using a particular port**_ (*подключиться к хосту, используя определенный порт*)</ins></span>
* **telnet host** <span style="color:lightblue">  - <ins>_**connect to host via telnet default port 23**_ (*подключиться к хосту через порт telnet по умолчанию 23*)</ins></span>

</span>

***
## <span style="color:orange">File Permission (<span style="color:green">Разрешение на файл</span>)</span>

<span style="color:yellow">

* **chmod 777[file_name]** <span style="color:lightblue">  - <ins>_**give read, write, and execute permission to everyone**_ (*дать всем разрешение на чтение, запись и выполнение*)</ins></span>
* **chmod 755[file_name]** <span style="color:lightblue">  - <ins>_**give full permission to owner, and read and execute permission to group and others**_ (*дать полное разрешение владельцу, а также разрешение на чтение и выполнение для группы и других*)</ins></span>
* **chmod 766[file_name]** <span style="color:lightblue">  - <ins>_**give full permission to owner, and read and write permission to group and others**_ (*дать полное разрешение владельцу, а также разрешение на чтение и запись для группы и других*)</ins></span>
* **chown [user] [file_name]** <span style="color:lightblue">  - <ins>_**change the file ownership**_ (*изменить владельца файла*)</ins></span>
* **chown [user]: [group] [file_name]** <span style="color:lightblue">  - <ins>_**change the owner and group ownership of a file**_ (*изменить владельца и группу владения файлом*)</ins></span>

</span>