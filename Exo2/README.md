# Exercice débutant 2 :

- sudo find /etc -type f > log.txt<br>
Cette commande permet de lister tous les fichiers du répertoire /etc puis enregistre cette liste dans le fichier log.txt.<br>

- ls -l log.txt<br>
Cette commande permet de vérifier que le dosser à bien été crée.<br> 

- cat log.txt<br>
Cette commande permet de lire le contenu du fichier log.txt.<br>  

![Photo 1](../Img/1.png)

- tail -n 10 /var/log/syslog<br>
Cette commande permet d'afficher les 10 dernières lignes du fichier syslog.<br>

- tail -n 10 /var/log/syslog >> log.txt<br>
Cette commmande permet de déplacer les 10 dernières lignes du fichier syslog vers le fichier log.txt.<br>

- cat log.txt<br>
Cette commande permet d'afficher le contenu du fichier log.txt. Cela me permet de vérifier que ma dernière commande à bien été effectuée.<br>

![Photo 2](../Img/2.png)

- grep -i "error" log.txt<br>
Cette commande permet de chercher le mot "error" dans le fichier log.txt. Le "-i" permet de ne pas faire de distinction entre majuscules et minuscules.<br>

![Photo 3](../Img/3.png)