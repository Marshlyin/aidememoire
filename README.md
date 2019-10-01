# Aide Mémoire
Tout les trucs qu'il faut pas que j'oublie quand je code, les projets que j'ai commencé, et trucs en plus que j'aime avoir sur mon pc (Je réinstalle trop souvent mon OS pour pas le noter quelque part).   
*Pour être honnête je fais d'abord ca pour m'entrainer à écrire avec un [clavier](https://k2.keychron.com/  "j'ai jamais entendu un son si ASMR pour taper") en QWERTY international, mais c'est toujours utile.*


## Les must have sur mon PC  
### Les extensions gnomes (sur Ubuntu - 19.04)
- Dash to panel
- gTile
- OpenWeather
- User Themes
- Lock Keys (comme je n'ai pas d'indicateur sur mes claviers)


### GTK theme
Le theme que j'utilise actuellement est "Fantome", qui se dl via   
`git clone clone https://github.com/addy-dclxvi/gtk-theme-collections ~/.themes` (un ensemble de themes assez sympa)

### Écouter de la musique dans l'invite de commande
mps-youtube :  
- `sudo apt-get install python3-pip`  
- `sudo apt-get install virtualenv python3-virtualenv.`
- `sudo pip3 install mps-youtube`  
- `sudo pip3 install youtube-dl`  
- `sudo pip3 install youtube-dl --upgrade` (oui on est obligé de faire la mise a jour après le dl)  
- `sudo apt-get install mpv`
On peut lancer la commande avec ` mpsyt `, puis `set player mpv` pour mettre en place le lecteur.
On recherche avec /le nom de la super chanson que l'on veut écouter (genre /ttc girlfriend)

### Les Packets nécéssaires pour développer  
LAMP : 
- `sudo apt install apache2 php libapache2-mod-php mariadb-server php-mysql`
- `sudo apt install php-curl php-gd php-intl php-json php-mbstring php-xml php-zip`
- `sudo apt install phpmyadmin`  
et création d'un profil admin
- `sudo mysql`
- `GRANT ALL ON *.* TO 'marshlyin'@'localhost' IDENTIFIED BY 'le_bon_gros_mdp' WITH GRANT OPTION;   
FLUSH PRIVILEGES;  
QUIT;`


NODE :
- `wget -qO- https://deb.nodesource.com/setup_12.x | sudo -E bash -`
- `sudo apt install -y nodejs`


## Logiciels utilisés

- Editeur de code : [Visual Studio Code](https://code.visualstudio.com/)
- IDE : [PhpStorm](https://www.jetbrains.com/phpstorm/) (Php/SQL), [WebStorm](https://www.jetbrains.com/webstorm/) (JS), [Android Studio](https://developer.android.com/studio) (Android natif, Flutter)
- Organisation (Kanban, planning) : [Zenkit](https://static.zenkit.com/downloads/zenkit-linux.deb)
- Gestion associative : [Slack](https://slack.com/intl/fr-fr/downloads/linux)
- Versioning (graphique) : [GitKraken](https://www.gitkraken.com/download)

## Projets en cours

### Pictochat
Une reprise en NodeJS du fameux logiciel de chat de Nintendo sorti sur DS.
Travail collaboratif provenant d'un PoC entamé avec [Monowii](https://github.com/monowii) et actuellement repris pour améliorer l'interface (style rétro, date et heure en temps réel, changement de couleur du dessin...)

> Pour le lancer, `node server.js` et rdv @ localhost:8080  
> Require : websocket / express / mustache / sqlite3


### Mailing Reworked
Projet initialement entammé lors de mon stage chez [Effios](http://www.effios.fr/) en temps que développeur CRM [Dolibarr](https://www.dolibarr.org/). C'est une refonte de l'UX pour le module d'emailing du CRM : Moins d'étapes intermediaires, une visibilité des listes accrues, etc...   
Le développement pour le compte d'Effios a été repris par mon [successeur](https://github.com/lefrancp), le développement communautaire devrait être repris courant Septembre.
> Necessite Dolibarr, un ERP CRM Open Source

### Radioplayer
Un lecteur de webradio fait en une nuit à la place de travailler sur des projets vraiment importants. Très basique, en HTML/CSS et un peu de js, il est prévu d'être refait avec Vue.Js afin de découvrir ce framework. 





