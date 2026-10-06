# Effets

Chaque effet a sa propre section dans le panneau. Les sections sont présentées ici dans
l'ordre du panneau. Les nombres entre parenthèses indiquent la plage de chaque réglage.

!!! tip
    Choisissez une valeur et appuyez sur **Entrée** pour la remettre par défaut.

![La section EFFETS VISUELS](assets/panel-effects.png){ width="480" }

## EFFETS VISUELS

C'est l'effet tilt-shift proprement dit : une zone nette en travers de l'écran, avec un
flou qui augmente au-dessus et en dessous. Les effets météo sont dessinés par lui aussi, ils
en ont donc besoin.

Flou tilt-shift
:   Active et désactive l'effet tilt-shift.

### NETTETÉ

Netteté suit le sujet
:   La zone nette suit ce que votre caméra regarde en orbite : votre personnage, votre
    véhicule ou le sujet d'une caméra fixe. Si vous dézoomez, la zone nette se resserre,
    comme une vraie miniature vue de plus loin.

Zone nette du sujet (0,05 à 2)
:   La taille de la zone nette autour du sujet, quand « Netteté suit le sujet » est activé.

Hauteur de netteté (0 à 1)
:   La position de la zone nette à l'écran. Utilisé quand « Netteté suit le sujet » est
    désactivé.

Zone nette (0 à 0,5)
:   La hauteur de la zone nette. Utilisé quand « Netteté suit le sujet » est désactivé.

Transition du flou (0,5 à 4)
:   La façon dont le flou monte hors de la zone nette. Les valeurs basses floutent juste
    après elle ; les valeurs hautes gardent plus net ce qui la borde et réservent le flou aux
    bords.

Inclinaison de la netteté (-4 à 4)
:   Incline le plan net, comme un objectif à bascule. Fonctionne avec « Flou selon la
    distance ».

### FLOU

Force du flou (0 à 0,06)
:   Le flou le plus fort, en haut et en bas de l'image.

Flou selon la distance
:   Floute selon la distance au plan net plutôt que selon la position à l'écran : un toit
    qui dépasse dans la zone nette devient quand même flou s'il est loin derrière votre
    sujet.

Effet de distance (0,5 à 40)
:   La vitesse à laquelle le flou augmente avec la distance au plan net, quand « Flou selon
    la distance » est activé.

Reflets bokeh (0 à 8)
:   Fait s'épanouir les points lumineux en disques doux, comme les reflets d'une photo macro.

Flou haute qualité
:   Un flou plus doux, un peu plus coûteux en performances.

### COULEUR

Saturation (0 à 3), Contraste (0,5 à 2)
:   Couleurs et contraste de l'image, le peps d'une maquette.

Vignettage (0 à 1,5)
:   Assombrit les coins de l'écran.

## FLOU DE DISTANCE

La profondeur de champ du jeu, avec vos distances.

Flou de distance
:   Active et désactive la profondeur de champ du jeu.

Flou d'arrière-plan (0 à 1,5)
:   L'intensité du flou au loin.

Flou d'arrière-plan dès (5 à 3000 m), Arrière-plan flou complet à (10 à 6000 m)
:   Où commence le flou d'arrière-plan et où il atteint toute sa force.

Flou de premier plan (0 à 1,5), Flou de premier plan jusqu'à (0 à 200 m)
:   La même chose pour le premier plan. Le flou de premier plan du jeu se voit peu ou pas du
    tout dans beaucoup de vues.

## COULEUR

L'étalonnage du jeu, avec vos valeurs.

Étalonnage
:   Active et désactive l'étalonnage.

Saturation (0 à 3), Contraste (0,5 à 2), Tons moyens (0,5 à 2), Hautes lumières (0,5 à 2)
:   L'étalonnage lui-même.

Maintenir appliqué
:   Le jeu peut remettre son propre étalonnage en cours de partie. Avec cette option, votre
    étalonnage est réappliqué à chaque image.

## IMAGE

Luminosité (0,5 à 2), Netteté (0 à 3)
:   La luminosité et l'accentuation du jeu.

## CAMÉRA ET OBJECTIF

Distance de la caméra (inactif, ou 1 à 200 m)
:   Permet à la caméra orbitale de reculer bien plus loin que le jeu ne l'autorise, pour la
    vue miniature classique de très haut. S'applique à la troisième personne à pied et à la
    caméra extérieure d'un véhicule ; les caméras cabine gardent leur propre distance.

Champ de vision personnalisé, Champ de vision (10 à 110 degrés)
:   Remplace le champ de vision de la caméra. Un champ étroit aplatit la scène, comme un
    téléobjectif.

Décentrement horizontal, Décentrement vertical (-0,5 à 0,5)
:   Fait glisser l'image de côté ou vers le haut et le bas sans tourner la caméra, comme le
    décentrement d'un objectif tilt-shift.

Vue à plat, Taille de la vue à plat (5 à 400 m)
:   Une vue sans aucune perspective, comme une maquette d'architecte. La taille indique
    combien de mètres du monde tiennent à l'écran de haut en bas.

## MÉTÉO

Pluie, neige et grêle dessinées dans la miniature, pour qu'elles se floutent avec elle. La
pluie du jeu ne fait pas partie de l'image sur laquelle travaille l'effet, le mod dessine
donc la sienne.

Effets météo
:   Active et désactive la pluie, la neige et la grêle du mod.

Suivre la météo du jeu
:   Suit la météo réelle : il pleut dans la miniature quand il pleut dans le jeu, y compris
    pendant le passage d'une météo à l'autre. Désactivez-le pour régler les quantités
    vous-même.

Pluie, Neige, Grêle (0 à 2)
:   La quantité de chacune quand « Suivre la météo du jeu » est désactivé.

Vent (-2 à 2)
:   Jusqu'où le vent pousse les précipitations de côté. Les valeurs négatives les poussent
    dans l'autre sens.

Vitesse de chute (0,1 à 4)
:   La vitesse de chute. 1 correspond à la pluie du jeu.

Flou avec la scène (0 à 4)
:   À quel point les précipitations se fondent dans le flou et le bokeh.

## STOP MOTION

Stop motion
:   Plafonne la fréquence d'images pour un effet stop motion.

Images par seconde
:   8, 10, 12, 15, 24 ou 30 images par seconde.
