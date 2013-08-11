My-piratebox
============

Screenshots
===========

Homepage
--------

![ScreenShot](https://raw.github.com/tontonDuPirox/my-piratebox/master/screens/screen-home.png)

Fichiers
--------

![ScreenShot](https://raw.github.com/tontonDuPirox/my-piratebox/master/screens/screen-shared.png)

Forum
-----

![ScreenShot](https://raw.github.com/tontonDuPirox/my-piratebox/master/screens/screen-forum.png)

Chat
----

![ScreenShot](https://raw.github.com/tontonDuPirox/my-piratebox/master/screens/screen-chat.png)

A propos
--------

![ScreenShot](https://raw.github.com/tontonDuPirox/my-piratebox/master/screens/screen-about.png)

Installation
============

On suppose ici que la piratebox est installée, et qu'elle fonctionne parfaitement. Pour en savoir plus, suivre le tutoriel de David Darts :
http://daviddarts.com/piratebox-diy-openwrt/?title=PirateBox_DIY_OpenWrt

1) Télécharger l'archive et la décompresser

    wget https://github.com/Corent1/my-piratebox/archive/master.zip && unzip master.zip

2) Se connecter au réseau wifi de la piratebox

3) Copier les fichiers vers la piratebox

    scp -r ./my-piratebox-master/opt/piratebox/* root@192.168.1.1:/opt/piratebox/

4) Se connecter en ssh à la piratebox

    ssh root@192.168.1.1

5) Redémarrer le service piratebox

    /etc/init.d/piratebox stop
    /etc/init.d/piratebox start
