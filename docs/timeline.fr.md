# Timeline caméra

La timeline caméra alterne toute seule entre vos caméras fixes. Composez une liste de plans,
chacun une caméra tenue un certain nombre de secondes, lancez-la et laissez vos ouvriers
travailler aux champs pendant que les vues changent d'elles-mêmes : prêt pour un timelapse.

!!! info "Activez-la d'abord"
    La timeline nécessite les [caméras fixes](static-cameras.md) et les
    [fenêtres d'aperçu](preview-windows.md). Une fois les deux activées, passez
    **Timeline caméra** sur OUI dans les lignes EXTRAS du panneau. La section TIMELINE
    CAMÉRA et la fenêtre d'édition apparaissent alors.

![La fenêtre d'édition de la timeline caméra avec une fenêtre d'aperçu](assets/timeline-editor.jpg)

## La fenêtre d'édition

La fenêtre TIMELINE CAMÉRA s'ouvre à côté du panneau. De haut en bas :

Le moniteur
:   L'image de la caméra à la tête de lecture. Cliquez dessus pour lancer ou mettre en pause
    le montage dans le moniteur.

Barre de transport
:   Le bouton **lecture** joue le montage dans le moniteur uniquement : la vue principale ne
    bouge pas. À côté s'affiche le temps. Le bouton **répéter** à droite bascule entre
    **En boucle** et **Une fois** (l'icône de répétition barrée d'un signe d'interdiction).

Palette de caméras
:   Une pastille par caméra. **Cliquez** sur une pastille pour ajouter un plan de cette
    caméra à la fin, ou **faites-la glisser** sur la piste pour insérer le plan à l'endroit
    où vous la lâchez.

Règle et piste
:   Un bloc par plan, coloré selon la caméra.

    - **Cliquez** sur un bloc pour le choisir ; la tête de lecture saute à son début.
    - **Faites glisser** un bloc pour le déplacer plus tôt ou plus tard.
    - **Faites glisser son bord droit** pour changer sa durée, en secondes entières.
    - Cliquez sur son **×** pour le supprimer.
    - **Cliquez** sur la règle ou sur une partie vide de la piste pour déplacer la tête de
      lecture. **Faites glisser** le long de la règle pour parcourir le montage ; faites
      glisser une partie vide de la piste pour la faire défiler.
    - La **molette** zoome autour du pointeur. Une fois zoomé, une barre de défilement
      apparaît sous la piste. Vous pouvez zoomer et faire défiler au-delà de la fin du
      dernier plan.

Lancer la timeline
:   Joue la timeline pour de vrai, dans la vue principale. Son raccourci,
    **Ctrl droit + T**, est affiché à côté.

Comme une fenêtre d'aperçu, l'éditeur se déplace par sa barre de titre et se redimensionne
par la poignée en bas à droite. L'**épingle** le garde à l'écran panneau fermé, et le **×**
le masque (la ligne **Fenêtre d'édition** du panneau le réaffiche). Pendant la lecture du
moniteur, la fenêtre d'aperçu de la caméra affichée dans le moniteur prend un cadre rouge.

## La section TIMELINE CAMÉRA

Tout ce que fait la fenêtre se fait aussi dans le panneau, au clavier ou à la manette.

Lecture
:   Indique où en est la timeline (Arrêtée, ou le plan et les secondes restantes).
    **Entrée** ou un clic la lance, comme Lancer la timeline.

Répéter
:   **En boucle** ou **Une fois**.

Fenêtre d'édition
:   **Affichée** ou **Masquée**.

Aperçu dans la fenêtre
:   Lance ou arrête le montage dans le moniteur de la fenêtre.

Modifier le plan
:   Choisit le plan que modifient les lignes en dessous. Le titre au-dessus compte vos plans
    et leur durée totale. Appuyez sur **Entrée** pour regarder à travers la caméra du plan.

Caméra
:   La caméra que montre ce plan.

Durée
:   La durée du plan, d'une seconde à une heure, par pas d'une seconde (10 secondes avec
    Page préc. et Page suiv.).

Déplacer le plan
:   Déplace le plan plus tôt (Gauche) ou plus tard (Droite).

Ajouter un plan
:   Ajoute un plan après celui choisi, de même durée et avec la caméra suivante : en
    appuyant plusieurs fois, vous parcourez toutes vos caméras.

Supprimer le plan
:   Supprime le plan choisi.

## Lancer la timeline

Appuyez sur **Lancer la timeline**, choisissez la ligne **Lecture** ou appuyez sur
**Ctrl droit + T** :

1. Le panneau se ferme et toutes les fenêtres sont masquées, même épinglées, ainsi que le
   HUD du jeu.
2. « La timeline démarre dans 3.. » compte à rebours depuis 3, au-dessus de « Appuyez sur
   Échap pour revenir ».
3. Les messages disparaissent et la timeline joue dans la vue principale, en changeant de
   caméra sans aucun message à l'écran.

**En boucle**, elle continue jusqu'à ce que vous l'arrêtiez. **Une fois**, elle joue chaque
plan puis reste sur la dernière caméra.

Appuyez sur **Échap** ou **Ctrl droit + T** pour revenir : vous retrouvez votre vue
précédente, le HUD revient et le panneau se rouvre s'il était ouvert.

L'horloge de la timeline s'arrête tant que le jeu est en pause ou que vous dormez, pour
qu'aucun plan ne s'écoule pendant qu'il ne se passe rien.

## Sauvegarde

La timeline est sauvegardée avec vos caméras, dans votre partie. Supprimer une caméra
supprime aussi ses plans.
