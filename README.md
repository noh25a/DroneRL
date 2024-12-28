# DroneRL
développement d'un drone capable de naviguer autonomement des waypoints.
L’objectif de ce projet est de développer un algorithme permettant à un drone de naviguer de manière autonome entre des points de passage prédéfinis (waypoints), tout en optimisant sa trajectoire pour éviter les obstacles et les collisions, en utilisant des outils d’apprentissage par renforcement. Ce modèle est ensuite comparé à une approche de contrôle manuel, où le drone est piloté à l’aide d’un clavier. Les drones s’entraînent dans un environnement simulé, collectant des ballons tout en minimisant les risques de crasher.

Etape 1:
On commence par l'approche Humain, où on va programmer un milieu qui simule la navigation d'un quadricoptère contrôler par les flèches du clavier, en se servant de Pygame pour la gestion des graphiques, événements et animation, ainsi de la bibliothèque math pour les calculs trigonométriques pour pouvoir bien sur simuler le comportement physique du drone, et aussi que la biblio random pour positionner aléatoirement les cibles.
