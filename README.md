# Algo-Pendu-TP

# Exercice : Jeu de Devine le Mot

## Contexte

Vous allez créer un petit jeu de devinette de mots. Dans ce jeu, l'utilisateur doit deviner un mot en proposant des lettres, un peu comme le jeu "Pendu". L'utilisateur a un nombre limité de tentatives pour deviner le mot. À chaque fois que l'utilisateur propose une lettre, le programme doit lui indiquer si cette lettre fait partie du mot ou non. Si la lettre fait partie du mot, le programme affiche les positions où cette lettre apparaît. L'utilisateur gagne s'il parvient à deviner toutes les lettres du mot avant d'épuiser ses tentatives.

## Consignes

1. Choisissez un mot (par exemple, "ordinateur") que l'utilisateur doit deviner.
2. Demandez à l'utilisateur combien de tentatives il souhaite avoir (ce nombre doit être positif).
3. Créez une chaîne vide ou une liste pour stocker les propositions de l'utilisateur (initialement remplie de tirets bas, car il n'a pas encore deviné de lettres).
4. Utilisez une boucle pour donner à l'utilisateur le nombre de tentatives qu'il a choisi.
5. À chaque itération, demandez à l'utilisateur de proposer une lettre.
6. Vérifiez si la lettre proposée fait partie du mot. Si c'est le cas, révélez la position de cette lettre dans le mot. Sinon, informez l'utilisateur que la lettre ne fait pas partie du mot.
7. Si l'utilisateur a deviné toutes les lettres avant d'épuiser ses tentatives, félicitez-le. Sinon, informez-le qu'il a perdu et révélez le mot.

## Points à Noter

- Utilisez des boucles pour gérer les tentatives de l'utilisateur.
- Utilisez également des boucles pour parcourir les lettres du mot et vérifier si la lettre proposée par l'utilisateur fait partie du mot.
- Soyez attentif à la gestion des entrées de l'utilisateur, et assurez-vous qu'il entre une seule lettre à la fois.
