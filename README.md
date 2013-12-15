yana-windows
============

Interface vocal windows pour le serveur domotique Y.A.N.A

Pré-requis
============

- Raspberry PI
- Apache 2 ou Lighttpd
- PHP 5
- SQLite 3
- Installation de [Yana-server](https://github.com/ldleman/yana-server) sur votre rapsberry PI

Installation
============

- Téléchargez et décompressez l'archive de yana windows
- Sur votre pc windows,exécutez et installez ScanSoft Virginie_Dri40_16kHz.exe
- Lancez le programme "yana.exe", ne tenez pas compte des messages puis faites un clic droit sur l'îcone de yana situé dans la barre de tâche et cliquez sur 'Configuration'
- Configurez 'Adresse du serveur' avec l'adresse de votre yana-serveur suivis de "action.php", exemple :

Si l'adresse réseau de votre rapsberry pi est ```192.168.0.14```, l'adresse à entrer est : ```http://192.168.0.14/yana-server/action.php``` 

- Entrez également le 'token' de sécurité situé sur la page principale de votre yana-serveur (en haut à gauche)
