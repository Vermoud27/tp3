# tp3
Groupe IUTC-727

RAVENEL Martin
MAROUARD Louis
COCAGNE Oscar
LELIEVRE David










Compte-rendu SAE 2.03 :

Installation de services réseaux
















2023                                                                                                                     IUT Le Havre

TP1 : Travailler sur un répertoire local

1) La commande git config list après les configurations demandées nous donne ceci : 

![alt text](/images/1.png)


2) Le dépôt git à bien été créé, et la commande git status nous donne bien ce résultat :

![alt text](/images/2.png) 

Il indique qu’aucun fichier n’est présent dans ce dépôt


3) Le fichier README.mdi  à été créé avec ce contenu : 

![alt text](/images/3.png) 


Lors de la création ou modification d’un fichier sur le répertoire local, la commande git status affichera ceci : 

![alt text](/images/4.png) 

 Pour effectuer le dépôt, il nous faut utiliser la commande git add nom_du_fichier  comme ceci : 
 
 ![alt text](/images/5.png) 
 
 Puis, valider le dépôt avec  git commit -m “Action réalisée”  ainsi :
 
![alt text](/images/6.png) 

Après la validation du dépôt, la commande git status nous confirme l’action en renvoyant ceci : 

![alt text](/images/7.png)

4) Le fichier Cryptomonnaie.java a bien été créé et compilé içi : 

![alt text](/images/8.png)

Cependant, grâce au fichier .gitignore , le fichier .class n'apparaît pas dans les dans les fichiers en attente de dépôt : 

![alt text](/images/11.png)

De ce fait, le dépot n’est effectué que sur le fichier .java : 

![alt text](/images/9.png)

Le fichier .gitignore permet au répertoire d’ignorer certains types de fichiers

![alt text](/images/10.png)




TP2 : Travailler en autonomie sur un dépôt GitHub distant

1) Créer un compte sur github

La création du compte GitHub est assez explicite. Il nécessite un email, un mot de passe et un nom d’utilisateur à retenir pour la suite.

2)Ajouter une nouvelle clé SSH à votre compte GitHub

GitHub a besoin d’une clé privée pour poursuivre sa création.
Pour cela nous avons dû créer notre propre clé et copier toute sa référence:

![alt text](/images/sae2.03(1).png)

![alt text](/images/sae2.03(2).png)

3) Pousser un dépôt existant depuis la ligne de commande
Nous pouvons regarder si le GitHub a bien été créé avec la commande git remote.
Une fois la création de github terminé, il faut contrôler les branches

![alt text](/images/sae2.03(3).png)

Puis certaine commande vont permettre de mettre à jour le Git

![alt text](/images/sae2.03(4).png)

Une fois cette étape terminée nous pouvons consulter à tout moment notre page web

4)Séquence de travail avec un dépôt distant

Pour transvaser entre GitHub et notre terminal il faut plusieur commande:

-En premier git status, pas obligatoire, mais il nous montre ce qui est à jour 

![alt text](/images/sae2.03(5).png)

-En second git add . (ou) -A (ou) "Nom du fichier", qui permet d’ajouter dans le Git soit tous les fichier, soit un en particulier.

-Puis git commit -m”Info de l’action” qui permet de décrire l'intérêt de l’action:

![alt text](/images/sae2.03(6).png)

-Et enfin git push qui permet de mettre à jour toute les actions qui ont était fait

![alt text](/images/sae2.03(7).png)

5) Cloner un dépôt distant sur notre machine locale

Cloner des fichiers GitHub va permettre un gain de temps, par exemple copier coller tout les fichiers d’un Git à un autre on peut:

![alt text](/images/sae2.03(8).png)




TP 3 : Travailler en équipe sur un dépôt GitHub distant


1) Inviter des collaborateurs dans un dépôt personnel

Sur GitHub on peut ajouter des collaborateurs pour travailler à plusieurs sur un projet

Une fois un collaborateur ajouter, ce dernier peut entrez une commande qui lui permet de récupérer tous les fichiers:

![alt text](/images/sae2.03(12).png)

Une fois que tout les collaborateur ont tous les fichiers, ils peuvent enregistrer leur travaux avec la commande vu juste avant :  git push

Les autre collaborateurs peuvent mettre à jour les travaux d’autrui avec la commande:
git pull



2) Développement d’un projet java en équipe

En collaboration on peut mener un projet sur java simultanément sur le fichier qu’on veut sans oublier de mettre à jour pour ne pas avoir de conflit 


3) Gérer des nouvelles fonctionnalités à l’aide des branches

La fonctionnalités des branches est très importantes , il faut donc toujours savoir dans quel branche on travail et bien les répartir avec les commandes
	-git branch
	
![alt text](/images/sae2.03(9).png)

	-tree

![alt text](/images/sae2.03(10).png)


On peut peut donc créer de nouvelle branche:

![alt text](/images/sae2.03(11).png)


Les fichiers qui seront créés dans cette branche ne seront que dans cette branche.

On peut fusionner les branches à tout moment pour que les branches est accès au fichiers des autres branches avec la commande git merge "Nom fichier"


