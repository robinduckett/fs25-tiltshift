# Le panneau

Tous les réglages du mod se trouvent dans un panneau sur le côté de l'écran.
**Ctrl droit + K** l'ouvre, **Ctrl droit + K** ou **Échap** le ferme. Le jeu continue de
tourner pendant que le panneau est ouvert, mais vos touches pilotent alors le panneau et non
votre personnage ou votre véhicule.

## Disposition

La barre de titre affiche CONFIGURATION TILT-SHIFT. L'icône en forme d'œil et
l'interrupteur à sa droite activent et désactivent tous les effets, comme
**Ctrl droit + J**.

Sous le titre, une ligne indique à qui appartient le rendu que modifient les lignes
d'effets, et d'où vient ce rendu. Il peut s'agir de votre vue en direct avec un profil
enregistré ou un rendu prédéfini, d'une caméra fixe avec son propre rendu, ou d'une caméra
qui utilise un profil enregistré.

Les lignes sont regroupées en sections, comme TILT-SHIFT, EFFETS VISUELS ou MÉTÉO, qui se
plient et se déplient. Au départ, seule la première est ouverte, et le panneau retient
celles que vous ouvrez. En bas, une légende montre les touches valables pour la ligne
sélectionnée.

Une valeur modifiée depuis la dernière application d'un rendu ou le dernier enregistrement
d'un profil passe en vert.

![Le panneau avec la section TILT SHIFT ouverte](assets/panel-main.png){ width="480" }

## Clavier et manette

| Touche | Action |
| --- | --- |
| Flèches **Haut / Bas** | Sélectionner la ligne au-dessus ou en dessous |
| Flèches **Gauche / Droite** | Modifier la valeur ou l'option sélectionnée |
| **Page préc. / Page suiv.** | Modifier la valeur par grands pas |
| **Entrée** ou **Espace** | Plier ou déplier une section, exécuter une action, basculer un interrupteur ou remettre une valeur par défaut |
| **Échap** | Fermer le panneau |

Le pavé numérique fonctionne aussi : 8 et 2 déplacent la sélection, 4 et 6 modifient la
valeur, 7 et 9 font de grands pas, et 5 équivaut à Entrée.

À la manette, la croix directionnelle déplace la sélection et modifie les valeurs. Le bouton
de validation fait comme Entrée, et le bouton retour ferme le panneau.

## Souris

Un clic sur un en-tête de section la plie ou la déplie, un clic sur une ligne la
sélectionne. Les interrupteurs et les actions s'exécutent dès le clic.

Pour modifier une valeur, cliquez sur le `<` ou le `>` à côté (en maintenant **Maj** pour
de grands pas), ou faites glisser la valeur sur le côté.

La molette fait défiler la liste. Pour modifier un réglage à la molette, cliquez d'abord sur
sa ligne. Une barre verte apparaît sur la ligne, et la molette modifie alors cette valeur
jusqu'à ce que vous cliquiez de nouveau sur la ligne.

Les touches Échap et Ctrl droit + J de la légende se cliquent aussi. En dehors du panneau,
la molette zoome toujours votre caméra, comme d'habitude.

## La section TILT-SHIFT

La première section contient les réglages dont vous vous servirez le plus.

Tous les effets
:   L'interrupteur de tout le rendu, comme **Ctrl droit + J**. Le désactiver conserve tous
    les réglages, enregistrés ou non.

Rendu
:   Choisir un rendu prédéfini ou l'un de vos profils enregistrés. Voir
    [Rendus et profils](looks-and-profiles.md).

PROFILS ENREGISTRÉS
:   Enregistrer les modifications, Enregistrer comme nouveau profil, Renommer le profil et
    Supprimer le profil. Voir
    [Rendus et profils](looks-and-profiles.md#enregistrer-votre-propre-rendu).

EXTRAS
:   Caméras fixes, Fenêtres d'aperçu et Timeline caméra. Chaque interrupteur apparaît une
    fois celui du dessus activé. Voir [Caméras fixes](static-cameras.md),
    [Fenêtres d'aperçu](preview-windows.md) et [Timeline caméra](timeline.md).

Échelle de l'interface
:   0,75x, 1x ou 1,25x, pour le panneau et toutes les fenêtres à la fois. À 1x, le panneau a
    la taille du HUD du jeu.

Réinitialiser tous les effets
:   Désactive tous les effets et rétablit le rendu d'origine du jeu. Cela concerne le flou
    tilt-shift, le flou de distance, le stop motion, le champ de vision personnalisé, la vue
    à plat, le décentrement, l'étalonnage, la luminosité, la netteté et la distance de la
    caméra. Vos profils enregistrés ne changent pas.
