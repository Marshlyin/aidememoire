# Aide Mémoire
Tout les trucs qu'il faut pas que j'oublie quand je code, les projets que j'ai commencé, et trucs en plus que j'aime avoir sur mon pc (Je réinstalle trop souvent mon OS pour pas le noter quelque part).   
*Pour être honnête je fais d'abord ca pour m'entrainer à écrire avec un [clavier](https://k2.keychron.com/  "j'ai jamais entendu un son si ASMR pour taper") en QWERTY international, mais c'est toujours utile.*


## Les must have sur mon PC  
### Les extensions gnomes (sur Pop!_OS - 19.04)
- Dash to panel
- gTile
- OpenWeather
- User Themes

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
On peut enfin lancer la commande avec ` mpsyt ` et on recherche avec /le nom de la super chanson que l'on veut écouter (genre /ttc girlfriend)

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

## Convention de nommage





