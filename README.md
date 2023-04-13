 

# Jeu du Morpion
Il s'agit d'une implémentation simple en ligne de commande du jeu classique du Morpion en Python. Le jeu permet à deux joueurs de s'affronter, avec le Joueur 1 utilisant "X" comme marqueur et le Joueur 2 utilisant "O". Le jeu vérifie les conditions de victoire et déclare un gagnant ou un match nul en conséquence.

## Comment Jouer? 

Exécutez le script Python pour démarrer le jeu.
Le plateau de jeu initial sera affiché, avec des espaces vides représentés par des espaces vides.
Le Joueur 1 commence en premier, suivi du Joueur 2.
Les joueurs jouent à tour de rôle en entrant les numéros de colonne et de ligne de la cellule où ils veulent placer leur marqueur.
Le plateau de jeu sera mis à jour et affiché après chaque coup.
Le jeu continue jusqu'à ce qu'un joueur gagne ou que le jeu se termine par un match nul.

## Fonctions
### afficher_grille(grille)
Cette fonction affiche le plateau de jeu actuel, montrant les positions des cellules et les marqueurs joués par les joueurs.

### tour(grille, joueur)
Cette fonction implémente le tour d'un joueur, en prenant en entrée les numéros de colonne et de ligne de la cellule où il veut placer son marqueur. Elle vérifie également si la cellule sélectionnée est déjà prise et demande une entrée valide.

### est_gagnant(grille)
Cette fonction vérifie si un joueur a gagné la partie en vérifiant les conditions de victoire sur le plateau de jeu.

### est_match_nul(grille)
Cette fonction vérifie si le plateau de jeu est complet et qu'aucun joueur n'a gagné, ce qui signifie que le match se termine par un match nul.
