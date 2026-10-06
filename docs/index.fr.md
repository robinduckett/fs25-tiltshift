---
hide:
  - navigation
  - toc
---

<div class="ts-hero" markdown>

![Caméra Tilt Shift](assets/logo.png){ .ts-logo }

<div class="ts-hero-text" markdown>

# Caméra Tilt Shift

<p class="ts-lead">Transformez votre ferme en miniature vivante. Caméra Tilt Shift ajoute aux vues à la troisième personne un effet tilt-shift réglable en direct : une bande de netteté basée sur la profondeur qui suit la cible de votre caméra, un bokeh pondéré par la luminosité, un étalonnage de saturation et de contraste, une limite d'images façon stop motion en option et des réglages d'objectif supplémentaires (champ de vision, vue orthographique, distance de caméra étendue). Une couche météo procédurale optionnelle ajoute pluie, neige et grêle qui se floutent avec la miniature et peuvent suivre le ciel réel. Enregistrez vos réglages préférés comme profils.</p>

[Prise en main](getting-started.md){ .md-button .md-button--primary }
[:material-bug-outline: Signaler un problème](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose){ .md-button }

</div>

</div>

![Une cour de ferme vue d'une caméra fixe en hauteur, avec le rendu miniature tilt-shift](assets/hero.jpg){ .ts-shot }

## Ce que fait le mod

L'effet ne s'applique qu'aux caméras à la troisième personne : les vues cabine, la première personne et les caméras fixes des véhicules restent intactes. Il fonctionne aussi avec les caméras libres et cinématiques d'autres mods, car il suit la caméra active.

Le panneau (Ctrl droit + K) se pilote au clavier, à la manette et à la souris : un clic sur une section la plie ou la déplie, un clic sur une ligne la sélectionne, les valeurs se règlent avec les flèches, d'un clic sur &lt; et &gt; ou en les faisant glisser de côté, et une fois une ligne cliquée la molette ajuste sa valeur. L'interrupteur du titre active et désactive les effets. L'échelle de l'interface (0,75x, 1x, 1,25x) redimensionne ensemble le panneau et toutes les fenêtres.

## Extras

Désactivés jusqu'à ce que vous les activiez l'un après l'autre dans la rubrique EXTRAS du panneau.

<div class="ts-cards" markdown>

<div class="ts-card" markdown>

### Caméras fixes

Ctrl droit + N pose une caméra exactement là où se trouve votre vue, ancrée dans le monde. Passez à elle et revenez avec Ctrl droit + C, parcourez vos caméras avec Ctrl droit + V, et continuez à conduire ou à marcher pendant qu'elles filment. Chaque caméra garde son propre rendu tilt-shift (ou un profil) et peut être orientée depuis le panneau ou mise en place en vol libre avec la souris et les touches de déplacement. Les caméras appartiennent à votre partie, et en multijoueur chaque joueur garde les siennes. Chaque caméra apparaît aussi sur la carte du menu pause et sur la mini-carte : sélectionnez-la sur la carte pour passer à elle ou la supprimer.

[En savoir plus](static-cameras.md)

</div>

<div class="ts-card" markdown>

### Fenêtres d'aperçu

Une image en direct de chaque caméra à côté du panneau. Déplacez une fenêtre par son titre, redimensionnez-la par son coin, épinglez-la pour la garder à l'écran panneau fermé, masquez-la, repositionnez sa caméra en vol libre ou supprimez-la (après confirmation). La caméra en cours de modification a un cadre vert, la caméra à l'antenne un cadre rouge.

[En savoir plus](preview-windows.md)

</div>

<div class="ts-card" markdown>

### Timeline caméra

Une fenêtre d'édition qui alterne automatiquement entre vos caméras, pensée pour les timelapses de vos ouvriers aux champs. Glissez des caméras de la palette sur la piste, glissez les plans pour les réordonner et leur bord pour leur durée, zoomez à la molette et prévisualisez le montage dans le moniteur. Lancer la timeline (ou Ctrl droit + T) masque le panneau, toutes les fenêtres et le HUD, compte à rebours depuis 3 et joue la timeline dans la vue principale, en boucle ou une fois en restant sur la dernière caméra. Appuyez sur Échap pour revenir. La timeline est sauvegardée avec vos caméras.

[En savoir plus](timeline.md)

</div>

</div>

## Raccourcis clavier

| Touche | Action |
| --- | --- |
| **Ctrl droit + K** | Ouvrir / fermer le panneau de configuration |
| **Ctrl droit + J** | Tous les effets activés / désactivés (vos réglages actuels sont conservés, même non enregistrés) |
| **Ctrl droit + 1-9** | Appliquer le profil 1-9 et activer les effets ; le même chiffre à nouveau les désactive |
| **Ctrl droit + N** | Ajouter une caméra fixe à la vue actuelle |
| **Ctrl droit + C** | Caméra fixe activée / désactivée (retour à la vue directe) |
| **Ctrl droit + V** | Caméra fixe suivante |
| **Ctrl droit + T** | Lancer la timeline caméra ; Ctrl droit + T ou Échap revient |
| **Vol libre d'une caméra** | Les touches de déplacement la bougent, la souris l'oriente, Maj accélère, Entrée enregistre, Échap annule |
| **Flèches ou pavé numérique** | Naviguer dans le panneau ; Gauche / Droite ajustent (Page préc. / Page suiv. pour les grands pas) |
| **Entrée** | Plier / déplier une section ou exécuter la ligne choisie ; Échap : fermer le panneau |
| **Manette** | La croix directionnelle navigue et ajuste tant que le panneau est ouvert |

!!! note "Limitations connues"

    - Les effets météo sont simulés en raison de limites fondamentales du moteur du jeu ; ils sont aussi fidèles que possible.
    - Certaines décalcomanies, le verre et d'autres matériaux transparents ne sont pas visibles lorsque les effets sont actifs : les effets utilisent la refraction map, rendue avant les matériaux transparents.
    - Les fenêtres d'aperçu montrent le monde sans effet : le rendu tilt-shift et la météo n'apparaissent que dans la vue principale.
    - Tant qu'une caméra fixe est active, la vue à la première personne à pied passe en troisième personne pour que vous restiez visible, et la touche caméra du jeu (C) est remplacée jusqu'au retour à la vue directe.
