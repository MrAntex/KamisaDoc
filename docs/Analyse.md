#
Analyse


**Classes utilisées:**


* Pièce
* Board
* Fenetre
* Game

**Relations entre les classes:**
Aucune

**Fonctionnement global:**

Le programme utilise 2 tableaux de pièces, qui corespondent aux pièce de chaque joueur. Ces pièces possèdent une donnée x et une y pour leur localisation sur le plateau, un numéro pour identifier leur couleur et un statut pour déterminer si elles sont sumo1, sumo2 ou simple pièce. A chaque tour le déplacement est vérifié dans les fonction membbre de Piece, puis les collisions sont vérifiées en parcourant les position des differents pions grace auxtableaux. La position est ensuite validée, ou non, et le pion se déplacera, ou la case deviendra rouge.
