Contact 	: Maxens Dubois

mail       	: maxens.dubois@gmail.com

réseau		: Maxens Dubois sur Facebook, LinkedIn, Viadéo

Projet :
	- Une expérience interactive par personne :
		-> Une phrase générale de concept (aucune limitation !)
		-> Entre 2 et 4 fonctionnalités (niveau visuel, sonore, ou jeu)

		
Exercice 1 :

	- Construire une pyramide de cubes (ou d'un autre objets de base)
		-> Visible quand on lance le jeu
		-> Ajouter de la couleur ou une texture
		-> Avoir des objets vides comme conteneur
		-> Exporter le Prefab de la pyramide
	
	- Construire un "village de pyramides", avec :
		-> Des clones de la pyramide
		-> Un clone avec un étage en plus
		-> Un terrain
		-> Ajouter un controler et se promener dans le village

	->> Exporter un Prefab de bâtiment, mettre dans le même dossier tous les éléments requis par le prefab		
		
Exercice 2 :

	- Dans la scène de l'exercice 1 ou dans une nouvelle scène , on veut créer un parcours avec une arrivée :
		-> Construire un parcours avec un point d'arrivé et un point de départ
		-> Ajouter un ThirdPersonControler (ou un first) pour jouer le parcours
		-> Placer des GameObjects vides avec des components de collision en Trigger sur ces deux zones
		-> Détecter l'entrée du joueur dans un de ces triggers
		-> A l'entrée d'une de ces zones, afficher un message dans la console
		-> Construire un trou avec un autre trigger, détecter l'entrée dedans et afficher un message de gameover

	->> Exporter un Prefab contenant une ligne d'arrivée, ou un piège
		
		
Exercice 3 :

	- Construire un canon !
		-> Construire une dale colorée légèrement surélevée
		-> Poser un Trigger dessus qui s'enclenche quand on le touche
		-> Le trigger donne une force à un objet qui le fait décoller, par exemple une sphère
	
	->> Exporter un Prefab contenant le canon


Exercice 4 :
		
	- Construire un mur à détruire par le canon :
		-> Pour détruire ce mur, il va falloir  activer le canon qui va tirer une balle sur le mur et le faire tomber
		-> Faire un mur en assemblant des formes simples (cubes, sphère, cylindres, ...)
		-> Faire une fenêtre dans le mur, empêcher les blocs du dessus de tomber grâce des "Joints"

	->> Exporter un Prefab contenant le mur
		

Exercice 5 :

	- Constuire un moulin :
		- Contruire 4 piliers au sol
		- Poser dessus une croix, construite en assemblant deux cubes
		- Poser sur la croix un cylindre, joints à la croix
		- Sur ce cylindre, poser un autre cylindre sur lequel sonts joints des pales
		- Configurer un joint pour que le second cylindre tourne en étant collé au premier
	
	->> Exporter un Prefab contenant le moulin

Exercice 6 :

	- Constuire une catapulte à roulette :
		- Le chassis en forme de H
		- 4 roues en forme de boule (avec un sphere collider) avec les bons joints
		- Une cuillère avec de quoi poser une boule
		- Lancer un projectile, avec AddForce ou AddTorque
		
	->> Exporter le prefab contenant la catapulte

	
Exercice 7 :
	
	- Contruire une maison :
		- Au niveau du sol, sur un terrain
		- Ajouter une porte
		- Enlever la lumière par défaut et ajouter de l'éclairage à l'intérieur
		- Utiliser Animator pour créer et lancer une Animation d'ouverture de porte
		- Ajouter un FPS controler
		
	->> Exporter la porte et son animation


Exercice 7 bis :

	- Continuer à travailler sur cette maison :
		 - Ajouter un Trigger qui déclenche l'ouverture de la porte quand on rentre dedans
		 - Ajouter un étage, plusieurs pièces à explorer
		 - Animer quelques objets dans la maison :
		 	- Des poissons dans un aquarium
		 	- Une souris qui court par terre
		 	- Des lumières qui scintillent
		 	- Le balancier d'une pendule
