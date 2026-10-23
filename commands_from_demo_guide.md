# Команды из «Полный гайд Демо 2027»

> Извлечено автоматически из текстового слоя PDF и распознанных фрагментов скриншотов. Проверяйте команды и IP-адреса перед запуском.

## Команды из текстового слоя PDF

- **Строка PDF 16:** `SSH .......................................................................................................................................... 23`
- **Строка PDF 18:** `FRR.......................................................................................................................................... 28`
- **Строка PDF 25:** `Ansible ..................................................................................................................................... 46`
- **Строка PDF 26:** `Docker ..................................................................................................................................... 47`
- **Строка PDF 38:** `fail2ban .................................................................................................................................... 70`
- **Строка PDF 454:** `rm –r /home/<имя пользователя>`
- **Строка PDF 455:** `userdel <имя пользователя>`
- **Строка PDF 534:** `nano /etc/resolv.conf`
- **Строка PDF 797:** `ip ospf message-digest-key <ID> md5 <пароль> — задаёт MD5-ключ для аутентификации`
- **Строка PDF 807:** `exit — выход из текущего режима.`
- **Строка PDF 829:** `systemctl restart NetworkManager`
- **Строка PDF 830:** `sleep 3`
- **Строка PDF 831:** `systemctl restart frr`
- **Строка PDF 1117:** `adcli: Утилита для выполнения действий в домене Active Directory. Используется для`
- **Строка PDF 1146:** `FRR И DNS, А ТАКЖЕ УБЕДИТЕСЬ, ЧТО ВЕЗДЕ ВЫСТАВЛЕН ВЕРНЫЙ NAMESERVER.`
- **Строка PDF 1205:** `nano /etc/chrony/chrony.conf`
- **Строка PDF 1208:** `systemctl restart chronyd`
- **Строка PDF 1310:** `docker.io — сам движок Docker (среда для запуска и управления контейнерами). В`
- **Строка PDF 1313:** `docker-compose — утилита для запуска многоконтейнерных приложений. Позволяет`
- **Строка PDF 1381:** `mariadb-server — сервер баз данных для хранения информации сайта.`
- **Строка PDF 1382:** `mariadb-client — консольная утилита для управления базой данных.`
- **Строка PDF 1385:** `MariaDB.`
- **Строка PDF 1410:** `EXIT;`
- **Строка PDF 1480:** `ssh sshuser@172.16.1.2 -p 2027`
- **Строка PDF 1485:** `ssh sshuser@172.16.2.2 -p 2027`
- **Строка PDF 1514:** `apt install -y ./Yandex.deb`
- **Строка PDF 1515:** `yandex-browser-stable --no-sandbox`
- **Строка PDF 1867:** `Ansible на BR-SRV:`
- **Строка PDF 2169:** `crontab -l`
- **Строка PDF 2170:** `systemctl status cron`
- **Строка PDF 2187:** `FRR.`

## Команды и конфигурации, распознанные на скриншотах

