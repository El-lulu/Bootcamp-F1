# Python 

### Exercice 1 :
Dans un premier temps on regarde si la chaine est vide ou si elle contient que des espaces pour cela on utilise un simple if qui verifie que l'entrée "texte" est ni égal à ""(donc vide) et en plus j'utilise la condition .strip qui permet de retirer tout les espaces. 

Pour convertir c'est simple on sait que le temps sera ecrit 1:33. Donc avant les : on aura les minutes qui faudra convertir en faisant *60 pour les avoir en seconde et tout ce que se trouve après il suffira de les additions au resultats de la premiere opération. Donc on utilse .split avec comme argument (":") et on recupere les donner avec un float comme indiquer sur l'enoncer 

Enfin pour renvoyer seulement les 3 premieres décimal on utilise round avec 3 comme argument. 

### Exercice 2 :
Dans un premier temps on creer une liste vide nommée resultats pour stocker chaque recupèré

la ligne :
    fichier = open(chemin, mode='r', encoding='utf-8')
Me permet d'ouvrir le fichier en mode de lecture grace au "mode='r'" ensuite on utilise DictReader pour transformer chaque ligne en dictionnaire.

Après j'utilise un boucle for pour récuperer la position au classement de chaque pilote. Et avec un simple if permet de verifier si il a abandonner et si il a pas abandoner alors on retourne la position du pilote

enfin on creer un dictionnaire avec toutes les donner et on retourne se dictionnaire

### Exercice 3 

1 On ouvre le fichier en mode 'w' pour pouvoir ecrire dedans    
2 Creation de l'objet csv.writer configurer avec le separateur ';'
3 pour ecrire l'entete on utilise .writerow
4 Pour finir avec une boucle for on verifie le temps et apres on extrait chaque avec pour les ecrires dans le csv

# JavaScript

### Exercice 1 

La fonction calcule le nombres de point en fonction de la position su pilote. Pour le faire on verfie déja si le joueurs fait partie du top 10 ensuite on utilise le BAREME il suffit juste de faire -1 a la position pour l'utiliser en tant qu'index pour le BAREM. Car on ne commence pas à 1 mais 
bien à 0 

### Exercice 2

On regroupe d'abord les résultats par pilote pour cumuler leurs points leurs victoires et leurs deuxiemes places. 

Ensuite on trie la liste comme ça : 

le nombre de points, le nombre de victoires en cas d'égalité, puis les 2ᵉ places, et enfin par ordre alphabétique si l'égalité persiste

### Exercice 1 
1 on creer une copie de la liste pour ne pas la modifier grace au .slice()
2 je trie par ordre les resultats grace au .sort 

### Exercice 2
La fonction permet d'afficher un tableau sur la page web Elle prend une liste et grace a cette liste elle affiches autaumatiquement un tableau.

### Exercice 3
Je cible un élément du tableau HTML par son ID puis je recupere toute les lignes grace à 'tr' 
Apres on parcours toute les lignes grace a foreach et si il font partie des trois prmeiere alors on lui attribut la classe CSS "podium"
