# tp3
Groupe IUTC-727
RAVENEL Martin
MAROUARD Louis
COCAGNE Oscar
LELIEVRE David










Compte-rendu SAE 2.03 :

Installation de services réseaux
















2023                                                                                                                     IUT Le Havre

Sommaire : 











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
