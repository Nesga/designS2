# Simulation de la vision du caméléon avec Processing, boutons Arduino

On a pris l'image jungle.jpg et on l'a découpée en deux verticalement, donnant deux images : jungledroite.jpg et junglegauche.jpg.
Dans le dossier cameleon, il y a un sketch Processing. 

Le programme utilise les deux images générées ci-dessus, sélectionne une portion pour chacune et met ces deux portions côte à côte sur l'écran. 

On connecte une carte Arduino avec 4 boutons. Deux servent à translater la portion de gauche de haut en bas et deux autres servent à translater celle de droite.

+ 4 boutons
+ 4 résistances MARRON NOIR ORANGE

Schéma (on a utilisé le même montage qu'avec les servos): 
![Schéma](https://github.com/Mistergix/designS2/blob/master/Rendu/2cameleon_avec_arduino_boutons_poussoirs/4bouttons.jpg)
