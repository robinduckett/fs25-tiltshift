# Effets

Chaque effet a sa propre section dans le panneau. Les sections sont présentées ici dans
l'ordre du panneau. Les nombres entre parenthèses indiquent la plage de chaque réglage.

!!! tip
    Choisissez une valeur et appuyez sur **Entrée** pour la remettre par défaut.

## SHADER ÉCRAN

C'est l'effet tilt-shift proprement dit : une bande nette en travers de l'écran, avec un
flou qui augmente au-dessus et en dessous. Les effets météo sont dessinés par lui aussi, ils
en ont donc besoin.

Quad de shader
:   Active et désactive l'effet tilt-shift.

### BANDE DE NETTETÉ

Bande auto
:   La bande nette suit ce que votre caméra regarde en orbite : votre personnage, votre
    véhicule ou le sujet d'une caméra fixe. Si vous dézoomez, la bande se resserre, comme
    une vraie miniature vue de plus loin.

Échelle de bande auto (0,05 à 2)
:   La largeur de la bande automatique autour du sujet.

Centre de netteté Y (0 à 1)
:   La position de la bande nette à l'écran. Utilisé quand la bande auto est désactivée.

Demi-largeur de bande nette (0 à 0,5)
:   La hauteur de la bande nette. Utilisé quand la bande auto est désactivée.

Puissance du dégradé (0,5 à 4)
:   La façon dont le flou monte hors de la bande. Les valeurs basses floutent juste après la
    bande ; les valeurs hautes gardent plus net ce qui la borde et réservent le flou aux
    bords.

Inclinaison du plan focal (-4 à 4)
:   Incline le plan net, comme un objectif à bascule. Fonctionne avec le flou basé sur la
    profondeur.

### FLOU

Flou max. (0 à 0,06)
:   Le flou le plus fort, en haut et en bas de l'image.

Flou basé sur la profondeur
:   Floute selon la distance au plan net plutôt que selon la position à l'écran : un toit
    qui dépasse dans la bande nette devient quand même flou s'il est loin derrière votre
    sujet.

Intensité de profondeur (0,5 à 40)
:   La vitesse à laquelle le flou augmente avec la distance au plan net, quand le flou basé
    sur la profondeur est actif.

Amplification du bokeh (0 à 8)
:   Fait s'épanouir les points lumineux en disques doux, comme les reflets d'une photo macro.

Flou haute qualité
:   Un flou plus doux, un peu plus coûteux en performances.

### RENDU

Saturation du shader (0 à 3), Contraste du shader (0,5 à 2)
:   Couleurs et contraste de l'image, le peps d'une maquette.

Vignettage (0 à 1,5)
:   Assombrit les coins de l'écran.

## PROFONDEUR DE CHAMP

La profondeur de champ du jeu, avec vos distances.

Flou
:   Active et désactive la profondeur de champ du jeu.

Rayon lointain (0 à 1,5)
:   L'intensité du flou au loin.

Début lointain (5 à 3000 m), Fin lointaine (10 à 6000 m)
:   Où commence le flou lointain et où il atteint toute sa force.

Rayon proche (0 à 1,5), Fin proche (0 à 200 m)
:   La même chose pour le premier plan. Le flou proche du jeu se voit peu ou pas du tout dans
    beaucoup de vues.

## ÉTALONNAGE

L'étalonnage du jeu, avec vos valeurs.

Étalonnage
:   Active et désactive l'étalonnage.

Saturation (0 à 3), Contraste (0,5 à 2), Gamma (0,5 à 2), Gain (0,5 à 2)
:   L'étalonnage lui-même.

Réappliquer chaque image
:   Le jeu peut remettre son propre étalonnage en cours de partie. Avec cette option, votre
    étalonnage est réappliqué à chaque image.

## POST-TRAITEMENT

Luminosité (0,5 à 2), Netteté (0 à 3)
:   La luminosité et l'accentuation du jeu.

## OBJECTIF + CAMÉRA

Distance de la caméra (inactif, ou 1 à 200 m)
:   Permet à la caméra orbitale de reculer bien plus loin que le jeu ne l'autorise, pour la
    vue miniature classique de très haut. S'applique à la troisième personne à pied et à la
    caméra extérieure d'un véhicule ; les caméras cabine gardent leur propre distance.

Remplacer le champ de vision, Champ de vision (10 à 110 degrés)
:   Remplace le champ de vision de la caméra. Un champ étroit aplatit la scène, comme un
    téléobjectif.

Shift X, Shift Y (-0,5 à 0,5)
:   Décentrement : fait glisser l'image de côté ou vers le haut et le bas sans tourner la
    caméra, comme le décentrement d'un objectif tilt-shift.

Orthographique, Hauteur ortho (5 à 400 m)
:   Une vue sans aucune perspective, comme une maquette d'architecte. La hauteur ortho
    indique combien de mètres du monde tiennent à l'écran de haut en bas.

## MÉTÉO

Pluie, neige et grêle dessinées dans la miniature, pour qu'elles se floutent avec elle. La
pluie du jeu ne fait pas partie de l'image sur laquelle travaille l'effet, le mod dessine
donc la sienne.

Précipitations
:   Active et désactive la pluie, la neige et la grêle du mod.

Suivre le ciel
:   Suit la météo réelle : il pleut dans la miniature quand il pleut dans le jeu, y compris
    pendant le passage d'une météo à l'autre. Désactivez-le pour régler les quantités
    vous-même.

Pluie, Neige, Grêle (0 à 2)
:   La quantité de chacune quand « Suivre le ciel » est désactivé.

Dérive du vent (-2 à 2)
:   Jusqu'où le vent pousse les précipitations de côté. Les valeurs négatives les poussent
    dans l'autre sens.

Vitesse de chute (0,1 à 4)
:   La vitesse de chute. 1 correspond à la pluie du jeu.

Fondu du flou (0 à 4)
:   À quel point les précipitations se fondent dans le flou et le bokeh.

## STOP MOTION

Limite d'images
:   Plafonne la fréquence d'images pour un effet stop motion.

FPS cible
:   8, 10, 12, 15, 24 ou 30 images par seconde.
