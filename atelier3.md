
**Bonjour à tous !**

L'objectif de ces deux jours est d'arriver à construire des objets que l'on pourra manipuler en VR comme des jouets d'enfant.

La première journée sera consacrée à la création des objets, puis la seconde à la mise en commun des productions de la classe 
pour que chacun ait une scène unique, représentant une scène de guerre.

Voici les objets à construire la première journée :

- Une catapulte (une machine qui lance quelque chose), 
- un projectile (lancé par la catapulte), 
- une plateforme avec des roues pour poser la catapulte
- Un morceau de mur à dupliquer, prêt à se briser

Pour chaque objet, respecter les règles suivantes :
- Conception :
	- Tout tient dans un objet "conteneur" avec le scale à 1, la position et la rotation à zéro
	- La hiérarchie des objets est organisée en sous-groupe de conteneurs
	- Les objets sont nommés, pas de noms par défaut ("mur", "sol", "cube", "sphere")
	- Les objets similaires sont regroupés dans des conteneurs
	- Les dépendances du prefabs sont dans un même dossier (material, mesh, texture ...)
	- Le package contient ce dossier
 - Un fichier txt qui décrit l'objet
 - Un ou plusieurs materials
 - Un prefab prêt à être utilisé

La matinée de la seconde journée, il faudra construire une scène avec un terrain, poser dessus les objets de la journée d'avant, et essayer de faire un train constitué des remorques avec dessus les catapultes.

Barème :

- Catapulte sur 10 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 points
  - Un animator capable avec des triggers de :
    - Lancer un tir - 2 points
    - Revenir à la position de départ pour être prêt à retirer - 2 points
    - Ajuster la direction du tir sur la hauteur et la direction 1 point chacun
  - La Catapulte peut être brisée et ne plus marcher : 1 point
    
    
- Projectile sur 4 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 point
  - Une physique propre avec un "physic material" : 1 point
  
- Plateforme avec des roues sur 5 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 points
  - Gestion des wheel colliders : 2 points

- Un morceau de muraille 4 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 points
  - Placement des fixed joints pour l'effondrement : 1 point
  
- Terrain sur 6 points :
  - Concept du terrain : 1 point
  - Règles de conception validées : 1 point
  - Textures adaptées au relief : 2 points
  - Herbes et arbres : 2 points
  
  Finalement 3 points : 
  - Une scène jouable avec des éléments de tout le monde : 2 points
  - En VR : 1 point
