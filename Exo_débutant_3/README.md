 # Exercice débutant 3 :

 - touch .secret.txt<br>
 Cette commande permet de créer un fichier .txt secret. C'est à dire invisible pour la commande ls.<br>

- ls ET ls -a<br>
ls affiche une liste des noms de tous les fichiers du répertoire, ls -a tous les fichiers + les fichiers cachés.<br>

 - chmod 600 .secret.txt<br>
 Cette commande permet de changer les permissions du fichier .secret.txt. 6 indique que le propriétaire peux lire et modifier le fichier, 00 que le groupe et les autres ne peuvent ni le lire ni le modifier.<br>

 - ls -l .secret.txt<br>
Cette commande permet de vérifier que les permissions ont bien été modifié.<br>

![Photo 4](../Img/4.png)

# Pour aller plus loin

On crée un nouvel utilisateur pour vérifier qu'il ne peux pas lire ni modifier le fichier.
