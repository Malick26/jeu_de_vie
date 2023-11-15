
# Jeu de la Vie - TL221 - FOO BIRR ADOUNA

Bienvenue dans le Jeu de la Vie TL221 - FOO BIRR ADOUNA ! Ce jeu est une implémentation du célèbre automate cellulaire "Jeu de la Vie" de John Conway.

## Comment jouer

1. **Tamabli/SIRPLACE :** Cliquez sur le bouton avec le symbole de lecture (`▶`) pour commencer ou arrêter le jeu.

2. **DEFATT :** Cliquez sur le bouton  DEFATT (`↺`) pour recommencer le jeu.

3. **Activer/Désactiver le son :** Cliquez sur l'icône du haut-parleur (`🔊`/`🔇`) pour activer ou désactiver le son.

## Timer

Le jeu comporte également un minuteur qui enregistre le temps écoulé depuis le début du jeu.

## Fonctions

### `toggleCell(row, col)`

Cette fonction permet de basculer l'état d'une cellule à la position spécifiée dans la grille. Utilisez-la en cliquant sur une cellule lorsque le jeu est arrêté.

### `startStopGame()`

Cette fonction démarre ou arrête le jeu en alternant entre les états de jeu et d'arrêt.

### `playGame()`

Cette fonction est appelée de manière répétée pour faire évoluer le jeu. Elle met à jour la grille et l'interface utilisateur à chaque itération.

### `updateGrid()`

Mettez à jour la grille en fonction des règles du Jeu de la Vie.

### `countNeighbors(row, col)`

Cette fonction compte le nombre de voisins vivants autour d'une cellule à la position spécifiée.

### `resetGame()`

Réinitialise le jeu en remettant le compteur de génération à zéro, en arrêtant le jeu et en régénérant une nouvelle grille aléatoire.

### `startTimer()`, `stopTimer()`, `updateTimer()`

Ces fonctions gèrent le minuteur du jeu.

### `toggleSound()`

Active ou désactive le son du jeu.

### `updateSoundIcon()`

Met à jour l'icône du haut-parleur en fonction de l'état du son.

## Icones

- L'icône Twitter a été téléchargée depuis [FreeLogoPNG](https://freelogopng.com/dounload.php?id=1171&search=Twitter-logo).

## Audio

La musique de fond du jeu a été téléchargée depuis [Pixabay](https://pixabay.com/fr/music/search/genre/jeux%20vid%C3%A9o/).


