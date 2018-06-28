Apprendre la programmation avec des exercices simples
==========

## 1. Introduction
Bienvenue dans cette page d'introduction au code. Elle sera remplie d'exercices très simples pour apprendre gentiment la programmation. Nous avons sélectionné ces exercices car c'est pile poile ce qu'il faut pour démarrer avec les concepts simples en informatique. Nous nous sommes inspirés de [ce site](https://adriann.github.io/programming_problems.html) pour les exercices.

## 2. Comment ça marche ?
Nous allons donner une liste d'exercices. Nous conseillons de faire les exercices à la suite, un par un. Si jamais tu galères sur l'un des exercices, essaie de faire le suivant. Si tu arrives à faire le suivant, passe à la suite. Si tu n'arrives pas à faire le suivant, pose-toi et réfléchis pour réussir le problème.


Pour chaque exercice, tu devras créer un programme Ruby, et l'exécuter pour le faire marcher. Le programme devra faire ce qui est indiqué.


## 3. Les exercices

1 . Crée une fonction qui prend un integer comme argument et qui renvoie "pair" pour les nombres pairs et "impairs" pour les nombres impairs.

2 . Crée un array, et renvoie la somme de tous les nombres positifs.
*Par exemple :  `[1,-4,7,12]` => `1 + 7 + 12 = 20`*
Si il n'y a rien à additionner, la somme est 0 ;)

3 . On te donne un nombre, trouve l'opposé. Facile, non ? Essaye de le faire en 1 ligne et sans conditions ;)
**Par exemple  :* `1 => -1` `-34 => 34`**
     
4 . Écris une fonction `reapeatStr` qui répète la chaine de caractères en argument exactement `n`fois.
*Par exemple :  `repeatStr(5,"thp") ==> "thpthpthpthpthp"`*

5 . Crée une fonction qui enlève la première et dernière lettre d'une chaîne de caractères. Un seul paramètre, la CDC originale.

6 . Crée une fonction qui retourne le plus petit integer d'un array. 
*Par exemple :* 
-  *Avec  `[34, 15, 88, 2]`  ta fonction renvoie  `2`*
-  *Avec  `[34, -345, -1, 100]`  ta fonction renvoie  `-345`*

7 . Imagine que tu as une array de mouton. Certains de ces moutons manquent. Créer une fonction qui compte le nombre de moutons présent dans l'array (true = présent).

*Par exemple : 
[true, true, true, false, true, true, true, true , true, false, true, false, true, false, false, true , true, true, true, true , false, false, true, true] renvoie 17.*

8 . Additionne tous les nombres d'une array... Sauf le plus petit et le plus gros nombre.

*Par exemple : `{ 6, 2, 1, 8, 10 } => 16`  & `{ 1, 1, 11, 2, 3 } => 6`*

9 . Facile. Enlève les espace d'une chaîne de caractères, et renvoie le résultat.

10 . Yes, t'es au dixième exo ! Voici un truc un peu plus challengeant : 
Renvoie un array, dans lequel le premier élément est la somme des nombres positifs, et le deuxième la somme des nombres négatifs.
Par exemple : 
*Cet array :  [1, 2, 3, 4, 5, 6, 7, 8, 9, 10, -11, -12, -13, -14, -15] 
Renvoie :  [10, -65]*

11 . Écris une fonction `summation` qui renvoie l'addition de chaque nombre entre 1 et le nombre rentré en paramètre. Le nombre donné sera toujours positif et supérieur à 0.
*Par exemple :* 
`summation(2) -> 3` 
*renvoie* `1 + 2`
 `summation(8) -> 36`
*renvoie*  ` 1 + 2 + 3 + 4 + 5 + 6 + 7 + 8`

12 . Inverse chaque nombre de l'array en paramètre d'une fonction `inverse`. Chaque positif deviens négatif, et inversement 
*Par exemple : `invert([1,-2,3,-4,5]) == [-1,2,-3,4,-5]`*

13 . Crée une fonction `rps`. Les règles sont les suivantes : `Scissors` bat `Paper`, `Paper` bat `Rock`, et `Rock` bat `Scissors`

*Par exemple : 
rps('scissors','paper') // Joueur 1 gagne ! rps('scissors','rock') // Joueur 2 gagne ! rps('paper','paper') // Egalité !*

14 . Crée une fonction qui transforme un nombre en chaîne de caractères.
*Par exemple : `number-to-string 123 ;; renvoie '123'`*


15 . Créé une fonction qui répète chaque lettre de la chaîne de caractère en argument.
*Par exemple : `double_char("String") ==> "SSttrriinngg" `*