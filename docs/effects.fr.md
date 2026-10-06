# Effets

Chaque effet a sa propre section dans le panneau. Cette page suit l'ordre du panneau. Les
nombres entre parenthèses donnent la plage de chaque réglage.

!!! tip
    Sélectionnez une valeur et appuyez sur **Entrée** pour la remettre par défaut.

![La section EFFETS VISUELS](assets/panel-effects.png){ width="480" }

## EFFETS VISUELS

C'est l'effet tilt-shift proprement dit : une zone nette en travers de l'écran, avec un flou
qui augmente au-dessus et en dessous. La météo du mod est dessinée par cet effet, elle a
donc besoin qu'il soit activé.

Flou tilt-shift
:   Active et désactive l'effet tilt-shift.

### NETTETÉ

Netteté suit le sujet
:   Garde la zone nette sur ce que votre caméra regarde : votre personnage, votre véhicule
    ou le sujet d'une caméra fixe. Quand vous dézoomez, la zone nette se resserre, comme une
    vraie maquette vue de plus loin.

Zone nette du sujet (0,05 à 2)
:   La taille de la zone nette autour du sujet quand Netteté suit le sujet est activé.

Hauteur de netteté (0 à 1)
:   La position de la zone nette à l'écran quand Netteté suit le sujet est désactivé.

Zone nette (0 à 0,5)
:   La hauteur de la zone nette quand Netteté suit le sujet est désactivé.

Transition du flou (0,5 à 4)
:   La vitesse à laquelle le flou augmente en dehors de la zone nette. Les valeurs basses
    commencent à flouter tout près d'elle. Les valeurs hautes gardent une plus grande partie
    de l'image nette et réservent le flou le plus fort aux bords de l'écran.

Inclinaison de la netteté (-4 à 4)
:   Incline le plan qui reste net, comme un vrai objectif tilt-shift. Fonctionne avec Flou
    selon la distance.

### FLOU

Force du flou (0 à 0,06)
:   Le flou le plus fort, atteint en haut et en bas de l'écran.

Flou selon la distance
:   Floute selon l'éloignement par rapport au plan net plutôt que selon la position à
    l'écran. Un toit loin derrière votre sujet reste flou, même là où il dépasse dans la
    zone nette.

Effet de distance (0,5 à 40)
:   La vitesse à laquelle le flou augmente avec l'éloignement du plan net, quand Flou selon
    la distance est activé.

Reflets bokeh (0 à 8)
:   Transforme les points lumineux en disques doux, comme les reflets d'une photo macro.

Flou haute qualité
:   Un flou plus doux, un peu plus coûteux en performances.

### COULEUR

Saturation (0 à 3), Contraste (0,5 à 2)
:   La couleur et le contraste de l'image. En les augmentant tous les deux, on obtient
    l'aspect vif d'une maquette peinte.

Vignettage (0 à 1,5)
:   Assombrit les coins de l'écran.

## FLOU DE DISTANCE

La profondeur de champ du jeu, avec vos distances.

Flou de distance
:   Active et désactive la profondeur de champ du jeu.

Flou d'arrière-plan (0 à 1,5)
:   L'intensité du flou de l'arrière-plan.

Flou d'arrière-plan dès (5 à 3000 m), Arrière-plan flou complet à (10 à 6000 m)
:   Là où l'arrière-plan commence à devenir flou, et là où le flou atteint sa pleine
    intensité.

Flou de premier plan (0 à 1,5), Flou de premier plan jusqu'à (0 à 200 m)
:   La même chose pour le premier plan, même si le flou de premier plan du jeu ne se voit
    que peu, voire pas du tout, dans beaucoup de vues.

## COULEUR

L'étalonnage du jeu, avec vos valeurs.

Étalonnage
:   Active et désactive l'étalonnage.

Saturation (0 à 3), Contraste (0,5 à 2), Tons moyens (0,5 à 2), Hautes lumières (0,5 à 2)
:   L'étalonnage lui-même.

Maintenir appliqué
:   Le jeu remet parfois son propre étalonnage en cours de partie. Avec ce réglage activé,
    le mod réapplique le vôtre à chaque image.

## IMAGE

Luminosité (0,5 à 2), Netteté (0 à 3)
:   La luminosité et l'accentuation du jeu.

## CAMÉRA ET OBJECTIF

Distance de la caméra (inactif, ou 1 à 200 m)
:   Permet à la caméra orbitale de reculer bien plus loin que le jeu ne le permet
    normalement, pour regarder la ferme de très haut. Fonctionne à pied en troisième
    personne et sur la caméra extérieure d'un véhicule ; les caméras cabine gardent leur
    propre distance.

Champ de vision personnalisé, Champ de vision (10 à 110 degrés)
:   Remplace le champ de vision de la caméra. Un champ étroit aplatit la scène, comme un
    téléobjectif.

Décentrement horizontal, Décentrement vertical (-0,5 à 0,5)
:   Fait glisser l'image sur le côté ou vers le haut et le bas sans tourner la caméra, comme
    le décentrement d'un objectif tilt-shift.

Vue à plat, Taille de la vue à plat (5 à 400 m)
:   Une vue sans perspective, comme une maquette d'architecte. Taille de la vue à plat
    indique combien de mètres du monde tiennent à l'écran de haut en bas.

## MÉTÉO

Le mod dessine sa propre pluie, sa neige et sa grêle dans l'image pour qu'elles se floutent
avec la miniature. Il n'a pas le choix : la pluie du jeu ne fait pas partie de l'image sur
laquelle travaille l'effet.

Effets météo
:   Active et désactive la pluie, la neige et la grêle du mod.

Suivre la météo du jeu
:   Suit la météo du jeu. Quand il pleut dans le jeu, il pleut dans la miniature, y compris
    pendant le passage d'un temps à l'autre. Désactivez-le pour régler les quantités
    vous-même.

Pluie, Neige, Grêle (0 à 2)
:   La quantité de chacune quand Suivre la météo du jeu est désactivé.

Vent (-2 à 2)
:   La force avec laquelle le vent pousse la pluie, la neige ou la grêle sur le côté. Les
    valeurs négatives la poussent dans l'autre sens.

Vitesse de chute (0,1 à 4)
:   La vitesse de chute. À 1, elle tombe aussi vite que la pluie du jeu.

Flou avec la scène (0 à 4)
:   À quel point la pluie, la neige ou la grêle se fondent dans le flou et le bokeh.

## STOP MOTION

Stop motion
:   Limite le nombre d'images par seconde pour que l'image bouge comme une animation en
    stop motion.

Images par seconde
:   8, 10, 12, 15, 24 ou 30.
