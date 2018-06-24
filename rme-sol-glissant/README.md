# Système de sol glissant avec RME

Ce système permet de créer des puzzles où l'on glisse sur la glace, comme on en voit dans beaucoup de donjons en 2D.

![](https://i.imgur.com/46NKUOp.png)

Lorsque le joueur est sur la région 1 (sol glissant), le système regarde si la case devant est passable dans le tileset, puis si un évènement au même niveau que le joueur pourrait l'empêcher de passer. Si tout est bon, on fait un pas en avant. Ces vérifications évitent de bloquer le jeu en essayant de faire avancer le joueur dans un mur.

## Liens utiles

* [Obtenir RME (RPG Maker Extender)](https://wiki.rpgmakeralliance.com/scripts)
* [Essai gratuit de RPG Maker VX Ace](https://www.rpgmakerweb.com/download/free-trials/trial-rpg-maker-vx-ace)
