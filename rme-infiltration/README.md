# Système d'infiltration complet avec RME

Le système est commandé par un simple évènement en processus parallèle, qui gère les champs de vision et la détection. Grâce à RME, on reconnaît tous les évènements dont le nom est *Garde* et on les traite comme tels. Chaque garde possède une première page dans laquelle est définie son apparence et ses autres paramètres pendant la ronde, et une deuxième page pour ses paramètres après avoir détecté le joueur. Les gardes ne contiennent aucune programmation supplémentaire.

Pour qu'un garde repère le joueur, deux conditions : son champ de vision doit l'atteindre, et ils doivent avoir un couloir en commun.

![Exemple](https://i.imgur.com/8Y7uVbr.png)

Le garde et le joueur sont sur le même couloir, mais le joueur échappe au champ de vision.

![Exemple](https://i.imgur.com/ltJ8MYA.png)

Le joueur est dans le champ de vision du garde, mais ils n'ont aucun couloir en commun.

![Exemple](https://i.imgur.com/QdTZW40.png)

Le joueur se trouve sur trois couloirs, dont un en commun avec le garde. L'alerte est donnée !

Tutoriel complet : https://rpgmakeralliance.com/d/84
