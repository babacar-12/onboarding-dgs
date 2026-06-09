Mes observations sur l'installation de docker : J'ai téléchargé docker depuis le site officiel et suivi les étapes. Après execution de la commande "docker version", elle a retourné les informations sur le client et le serveur.

TP1 : Après execution de "docker run hello-world", docker a cherché l'image hello-world sur la machine et ne l'a pas trouvée. Il l'a téléchargée depuis Docker Hub, il a créé un conteneur à partir de cette image et le conteneur a affiché son message puis s'est arrêté. J'ai tapé aussi la commande "docker ps -a" qui a listé les conteneurs.

TP2 : j'ai lancé le serveur Nginx et je suis allé sur le navigateur pour taper "http://localhost:8000". La page affiche Welcome to nginx. Et aussi j'ai vérifié les logs, arrêté et supprimé le conteneur

TP3 : Je suis entré dans le conteneur puis dans /usr/share/nginx/html et listé les fichiers présents dans ce répertoire. Puis je suis sorti et j'ai supprimé le conteneur

TP4 : j'ai créé ma propre image docker. D'abord j'ai créé un dossier montp contenant un fichier index.html et un autre Dockerfile. Ensuite, j'ai construit l'image, lancé le conteneur et verifié mon navigateur. Enfin j'ai eu sur la page : Ma premiere image docker

TP5 : j'ai créé un nouveau dossier contenant un fichier docker-compose.yml avec le mapping 8080:80. Puis j'ai lancé l'environnement et verifié l'affichage. Je vois welcome to nginx et enfin j'ai tout arrêté et supprimé

Installation de git : j'ai téléchargé git depuis le site officiel. La verfication a retourné le numero de version installé. J'ai configuré mon identité

TP Git GitHub : j'ai créé un compte sur github.com. J'ai créé un dépot public nommé onboarding-dgs, j'ai cloné le dépot sur ma machine  et créé le fichier notes.md
