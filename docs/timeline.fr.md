# Timeline caméra

La timeline caméra passe toute seule d'une caméra fixe à l'autre. Vous composez une liste de
plans, chacun une caméra tenue un certain nombre de secondes, puis vous la lancez. Pendant
que vos ouvriers travaillent aux champs, la vue change sans arrêt, ce qui facilite
l'enregistrement d'un timelapse.

!!! info "Activez-la d'abord"
    La timeline a besoin des [caméras fixes](static-cameras.md) et des
    [fenêtres d'aperçu](preview-windows.md). Une fois les deux activées, réglez
    **Timeline caméra** sur OUI dans les lignes EXTRAS du panneau. La section
    TIMELINE CAMÉRA et la fenêtre d'édition apparaissent alors.

![La fenêtre d'édition de la timeline caméra avec une fenêtre d'aperçu](assets/timeline-editor.jpg)

## La fenêtre d'édition

La fenêtre TIMELINE CAMÉRA s'ouvre à côté du panneau. De haut en bas, elle contient :

Le moniteur
:   L'image de la caméra sous la tête de lecture. Cliquez dessus pour lire le montage dans
    le moniteur ou le mettre en pause.

Transport
:   Le bouton de lecture lit le montage dans le moniteur uniquement ; la vue principale ne
    bouge pas. Le temps s'affiche à côté. Le bouton de répétition, à droite, passe de
    En boucle à Une fois ; en mode Une fois, l'icône de répétition est barrée d'un signe
    d'interdiction.

Palette de caméras
:   Une puce par caméra. Cliquez sur une puce pour ajouter un plan de cette caméra à la fin,
    ou faites-la glisser sur la piste pour insérer le plan là où vous la lâchez.

Règle et piste
:   Un bloc par plan, coloré selon la caméra. Sur la piste, vous pouvez :

    - cliquer sur un bloc pour le sélectionner, ce qui place la tête de lecture à son début ;
    - faire glisser un bloc pour le placer plus tôt ou plus tard ;
    - faire glisser son bord droit pour l'allonger ou le raccourcir, par secondes entières ;
    - cliquer sur son × pour le supprimer.

    Un clic sur la règle ou sur une partie vide de la piste déplace la tête de lecture.
    Faire glisser le long de la règle parcourt le montage, et faire glisser une partie vide
    de la piste la fait défiler. La molette zoome autour du pointeur, et une barre de
    défilement apparaît sous la piste tant que vous êtes zoomé. Vous pouvez zoomer et faire
    défiler au-delà de la fin du dernier plan.

Lancer la timeline
:   Lit la timeline dans la vue principale. Son raccourci, **Ctrl droit + T**, est affiché à
    côté.

La fenêtre d'édition fonctionne comme une fenêtre d'aperçu : sa barre de titre sert à la
déplacer et la poignée de son coin inférieur droit à la redimensionner. L'épingle la garde à
l'écran quand le panneau est fermé, et × la masque (la ligne Fenêtre d'édition du panneau la
fait revenir). Pendant la lecture dans le moniteur, la fenêtre d'aperçu de la caméra
affichée dans le moniteur prend un cadre rouge.

## La section TIMELINE CAMÉRA

Tout ce que fait la fenêtre peut aussi se faire depuis le panneau, au clavier ou à la
manette.

Lecture
:   Indique si la timeline est arrêtée ou, pendant la lecture, le plan en cours et les
    secondes restantes. **Entrée** ou un clic lance la timeline, comme Lancer la timeline.

Répéter
:   **En boucle** ou **Une fois**.

Fenêtre d'édition
:   **Affichée** ou **Masquée**.

Aperçu dans la fenêtre
:   Lit ou arrête le montage dans le moniteur de la fenêtre.

Modifier le plan
:   Choisit le plan que modifient les lignes en dessous. Le titre au-dessus indique le
    nombre de plans et leur durée totale. **Entrée** permet de regarder par la caméra du
    plan.

Caméra
:   La caméra que montre le plan.

Durée
:   La durée du plan, de 1 seconde à une heure, par pas de 1 seconde (10 secondes avec
    Page préc. et Page suiv.).

Déplacer le plan
:   Place le plan plus tôt (Gauche) ou plus tard (Droite).

Ajouter un plan
:   Ajoute après le plan sélectionné un plan de même durée avec la caméra suivante de la
    liste. En appuyant plusieurs fois, vous obtenez un plan par caméra.

Supprimer le plan
:   Supprime le plan sélectionné.

## Lancer la timeline

Appuyez sur **Lancer la timeline**, choisissez la ligne Lecture ou appuyez sur
**Ctrl droit + T**. Le panneau se ferme et toutes les fenêtres disparaissent (même celles
qui sont épinglées), ainsi que le HUD du jeu. Un message affiche le compte à rebours « La
timeline démarre dans 3.. », avec « Appuyez sur Échap pour revenir » en dessous. Ensuite,
les messages disparaissent et la timeline se lit dans la vue principale. Elle change de
caméra sans afficher de message.

En mode **En boucle**, la timeline recommence jusqu'à ce que vous l'arrêtiez. En mode
**Une fois**, elle lit chaque plan puis reste sur la dernière caméra.

Appuyez sur **Échap** ou **Ctrl droit + T** pour revenir. Vous retrouvez la vue d'avant, le
HUD revient, et le panneau se rouvre s'il était ouvert au lancement.

L'horloge de la timeline s'arrête quand le jeu est en pause ou que vous dormez, pour
qu'aucun plan ne s'écoule pendant qu'il ne se passe rien.

## Sauvegarde

La timeline est sauvegardée avec vos caméras, dans votre partie. Supprimer une caméra
supprime aussi ses plans.
