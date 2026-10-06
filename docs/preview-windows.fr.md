# Fenêtres d'aperçu

Les fenêtres d'aperçu affichent à côté du panneau l'image en direct de chaque caméra fixe,
pour que vous puissiez voir toutes vos caméras en même temps.

!!! info "Activez-les d'abord"
    Les fenêtres d'aperçu nécessitent les [caméras fixes](static-cameras.md). Une fois
    Caméras fixes activé, réglez **Fenêtres d'aperçu** sur OUI dans les lignes EXTRAS du
    panneau.

![La fenêtre d'édition de la timeline caméra avec une fenêtre d'aperçu](assets/timeline-editor.jpg)

## Utiliser les fenêtres

Les fenêtres s'affichent tant que le panneau est ouvert. Chaque fenêtre a une barre de
titre avec le numéro et le nom de la caméra, et en dessous l'image en direct de la caméra.

Pour déplacer une fenêtre, faites glisser sa barre de titre. Pour la redimensionner, faites
glisser la poignée de son coin inférieur droit ; l'image garde ses proportions. Un clic sur
l'image sélectionne cette caméra pour la modifier dans le panneau.

Pour qu'une fenêtre reste à l'écran après la fermeture du panneau, cliquez sur son cadre ou
sur l'épingle. Les fenêtres non épinglées se ferment avec le panneau.

Les boutons de la barre de titre, de droite à gauche :

| Bouton | Action |
| --- | --- |
| × | Masque la fenêtre. La ligne Fenêtre d'aperçu de la caméra, dans le panneau, permet de la réafficher |
| Corbeille | Supprime la caméra, après la boîte de dialogue Oui/Non du jeu |
| Vol | Permet de placer la caméra à une nouvelle position en vol libre (voir [Placer une caméra en vol libre](static-cameras.md#placer-une-camera-en-vol-libre)) |
| Épingle | Garde la fenêtre à l'écran quand le panneau est fermé |

## Couleurs du cadre

La caméra que vous modifiez dans le panneau a un cadre vert. La caméra à l'antenne,
c'est-à-dire celle qu'affiche le moniteur de la [timeline caméra](timeline.md), a un cadre
rouge.

## Détails

La position, la taille et l'épinglage de chaque fenêtre sont enregistrés avec vos caméras.
La ligne Échelle de l'interface du panneau modifie la taille des fenêtres en même temps que
celle du panneau.

Pour économiser des performances, les fenêtres épinglées sont mises à jour un peu moins
souvent quand le panneau est fermé. Si vous avez beaucoup de caméras, le panneau affiche
les fenêtres de huit d'entre elles au maximum, autour de la caméra que vous modifiez.

Les fenêtres d'aperçu montrent l'image de chaque caméra sans les effets du mod. Le flou
tilt-shift, le flou de distance et les effets météo n'apparaissent que dans la vue
principale.
