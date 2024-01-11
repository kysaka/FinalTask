vladisalv@vladisalv-VirtualBox:~$ echo "собаки, кошки, хомяки" > "Домашние животные"

vladisalv@vladisalv-VirtualBox:~$ echo "лошади, верблюды, ослы" > "Вьючные животные"

vladisalv@vladisalv-VirtualBox:~$ cat "Домашние животные" "Вьючные животные" > "Друзья человека"

vladisalv@vladisalv-VirtualBox:~$ cat "Друзья человека"

собаки, кошки, хомяки

лошади, верблюды, ослы

vladisalv@vladisalv-VirtualBox:~$ mkdir Kennel

vladisalv@vladisalv-VirtualBox:~$ cd ~/Kennel

vladisalv@vladisalv-VirtualBox:~$ mv "Друзья человека" ~/Kennel

vladisalv@vladisalv-VirtualBox:~$ sudo wget https://dev.mysql.com/get/mysql-apt-config_0.8.23-1_all.deb

vladisalv@vladisalv-VirtualBox:~$ sudo dpkg -i mysql-apt-config_0.8.23-1_all.deb

vladisalv@vladisalv-VirtualBox:~$ sudo apt-get update

vladisalv@vladisalv-VirtualBox:~$ sudo apt-get install mysql-server

vladisalv@vladisalv-VirtualBox:~$ sudo wget https://download.docker.com/linux/ubuntu/dists/jammy/pool/stable/amd64/docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb

vladisalv@vladisalv-VirtualBox:~$ sudo dpkg -i docker-ce-cli_20.10.13~3-0~ubuntu-jammy_amd64.deb

vladisalv@vladisalv-VirtualBox:~$ sudo dpkg -r docker-ce

(Чтение базы данных … на данный момент установлено 190154 файла и каталога.)

Удаляется docker-ce (5:24.0.6-1~ubuntu.22.04~jammy) …

vladisalv@vladisalv-VirtualBox:~$ sudo dpkg -r docker-ce-cli

(Чтение базы данных … на данный момент установлено 190145 файлов и каталогов.)

Удаляется docker-ce-cli (5:20.10.13~3-0~ubuntu-jammy) …

Обрабатываются триггеры для man-db (2.10.2-1) …