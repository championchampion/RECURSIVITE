# RECURSIVITE

cet exercice consiste à  vérifier si un mot donné est un palindrome.

pour le faire nous allons passer comme parametre à la fonction, un tableau de caractère contenant le mot à vérifier,
2 entiers i et n  pour permettre de parcourir le tableau  des 2 extremités vers le centre

avant de comparer les caractères 2 à 2 on vérifie d'abord la taille du tableau. si le tableau est vide ou contient un seul caractère alors 
on conclut que c'est un palindrome et on arrete

si le tableau contient au moins 2 caractères on parcour le tableau en commençant de chaque extremité et on compare les caratères 2 à 2

si pas d'égalité on arrête et on conclut que ce n'est pas un palindrome
sinon on teste le reste du mot en appelant la fonction elle même.
on passe en parametre le tableau de caractère et les indices des caratères incrementés
jusqu'a ce que le tableau soit entièrement parcouru soit i=n. 
Alors si l'égalité est confirmé jusqu'a cette étape on retourne vrai pour dire que le mot est un palindrome
