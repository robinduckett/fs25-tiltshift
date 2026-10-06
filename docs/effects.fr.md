# Effets

Chaque effet a sa propre section dans le panneau. Cette page les décrit dans l'ordre du
panneau. Les nombres entre parenthèses indiquent la plage de chaque réglage.

!!! tip
    Sélectionnez une valeur et appuyez sur **Entrée** pour rétablir sa valeur par défaut.

![La section EFFETS VISUELS](assets/panel-effects.png){ width="480" }

## EFFETS VISUELS

C'est l'effet tilt-shift : une zone nette horizontale, avec un flou qui augmente au-dessus
et au-dessous. La pluie, la neige et la grêle du mod sont dessinées par le même effet et
n'apparaissent donc que lorsqu'il est activé.

Flou tilt-shift
:   Active ou désactive l'effet tilt-shift.

### NETTETÉ

Netteté suit le sujet
:   Garde la zone nette sur ce autour de quoi tourne votre caméra : votre personnage, votre
    véhicule ou le sujet d'une caméra fixe. Plus vous dézoomez, plus la zone nette se
    rétrécit.

Zone nette du sujet (0,05 à 2)
:   La taille de la zone nette autour du sujet, quand « Netteté suit le sujet » est activé.

Hauteur de netteté (0 à 1)
:   La hauteur de la zone nette à l'écran, quand « Netteté suit le sujet » est désactivé.
    0,5 correspond au milieu de l'écran.

Zone nette (0 à 0,5)
:   La hauteur de la zone nette, quand « Netteté suit le sujet » est désactivé.

Transition du flou (0,5 à 4)
:   La vitesse à laquelle le flou augmente en dehors de la zone nette. Avec une valeur
    basse, tout ce qui est hors de la zone nette devient vite flou. Avec une valeur haute,
    une plus grande partie de l'image reste nette et le flou se concentre sur les bords
    haut et bas.

Inclinaison de la netteté (-4 à 4)
:   Incline le plan de netteté, comme le fait un objectif tilt-shift. N'a d'effet que si
    « Flou selon la distance » est activé.

### FLOU

Force du flou (0 à 0,06)
:   Le flou maximal, atteint en haut et en bas de l'écran.

Flou selon la distance
:   Calcule le flou en fonction de la distance au plan de netteté plutôt que de la position
    à l'écran. Par exemple, un toit loin derrière votre sujet reste flou même s'il entre
    dans la zone nette.

Effet de distance (0,5 à 40)
:   La vitesse à laquelle le flou augmente avec la distance au plan de netteté, quand
    « Flou selon la distance » est activé.

Reflets bokeh (0 à 8)
:   Transforme les points lumineux des zones floues en disques ronds et doux.

Flou haute qualité
:   Un flou plus régulier, un peu plus gourmand en performances.

### COULEUR

Saturation (0 à 3), Contraste (0,5 à 2)
:   La saturation et le contraste de l'image. Des valeurs plus élevées rendent les couleurs
    plus vives.

Vignettage (0 à 1,5)
:   Assombrit les coins de l'écran.

## FLOU DE DISTANCE

La profondeur de champ du jeu, avec les distances que vous choisissez.

Flou de distance
:   Active ou désactive la profondeur de champ du jeu.

Flou d'arrière-plan (0 à 1,5)
:   L'intensité du flou de l'arrière-plan.

Flou d'arrière-plan dès (5 à 3000 m), Arrière-plan flou complet à (10 à 6000 m)
:   La distance à partir de laquelle l'arrière-plan devient flou, et celle à partir de
    laquelle le flou atteint son intensité maximale.

Flou de premier plan (0 à 1,5), Flou de premier plan jusqu'à (0 à 200 m)
:   La même chose pour le premier plan. Dans beaucoup de vues, le jeu n'affiche que peu ou
    pas de flou au premier plan.

## COULEUR

L'étalonnage du jeu, avec les valeurs que vous choisissez.

Étalonnage
:   Active ou désactive l'étalonnage.

Saturation (0 à 3), Contraste (0,5 à 2), Tons moyens (0,5 à 2), Hautes lumières (0,5 à 2)
:   Les valeurs de l'étalonnage.

Maintenir appliqué
:   Le jeu rétablit parfois son propre étalonnage en cours de partie. Avec « Maintenir
    appliqué », le mod réapplique vos valeurs à chaque image.

## IMAGE

Luminosité (0,5 à 2), Netteté (0 à 3)
:   La luminosité et l'accentuation de la netteté du jeu.

## CAMÉRA ET OBJECTIF

Distance de la caméra (inactif, ou 1 à 200 m)
:   Permet à la caméra à la troisième personne de reculer bien plus loin que le jeu ne le
    permet normalement, pour regarder la ferme de très haut. Fonctionne à pied à la
    troisième personne et avec la caméra extérieure d'un véhicule. Les caméras cabine ne
    sont pas concernées.

Champ de vision personnalisé, Champ de vision (10 à 110 degrés)
:   Remplace le champ de vision de la caméra. Un champ de vision étroit aplatit la scène,
    comme un téléobjectif.

Décentrement horizontal, Décentrement vertical (-0,5 à 0,5)
:   Déplace l'image sur le côté ou vers le haut et le bas sans tourner la caméra, comme la
    fonction de décentrement d'un objectif tilt-shift.

Vue à plat, Taille de la vue à plat (5 à 400 m)
:   La vue à plat supprime la perspective : les objets gardent la même taille quelle que
    soit leur distance. « Taille de la vue à plat » indique combien de mètres du monde
    tiennent à l'écran, de haut en bas.

## MÉTÉO

La pluie du jeu ne fait pas partie de l'image sur laquelle travaille l'effet, elle ne
serait donc pas floue. Le mod dessine à la place sa propre pluie, sa propre neige et sa
propre grêle, qui deviennent floues avec le reste de l'image.

Effets météo
:   Active ou désactive la pluie, la neige et la grêle du mod.

Suivre la météo du jeu
:   Suit la météo du jeu, y compris le passage d'un type de temps au suivant. Désactivez ce
    réglage pour choisir les quantités vous-même.

Pluie, Neige, Grêle (0 à 2)
:   La quantité de chacune quand « Suivre la météo du jeu » est désactivé.

Vent (-2 à 2)
:   À quel point la pluie, la neige et la grêle sont poussées sur le côté. Les valeurs
    négatives les poussent dans l'autre sens.

Vitesse de chute (0,1 à 4)
:   La vitesse à laquelle elles tombent. 1 correspond à la vitesse normale.

Flou avec la scène (0 à 4)
:   À quel point la pluie, la neige et la grêle deviennent floues avec le reste de l'image.

## STOP MOTION

Stop motion
:   Limite le nombre d'images par seconde pour que les mouvements ressemblent à une
    animation en stop motion.

Images par seconde
:   8, 10, 12, 15, 24 ou 30.
