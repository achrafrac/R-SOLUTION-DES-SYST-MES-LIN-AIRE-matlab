 #                        Interface graphique Matlab
 ##                *RÉSOLUTION DES SYSTÈMES LINÉAIRES AX=B*
   
![image](https://user-images.githubusercontent.com/85987778/155781151-e1012b20-4348-47f1-b9d3-daaa36621bde.png)

### Introduction
Les systèmes linéaires forment la base calculatoire de l'algèbre linéaire. Ils interviennent à travers leurs applications dans plusieurs domaines; La physique et la mécanique, la chimie, science de l'ingénieur etc.                                                         
Le but de notre projet est de réaliser une application, en utilisant le language Matlab, capable de résoudre les systèmes linéaires Ax = b.
  
  ### Description du projet
  
  Matlab GUI (Graphical User Interface) est un outil dédié à la création des interfaces graphiques qui permet au programmeur de créer des interfaces GUI pour mettre à profit les performances du langage Matlab aux utilisateurs qui ne sont pas familiarisés avec ce langage.
•	Les objectifs de ce projet sont : 
−	La résolution numérique de Ax = b avec différentes méthodes ; directes et  itératives.
−	La résolution graphiques de Ax = b
•	Les limites de ce projet :
−	On se limite dans ce projet à la résolution graphiques de Ax =b en 2D .

Présentant tout d'abord l'interface de l'application.
Il est constitué de deux champs, le premier pour l'insertion de la matrice A et le deuxième pour le vecteur b. 
Après, l'utilisateur va choisir l'une de ces méthodes. soit directe ou itérative. D'ailleurs il ne peut pas choisir plus qu'une méthode.

Ensuite, on a trois boutton :
Resolve : Récupère la matrice A et le vecteur b, et fournit la solution numérique, et dans le cas des méthodes itératives
il nous affiche le nombre d'itérations faites jusqu'on arrive à la solution.

Draw : il est utiliser dans le cas où la matrice A est une matrice 2*2. Il nous fournit la solution graphique du système linéaire.Dans le cas échéant, il nous affiche un
message indiquant que la solution graphique n'est pas disponible.

Et enfin le boutton Clear qui efface tout le texte de l'interface, résultant en un écran clair, puis il supprime toutes les variables
de l'espace de travail actuel et les libérant de la mémoire système.

   


