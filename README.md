yana-windows
============

Interface vocal windows pour le serveur domotique Y.A.N.A

Pré-requis
============

- PC windows vista minimum (windows seven conseillé)
- Installation de [Yana-server](https://github.com/ldleman/yana-server) sur votre raspberry PI

Installation
============

- Téléchargez et décompressez l'archive de yana windows
- Sur votre pc windows,exécutez et installez ScanSoft Virginie_Dri40_16kHz.exe
- Lancez le programme "yana.exe", ne tenez pas compte des messages puis faites un clic droit sur l'îcone de yana situé dans la barre de tâche et cliquez sur 'Configuration'
- Configurez 'Adresse du serveur' avec l'adresse de votre yana-serveur suivis de "action.php", exemple :

Si l'adresse réseau de votre rapsberry pi est ```192.168.0.14```, l'adresse à entrer est : ```http://192.168.0.14/yana-server/action.php``` 

- Entrez également le 'token' de sécurité situé sur la page principale de votre yana-serveur (en haut à gauche)
- Cliquez sur enregistrer, le programme se relance et l'installation est terminée !! 

Utilisation est tests
============

- Sur yana-server vérifiez dans Configuration->Plugins que le plugin "Informations vocales" est bien activé, si ce n'est pas le cas, activez le et
relancer yana windows.
- Vérifiez lors du lancement de yana windows que seul les messages "Je peux maintenant parler :)" et "Je peux maintenant t'écouter... :)" apparaissent.
- Parlez au micro a voie clair et intelligible et lancez la commande "Yana, quelle heure est il ?"
- Si yana vous réponds, tout fonctionne, dans le cas contraire, vérifiez le contenu de l'historique (clic droit sur l'icone de yana en barre de notification) et envoyez le dans [la section issue](https://github.com/ldleman/yana-windows/issues)