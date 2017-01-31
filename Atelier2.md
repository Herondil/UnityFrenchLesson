
**Bonjour à tous !**

L'objectif de ces deux jours est d'arriver à construire des objets que l'on pourra manipuler en VR comme des jouets d'enfant.

La première journée sera consacrée à la création des objets, puis la seconde à la mise en commun des productions de la classe 
pour que chacun ait une scène unique, représentant l'assaut d'un chateau fort.

Voici les objets à construire la première journée :

- Une catapulte (une machine qui lance quelque chose), 
- un projectile (lancé par la catapulte), 
- une plateforme avec des roues pour poser la catapulte

- Un morceau de murailles
- Un donjon
- Une porte façon pont levis, avec des chaines

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

La matinée de la seconde journée, il faudra construire une scène avec un chateau construit grâce aux objets de la journée d'avant sur un terrain, et essayer de faire un rail pour un train constitué des remorques avec dessus les catapultes.

Barème :

- Catapulte sur 10 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 3 points
  - Un animator capable avec des triggers de :
    - Lancer un tir - 2 points
    - Revenir à la position de départ pour être prêt à retirer - 2 points
    - Ajuster la direction du tir sur la hauteur et la direction 1 point chacun
    
    
- Projectile sur 4 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 point
  - Une physique propre avec un "physic material" : 1 point
  
 - Plateforme avec des roues sur 5 points :
  - Concept unique à la classe : 1 point
  - Règles de conception validées : 2 point
  - Gestion des wheel colliders : 2 points
