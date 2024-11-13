Looter swiftUI:
Exercice 1 :
1, il manque l’instruction id : \.self qui sert à indiquer au code que toutes les occurrences de la liste sont uniques.

Exercice 2 : 
1, Ajout d'une fonction permettant l’ajout dynamique d’un item dans la variable loot et transformation de l'instruction List” en ForEach”. 
2, la transformation de l’instruction en “ForEach”, permet de faire une boucle qui est itérable et donc permet d’ajouter des “items” à l'intérieur de la variable.  Le fait de mettre le bouton à l’extérieur du ForEach, permet de rajouter juste l’itm sans rajouter la list

Exercice 3 : 
1, Non, le code ne fonctionne pas puisque la variable loot est imutable c’est à dire qu’on ne peut rien ajouter à l’intérieur.
3, Cela fonctionne, maintenant que nous avons placé le “@state” devant la déclaration de la variable “loot”. on peut expliquer que cela fonctionne car l’instruction “State” permet de transformer la variable “loot” imutable en mutable.

4. Ajout-item

Exercice 1:

