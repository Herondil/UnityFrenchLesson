Bonjour !

Voici un sujet à réaliser pour valider la note du premier semestre d'Unity.

Il consiste en la réalisation d'un train, à l'intérieur duquel on peut se déplacer avec le FPS controler.

L'idée du jeu est de passer du wagon à la locomotive, dans laquelle nous allons pouvoir guider le train.

Il faut réaliser les GameObjects suivants et les exporter sur le dossier Drive en suivant la méthode expliquée ici :

Chaque objet doit valider les points suivants :
- Concept unique : 1 pt
- Règles de conception : 2 pts

Le train avance tout seul grâce au compononent "Constant force" et à une animation.

- Wagon :
  - Utilisation des wheel collider
  - Création d'une porte fermée utilisant au moin un Hinge joint
  - Le wagon possède un aniamtor avec un trigger capable de débloquer les portes avant et arrière

- Locomotive :
  - Comme le wagon, sauf que la porte est déjà ouverte
  - Animator capable avec des triggers d'accélerer ou de freiner  

- Rail allant tout droit

- Virage vers gauche et droite

- Un aiguillage avec un animator pour mettre le rail en position A ou B

Au final, il doit être possible de créer un terrain, de poser les rails, une locomotive avec quelques wagons, et recréer ainsi le jeu.

Les packages doivent être remis dans le dirve au plus tard le 30 novembre à 19h.

N'hésitez pas en cas de questions !