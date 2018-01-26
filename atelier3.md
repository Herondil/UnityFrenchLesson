
**Bonjour à tous !**

L'objectif de ce TP en deux séances de 3h est d'arriver à concevoir un jeu à pince géant en VR.

Le cours consistera en la fabrication des gameobjects requis, et à la fin du second second au test du passage en VR avec le HTC Vive sur une scène utilisant tous les objets fabriqué.

Voici les objets à construire :

- Un objet à ramasser par la pince, 
- Une pince animée qui va servir à ramasser l'objet (avec des rails), 
- Un panneau de contrôle avec des touches, 4 pour les directions et 1 pour faire descendre la pince

Pour chaque objet, respecter les règles suivantes :
- Conception :
	- Tout tient dans un objet "conteneur" avec le scale à 1, la position et la rotation à zéro
	- La hiérarchie des objets est organisée en sous-groupe de conteneurs
	- Les objets sont nommés, pas de noms par défaut ("cube", "sphere","GameObject")
	- Les objets similaires sont regroupés dans des conteneurs
	- Les dépendances du prefabs sont dans un même dossier (material, mesh, texture ...)
	- Le package contient ce dossier
 - Un fichier txt qui décrit l'objet
 - Les éventuels materials
 - Un prefab prêt à être utilisé

L'objectif est de pouvoir s'amuser à combiner les 3 objets de tout le monde dans une nouvelle scène, mixer un panneau de commande, une pince, et autant d'objet à ramasser qu'on le souhaite.

Idéalement, après être tombée la pince ramène l'objet qu'elle a ramassé vers le joueur, pour qu'il puisse le récupérer via une trappe avec des portes battantes.

Barème :

- Pince sur 8 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 points
  - Un animator capable avec des triggers de :
    - Déplacement dans les 4 directions - 2 points
    - Descendre et pincer - 2 points
    - Revenir à une position initiale et lacher l'objet - 1 point
    
- Objet à ramasser sur 4 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 point
  - Une physique propre avec un "physic material" : 1 point

- Pannneau de commande 5 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 points
  - Utilisation du script pour activer les trigger de la pince - 1 point
  - Il y a un effet de particules quand on touche un bouton - 1 point
  
  
  Finalement 3 points : 
  - Une scène jouable avec des éléments de tout le monde : 2 points
  - En VR : 1 point
