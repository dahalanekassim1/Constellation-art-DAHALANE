CONSTELLATION 

Un projet codé en python

je cherche a créer un constellation 
ceci est un projet que j'ai fait

Ceci est un capture qui montre la fin du projet
<img width="912" height="737" alt="image" src="https://github.com/user-attachments/assets/33e8437e-2ecb-4841-ab0f-24c3f037b724" />

Ce projet a été développé de manière itérative en traduisant une structure de constellation en coordonnées cartésiennes (X, Y) et en tracés géométriques. 

J'ai d'abord défini l'ambiance graphique pour simuler l'espace et le ciel nocturne :
* Un arrière-plan noir profond : " turtle.bgcolor("black") "
* Un tracé couleur Cyan/Néon très lumineux  " #00FFFF "  avec une épaisseur renforcée width(3) pour donner un effet de lignes d'énergie.
* Une vitesse d'exécution rapide  " speed(10) "  pour tracer les formes complexes sans attente.

pour le tracement des lignes :
* j'ai utiliser " t.up() " pour pouvoir rien écrire si je me deplace par (lever le stylo), " t.down() " pour baisser le stylo et " t.goto(x, y) " qui permet de me deplacer .
* pour les ligne droite " t.forward() " et de  courbes complexes à base de rayons variables " circle() " pour donner un bonne forme a la constellation comme les courbes a la queue).
* Utilisation d'un boucle " for i in range (1, 3) " pour la creation de certain motif géométrique au noveau de la tete .


Pour les étoiles : 
* " t.color("yellow") " pour la couleur des points
* Utilisation de la fonction " t.doto() " pour marqué le point

En fin :
* Désactivation du curseur de la tortue à la fin et maintien de la fenêtre ouverte grâce à " turtle.done() "


