# Fenêtres d'aperçu

Les fenêtres d'aperçu montrent chaque caméra fixe en direct, à côté du panneau, pour
comparer vos cadrages et choisir celui qui vous convient.

!!! info "Activez-les d'abord"
    Les fenêtres d'aperçu ont besoin des [caméras fixes](static-cameras.md). Une fois
    Caméras fixes activé, réglez **Fenêtres d'aperçu** sur OUI dans les lignes EXTRAS du
    panneau.

![La fenêtre d'édition de la timeline caméra avec une fenêtre d'aperçu](assets/timeline-editor.jpg)

## Utiliser les fenêtres

Les fenêtres apparaissent pendant que le panneau est ouvert. Chacune a une barre de titre
avec le numéro et le nom de la caméra, et l'image en direct en dessous.

Faites glisser la barre de titre pour déplacer une fenêtre, ou la poignée de son coin
inférieur droit pour la redimensionner ; l'image garde ses proportions. Un clic sur l'image
fait de cette caméra celle que vous modifiez dans le panneau.

Cliquez sur le cadre ou sur l'épingle pour épingler la fenêtre. Une fenêtre épinglée reste à
l'écran quand vous fermez le panneau, alors que les autres se ferment avec lui.

Les boutons de la barre de titre, de droite à gauche :

| Bouton | Action |
| --- | --- |
| × | Masque la fenêtre. La ligne Fenêtre d'aperçu de la caméra dans le panneau la réaffiche |
| Corbeille | Supprime la caméra, après la question Oui/Non du jeu |
| Vol | Permet d'amener la caméra à une nouvelle position (voir [Mettre une caméra en place en vol libre](static-cameras.md#mettre-une-camera-en-place-en-vol-libre)) |
| Épingle | Garde la fenêtre à l'écran quand le panneau est fermé |

## Couleurs du cadre

Un cadre vert signale la caméra que vous modifiez dans le panneau. Un cadre rouge signale la
caméra à l'antenne, celle qu'affiche le moniteur de la [timeline caméra](timeline.md).

## Détails

La position, la taille et l'épinglage des fenêtres sont enregistrés avec vos caméras, et la
ligne Échelle de l'interface du panneau les redimensionne avec le panneau.

Pour économiser des performances, les fenêtres épinglées se rafraîchissent un peu moins
souvent quand le panneau est fermé. Si vous avez beaucoup de caméras, le panneau affiche des
fenêtres pour huit d'entre elles au plus, autour de celle que vous modifiez.

Un aperçu montre le monde depuis sa caméra, sans les effets du mod. Le rendu tilt-shift, le
flou de distance et la météo n'apparaissent que dans la vue principale.
