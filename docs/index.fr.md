---
hide:
  - navigation
  - toc
---

<div class="ts-hero" markdown>

![Caméra Tilt Shift](assets/logo.png){ .ts-logo }

<div class="ts-hero-text" markdown>

# Caméra Tilt Shift

<p class="ts-lead">Caméra Tilt Shift sert à filmer votre ferme. Le mod donne à Farming Simulator 25 l'aspect d'une photographie tilt-shift, vous laisse placer des caméras sur la carte et passer de l'une à l'autre, et joue tout seul une timeline de plans de caméra, pour que vous puissiez enregistrer des vidéos et des timelapses avec votre logiciel d'enregistrement d'écran. Tout est dessiné en direct dans le jeu : ce que votre enregistreur capture est l'image finale, sans montage ensuite. Le mod n'enregistre rien lui-même.</p>

[Prise en main](getting-started.md){ .md-button .md-button--primary }
[:material-bug-outline: Signaler un problème](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose){ .md-button }

</div>

</div>

![Une cour de ferme vue d'une caméra fixe en hauteur, avec le rendu miniature tilt-shift](assets/hero.jpg){ .ts-shot }

## Ce que fait le mod

Le rendu : une bande horizontale reste nette et tout ce qui se trouve au-dessus et au-dessous devient flou, ce qui donne à la scène l'aspect d'une maquette. Par défaut, la bande nette suit le sujet autour duquel tourne votre caméra, pour que votre véhicule ou votre personnage reste net. Vous pouvez aussi afficher un bokeh sur les points lumineux, rendre les couleurs plus vives et assombrir les coins de l'image, modifier le champ de vision, supprimer la perspective, décentrer l'objectif, reculer la caméra bien plus loin que le jeu ne le permet et limiter le nombre d'images par seconde pour un rendu stop motion. Le mod dessine sa propre pluie, sa propre neige et sa propre grêle, qui suivent la météo du jeu et deviennent floues avec le reste de l'image. Enregistrez les rendus qui vous plaisent comme profils et passez de l'un à l'autre avec un raccourci, même pendant l'enregistrement.

L'effet s'applique aux vues à la troisième personne : à pied à la troisième personne, à la caméra extérieure d'un véhicule, aux caméras du mod lui-même et aux caméras libres ou cinématiques d'autres mods, car il suit toujours la caméra active. Les vues cabine, la première personne et les caméras de véhicule non orientables, comme les caméras de recul, restent telles quelles.

Tous les réglages se trouvent dans un panneau (Ctrl droit + K), utilisable au clavier, à la manette ou à la souris. Un clic sur une section la plie ou la déplie, un clic sur une ligne la sélectionne. Vous modifiez une valeur avec les flèches, d'un clic sur &lt; et &gt; à côté, ou en la faisant glisser sur le côté. Après un clic sur une ligne, la molette modifie sa valeur. L'interrupteur du titre du panneau active et désactive tous les effets. L'échelle de l'interface (0,75x, 1x ou 1,25x) modifie la taille du panneau et de toutes les fenêtres du mod. Le bouton Échap en haut à gauche ferme le panneau, et quand vous le fermez, vous retrouvez la vue depuis laquelle vous l'avez ouvert. Le jeu est assombri derrière le panneau tant qu'il est ouvert. Un réglage qui diffère du rendu appliqué ou enregistré s'affiche en vert avec un astérisque, de même que l'en-tête de sa section ; si vous fermez le panneau alors qu'un profil a des valeurs pas encore enregistrées, il vous demande si vous voulez les enregistrer.

## Extras

Trois extras sont désactivés tant que vous ne les activez pas, l'un après l'autre, dans les lignes EXTRAS du panneau.

<div class="ts-cards" markdown>

<div class="ts-card" markdown>

### Caméras fixes

Ctrl droit + N ajoute une caméra à votre vue actuelle, fixée à un point du monde. Ctrl droit + C passe à cette caméra et revient, et Ctrl droit + V passe à la caméra suivante, pendant que vous continuez à conduire ou à marcher : vous pouvez ainsi filmer votre propre travail depuis le bord du champ. Chaque caméra a ses propres réglages d'effets ou utilise l'un de vos profils, de sorte que chaque angle peut avoir son propre rendu. Vous pouvez orienter une caméra dans le panneau ou la placer en vol libre avec la souris et les touches de déplacement. Tant que vous regardez à travers une caméra, une barre en bas de l'écran rappelle les touches pour revenir ; elle fait partie du HUD et disparaît avec lui. Chaque caméra est marquée sur la mini-carte et sur la carte du menu pause, où vous pouvez la sélectionner pour regarder à travers elle ou la supprimer. Après Passer à la caméra sur la carte, le HUD est masqué et vous regardez à travers la caméra : Ctrl droit + P la place en vol libre, Ctrl droit + K ouvre le panneau et Échap vous ramène en arrière. Les caméras appartiennent à votre partie et sont écrites quand le jeu sauvegarde ; en multijoueur, chaque joueur a les siennes.

[En savoir plus](static-cameras.md)

</div>

<div class="ts-card" markdown>

### Fenêtres d'aperçu

L'image en direct de chaque caméra, affichée à côté du panneau, pour voir tous vos angles en même temps. Vous pouvez déplacer une fenêtre par sa barre de titre, la redimensionner par son coin, l'épingler pour qu'elle reste à l'écran quand le panneau est fermé, la masquer, placer sa caméra à une nouvelle position en vol libre ou supprimer la caméra (après confirmation). La caméra que vous modifiez a un cadre vert, et la caméra à l'antenne un cadre rouge.

[En savoir plus](preview-windows.md)

</div>

<div class="ts-card" markdown>

### Timeline caméra

Une liste de plans qui passe toute seule d'une caméra à l'autre, chaque plan montrant une caméra de 1 seconde à 1 heure, pour qu'un timelapse de vos ouvriers aux champs puisse durer aussi longtemps que vous le souhaitez. Vous la composez dans la fenêtre d'édition : faites glisser des caméras de la palette sur la piste, déplacez les plans pour changer leur ordre et tirez sur leurs bords pour changer leur durée. La molette sert à zoomer, et le moniteur affiche un aperçu. Lancer la timeline (ou Ctrl droit + T) masque le panneau, toutes les fenêtres et le HUD, fait un compte à rebours depuis 3 puis joue la timeline dans la vue principale, en boucle ou une seule fois, en restant sur la dernière caméra à la fin. Les coupes sont silencieuses : aucun message n'apparaît au changement de caméra, pour que rien ne se retrouve dans votre enregistrement. L'horloge de la timeline s'arrête quand le jeu est en pause ou que vous dormez. Appuyez sur Échap pour revenir. La timeline est sauvegardée avec vos caméras.

[En savoir plus](timeline.md)

</div>

</div>

## Raccourcis clavier

| Touche | Action |
| --- | --- |
| **Ctrl droit + K** | Ouvrir ou fermer le panneau |
| **Ctrl droit + J** | Activer ou désactiver tous les effets (vos réglages sont conservés, enregistrés ou non) |
| **Ctrl droit + 1-9** | Appliquer le profil 1-9 et activer les effets ; le même chiffre une seconde fois les désactive |
| **Ctrl droit + N** | Ajouter une caméra fixe à votre vue actuelle |
| **Ctrl droit + C** | Passer à une caméra fixe, ou revenir à la vue directe |
| **Ctrl droit + V** | Passer à la caméra fixe suivante |
| **Ctrl droit + T** | Lancer la timeline caméra ; Ctrl droit + T ou Échap l'arrête |
| **Ctrl droit + P** | Placer une caméra en vol libre pendant que vous regardez à travers elle depuis la carte du menu pause |
| **Vol libre d'une caméra** | Les touches de déplacement la déplacent, la souris la fait tourner, Maj accélère, Entrée enregistre, Échap annule et vous ramène à la vue que vous aviez |
| **Flèches ou pavé numérique** | Sélectionner les lignes du panneau ; Gauche et Droite modifient la valeur (Page préc. et Page suiv. pour les grands pas) |
| **Entrée** | Plier ou déplier une section, ou exécuter la ligne sélectionnée ; Échap : fermer le panneau |
| **Manette** | La croix directionnelle sélectionne les lignes et modifie les valeurs tant que le panneau est ouvert |

!!! note "Limitations connues"

    - La pluie, la neige et la grêle sont simulées, en raison des limites du moteur du jeu. Je les ai rendues aussi proches que possible de la météo du jeu.
    - Certains autocollants, le verre et d'autres matériaux transparents ne sont pas visibles quand le flou tilt-shift est activé. Le flou travaille sur une copie de l'image que le jeu crée avant de dessiner les matériaux transparents.
    - Les fenêtres d'aperçu et le moniteur de la timeline montrent l'image de chaque caméra sans les effets. Le flou tilt-shift et la météo n'apparaissent que dans la vue principale.
    - Quand vous regardez à pied à travers une caméra fixe, le mod vous passe de la première à la troisième personne pour que votre personnage soit visible, et vous y ramène à votre retour à la vue directe. La touche caméra du jeu (C) est sans effet jusqu'à votre retour à la vue directe.
    - Le jeu lui-même n'a pas de touche pour masquer tout le HUD. La timeline et Passer à la caméra sur la carte le masquent pour vous ; quand vous regardez à travers une caméra avec Ctrl droit + C ou Ctrl droit + V, le HUD reste à l'écran.