- **Страница 6:** `root@debian:~# hostnamectl set-hostname isp.au-team.irpo; exec bash`
- **Страница 6:** `root@isp:~# §j`
- **Страница 6:** `root@debian:~# hostnamectl set-hostname hq-rtr.au-team.irpo; exec bash`
- **Страница 6:** `root@hq-rtr:~# ff`
- **Страница 6:** `root@debian:~# hostnamectl set-hostname hq-srv.au-team.irpo; exec bash`
- **Страница 6:** `root@hq-srv:~#`
- **Страница 6:** `root@debian:~# hostnamectl set-hostname hq-cli.au-team.irpo; exec bash`
- **Страница 6:** `root@hq-cli:~# fj`
- **Страница 6:** `root@debian:~# hostnamectl set-hostname br-rtr.au-team.irpo; exec bash`
- **Страница 6:** `root@br-rtr:~#`
- **Страница 6:** `root@debian:~# hostnamectl set-hostname br-fw.au-team.irpo; exec bash`
- **Страница 6:** `root@br-fw:~#`
- **Страница 6:** `root@debian:~# hostnamectl set-hostname br-srv.au-team.irpo; exec bash`
- **Страница 6:** `root@br-srv:~# If`
- **Страница 8:** `root@isp:~# nano /etc/network/interfaces`
- **Страница 8:** `auto lo`
- **Страница 8:** `iface lo inet loopback`
- **Страница 8:** `auto ens3`
- **Страница 8:** `iface ens3 inet dhcp`
- **Страница 8:** `auto ens4`
- **Страница 8:** `iface ens4 inet static`
- **Страница 8:** `address 172.16.1.1/28`
- **Страница 8:** `auto ens5`
- **Страница 8:** `iface ens5 inet static`
- **Страница 8:** `address 172.16.2.1/28`
- **Страница 11:** `root@isp:~# systemctl restart networking`
- **Страница 11:** `root@isp:~# ip -br a`
- **Страница 11:** `root@isp:~# systemctl restart NetworkManager`
- **Страница 11:** `root@hq-rtr:~# nano /etc/network/interfaces`
- **Страница 12:** `iface ens3 inet static`
- **Страница 12:** `address 172.16.1.2/28`
- **Страница 12:** `gateway 172.16.1.1`
- **Страница 12:** `address 192.168.100.1/27`
- **Страница 12:** `address 192.168.200.1/28`
- **Страница 12:** `auto ens6`
- **Страница 12:** `iface ens6 inet static`
- **Страница 12:** `address 192.168.99.1/29`
- **Страница 12:** `sysctl.conf H nftables.conf`
- **Страница 12:** `root@hq-rtr:~# systemctl restart networking`
- **Страница 12:** `root@hq-srv:~# nano /etc/network/interfaces`
- **Страница 15:** `root@br-rtr:~# systemctl restart networking`
- **Страница 15:** `root@br-fw:~# nano /etc/network/interfaces`
- **Страница 15:** `address 172.16.10.2/30`
- **Страница 15:** `gateway 172.16.10.1`
- **Страница 15:** `address 172.16.20.1/28`
- **Страница 15:** `sysctl.conf 1 nftables.conf`
- **Страница 17:** `rm -r /home/<uma nonb3oBatena>`
- **Страница 17:** `userdel <uma nonb3oBatena>`
- **Страница 17:** `root@hq-rtr:~# adduser net admin`
- **Страница 17:** `passwd: naponb ycnewHo o6HoBNéH`
- **Страница 17:** `root@br-rtr:~# adduser net admin`
- **Страница 17:** `passwd: maponb ycnewHo oOHoBNéH`
- **Страница 40:** `root@br-srv:~# mv /etc/samba/smb.conf /etc/samba/smb.conf.bak`
- **Страница 40:** `root@br-srv:~# systemctl stop smbd nmbd winbind`
- **Страница 40:** `root@br-srv:~# systemctl stop samba-ad-dc`
- **Страница 40:** `root@br-srv:~# samba-tool domain provision --use-rfc2307 --interactive`
- **Страница 40:** `Realm [AU-TEAM.IRPO]:`
- **Страница 40:** `Server Role (dc, member, standalone) [dc]:`
- **Страница 40:** `root@br-srv:~# samba-tool domain passwordsettings set --min-pwd-length=8`
- **Страница 42:** `root@hq-cli:~# apt install -y realmd sssd sssd-tools libnss-sss libpam-sss adcli`
- **Страница 53:** `root@hq-rtr:~# nano /etc/nftables.conf`
- **Страница 53:** `root@hq-rtr:~# systemctl restart nftables`
- **Страница 53:** `root@br-rtr:~# systemctl restart nftables`

## Примечание

Большая часть команд в исходном PDF вставлена как изображения. OCR распознаёт текст не идеально, а часть страниц не удалось распознать автоматически. Поэтому этот файл собирает найденные команды, но не гарантирует точную полноту всех команд со всех 83 страниц. Сверяйте с оригиналом, особенно конфигурации сети, NAT, SSH и правила доступа.
