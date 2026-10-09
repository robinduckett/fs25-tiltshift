# Timeline caméra

La timeline caméra passe automatiquement d'une caméra fixe à l'autre. Vous créez une liste
de plans, chacun montrant une caméra pendant un nombre de secondes donné, puis vous lancez
la timeline. C'est pratique, par exemple, pour enregistrer un timelapse pendant que vos
ouvriers travaillent aux champs, ou une vidéo qui passe d'un angle de la ferme à l'autre.

!!! info "Activez-la d'abord"
    La timeline nécessite les [caméras fixes](static-cameras.md) et les
    [fenêtres d'aperçu](preview-windows.md). Une fois les deux activées, réglez
    **Timeline caméra** sur OUI dans les lignes EXTRAS du panneau. La section TIMELINE
    CAMÉRA et la fenêtre d'édition apparaissent alors.

![La fenêtre d'édition de la timeline caméra avec une fenêtre d'aperçu](assets/timeline-editor.jpg)

## La fenêtre d'édition

La fenêtre TIMELINE CAMÉRA s'ouvre à côté du panneau. De haut en bas, elle contient :

Le moniteur
:   Affiche l'image de la caméra à la tête de lecture. Cliquez dessus pour lancer ou mettre
    en pause la lecture de la timeline dans le moniteur.

Lecture
:   Le bouton de lecture joue la timeline dans le moniteur uniquement ; la vue principale
    ne change pas. Le temps est affiché à côté. Le bouton de répétition, à droite, alterne
    entre En boucle et Une fois. En mode Une fois, l'icône de répétition est barrée.

Palette de caméras
:   Une puce par caméra. Cliquez sur une puce pour ajouter un plan de cette caméra à la fin
    de la timeline, ou faites-la glisser sur la piste pour insérer le plan à cet endroit.

Règle et piste
:   La piste affiche un bloc par plan, coloré selon la caméra. Vous pouvez :

    - cliquer sur un bloc pour le sélectionner et placer la tête de lecture à son début ;
    - faire glisser un bloc pour avancer ou reculer le plan ;
    - faire glisser le bord droit d'un bloc pour changer la durée du plan, en secondes
      entières ;
    - cliquer sur le × d'un bloc pour supprimer le plan.

    Un clic sur la règle ou sur une partie vide de la piste déplace la tête de lecture.
    Faites glisser le long de la règle pour parcourir la timeline, ou faites glisser une
    partie vide de la piste pour la faire défiler. La molette zoome autour du pointeur ;
    quand vous zoomez, une barre de défilement apparaît sous la piste. Vous pouvez zoomer
    et faire défiler au-delà de la fin du dernier plan.

Lancer la timeline
:   Joue la timeline dans la vue principale. Son raccourci, **Ctrl droit + T**, est affiché
    à côté du bouton.

Vous déplacez et redimensionnez la fenêtre d'édition comme une fenêtre d'aperçu, avec sa
barre de titre et la poignée de son coin inférieur droit. L'épingle la garde à l'écran
quand le panneau est fermé, et le × la masque (la ligne Fenêtre d'édition du panneau
permet de la réafficher). Pendant la lecture dans le moniteur, la fenêtre d'aperçu de la
caméra affichée dans le moniteur a un cadre rouge.

## La section TIMELINE CAMÉRA

Tout ce que fait la fenêtre peut aussi se faire dans le panneau, au clavier ou à la
manette.

Lecture
:   Indique si la timeline est arrêtée ou, pendant la lecture, le plan en cours et les
    secondes restantes. Appuyez sur **Entrée** ou cliquez sur la ligne pour lancer la
    timeline, comme avec Lancer la timeline.

Répéter
:   **En boucle** ou **Une fois**.

Fenêtre d'édition
:   **Affichée** ou **Masquée**.

Aperçu dans la fenêtre
:   Lance ou arrête la lecture de la timeline dans le moniteur de la fenêtre d'édition.

Modifier le plan
:   Choisit le plan que modifient les lignes en dessous. Le titre au-dessus indique le
    nombre de plans et leur durée totale. Appuyez sur **Entrée** pour regarder à travers la
    caméra du plan.

Caméra
:   La caméra montrée par le plan.

Durée
:   La durée du plan, de 1 seconde à 1 heure, par pas de 1 seconde (10 secondes avec
    Page préc. et Page suiv.).

Déplacer le plan
:   Avance (Gauche) ou recule (Droite) le plan dans la timeline.

Ajouter un plan
:   Ajoute un plan après le plan sélectionné, avec la même durée et la caméra suivante.
    Appuyez plusieurs fois pour obtenir un plan pour chaque caméra.

Supprimer le plan
:   Supprime le plan sélectionné.

## Lancer la timeline

Pour lancer la timeline, cliquez sur **Lancer la timeline**, choisissez la ligne Lecture ou
appuyez sur **Ctrl droit + T**. Le panneau se ferme et toutes les fenêtres sont masquées,
y compris les fenêtres épinglées, de même que le HUD du jeu. Le message « La timeline
démarre dans 3.. » fait un compte à rebours, avec « Appuyez sur Échap pour revenir » en
dessous. Ensuite, les messages disparaissent et la timeline est jouée dans la vue
principale. Aucun message ne s'affiche lors des changements de caméra. Pendant la lecture,
rien du mod n'apparaît à l'écran : lancez votre enregistrement d'écran une fois le compte à
rebours terminé et arrêtez-le avant d'appuyer sur Échap.

En mode **En boucle**, la timeline recommence jusqu'à ce que vous l'arrêtiez. En mode
**Une fois**, elle joue chaque plan une fois puis reste sur la dernière caméra.

Appuyez sur **Échap** ou **Ctrl droit + T** pour l'arrêter. Vous retrouvez la vue que vous
aviez avant, le HUD réapparaît et le panneau se rouvre s'il était ouvert au lancement.

L'horloge de la timeline s'arrête quand le jeu est en pause ou que vous dormez : aucun plan
ne s'écoule pendant que rien ne se passe.

## Sauvegarde

La timeline est sauvegardée avec vos caméras, dans votre partie. Quand vous supprimez une
caméra, ses plans sont aussi supprimés.
