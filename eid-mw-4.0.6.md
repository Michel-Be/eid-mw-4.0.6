eid-mw-4.0.6
============

Lecteur de carte d'identité électronique belge. Ce paquet est celui du "Middleware" qui est le logiciel nécessaire au fonctionnement de base.

Vous pouvez télécharger le paquet au format .pisi à cette adresse :

https://www.dropbox.com/s/pvwvmyafxrb9dlh/eid-mw-4.0.6-4.0.6-1-p01-x86_64.pisi?dl=0
ou ici : https://github.com/Michel-Be/eid-mw-4.0.6 ==> Téléchargez le paquet pisi

Pour Pisi Linux, après avoir installé ce paquet ajoutez via le terminal les paquets suivants :
sudo pisi it ccid
sudo pisi it pcsc-lite-openct

Redémarrez votre ordinateur et testez via votre navigateur en allant sur cette page : http://www.test.eid.belgium.be/

* N'oubliez pas d'installer et activer dans Firefox l'extension eID Belgique

**Le "Viewer" qui est optionnel et permet de visualiser les informations enregistrées sur le carte, le viewer sera ajouter dès qu'il sera créé.
