# tp3
Normalement, dans le développement réel d'une application, des conflits se produiront spontanément. Cependant, pour notre formation, nous allons intentionnellement forcer un conflit dans git.

Dans la plupart des cas, git est capable de mélanger les modifications que différents utilisateurs apportent à différents fichiers, mais si deux utilisateurs apportent des modifications au même fichier localement (surtout si la modification se trouve sur la même ligne), git ne pourra pas savoir quelle modification est la bonne. Produisons un tel conflit :

<<<<<<< HEAD
- Voici une ligne du README.md avec dex (deux) fautes de frape (fautes de frappe) à corriger
=======
- Voici une ligne du README.md avec deux (deux) fotes de frape (fautes de frappe) à corriger
>>>>>>> e3f0d677f6a72db269f8e86e615a6a857a4a83ed

- **Athos** corrigera la première faute de frappe (deux) et **Porthos** la seconde (fautes de frappe) 

- Chacun va faire un clone du repositoire et corriger sa faute de frappe localement, puis essayer de faire un `push` du changement.


![alt text](https://abderzah.github.io/Introduction-GIT/tp5/images/linus.jpeg)
