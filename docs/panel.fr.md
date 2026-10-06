# Le panneau

Tout le mod se règle dans un panneau sur le côté de l'écran. Appuyez sur **Ctrl droit + K**
pour l'ouvrir, et sur **Ctrl droit + K** ou **Échap** pour le fermer. Pendant qu'il est
ouvert, le jeu continue, mais vos touches pilotent le panneau au lieu de votre personnage ou
de votre véhicule.

## Disposition

- **La barre de titre** indique CONFIGURATION TILT-SHIFT. L'interrupteur avec l'icône d'œil
  à sa droite active et désactive tous les effets, comme **Ctrl droit + J**.
- **La ligne sous le titre** indique quel rendu les lignes d'effets modifient en ce moment
  et d'où il vient : la vue directe avec un profil enregistré ou un rendu prédéfini, une
  caméra fixe avec son propre rendu, ou une caméra qui utilise un profil enregistré.
- **Les sections** comme TILT-SHIFT, EFFETS VISUELS ou MÉTÉO se plient et se déplient.
  Seule la première est ouverte au départ ; le panneau retient celles que vous avez
  ouvertes.
- **La légende** en bas montre les touches valables pour la ligne choisie.

Les valeurs modifiées depuis la dernière application d'un rendu ou le dernier
enregistrement d'un profil s'affichent en vert.

![Le panneau avec la section TILT SHIFT ouverte](assets/panel-main.png){ width="480" }

## Clavier et manette

| Touche | Action |
| --- | --- |
| Flèches **Haut / Bas** | Choisir la ligne au-dessus ou en dessous |
| Flèches **Gauche / Droite** | Modifier la valeur ou l'option choisie |
| **Page préc. / Page suiv.** | Modifier la valeur par grands pas |
| **Entrée** ou **Espace** | Plier / déplier une section, exécuter une action, basculer un interrupteur ou remettre une valeur par défaut |
| **Échap** | Fermer le panneau |

Le pavé numérique fonctionne aussi panneau ouvert : **8** et **2** déplacent la sélection,
**4** et **6** modifient la valeur, **7** et **9** font de grands pas et **5** équivaut à
Entrée.

À la manette, la croix directionnelle déplace la sélection et modifie les valeurs, le bouton
de validation agit comme Entrée et le bouton retour ferme le panneau.

## Souris

- **Cliquez sur un titre de section** pour la plier ou la déplier.
- **Cliquez sur une ligne** pour la choisir. Les interrupteurs et les actions s'exécutent au
  clic.
- **Cliquez sur `<` ou `>`** à côté d'une valeur pour la modifier d'un pas. Maintenez
  **Maj** pour de grands pas.
- **Faites glisser une valeur de côté** pour la modifier en continu.
- **La molette** fait défiler la liste. Pour régler une valeur à la molette, cliquez d'abord
  sur sa ligne : une barre verte la marque et la molette ajuste désormais cette valeur.
  Cliquez à nouveau sur la ligne pour rendre la molette au défilement.
- **Cliquez sur les touches** de la légende pour Échap et Ctrl droit + J afin de fermer le
  panneau ou d'activer et désactiver tous les effets.

Au-dessus du monde, hors du panneau, la molette zoome toujours votre caméra.

## La section TILT-SHIFT

La première section regroupe les réglages les plus utilisés :

Tous les effets
:   L'interrupteur principal de tout le rendu, comme **Ctrl droit + J**. Le désactiver
    conserve tous les réglages, enregistrés ou non.

Rendu
:   Choisir un rendu prédéfini ou l'un de vos profils enregistrés. Voir
    [Rendus et profils](looks-and-profiles.md).

PROFILS ENREGISTRÉS
:   **Enregistrer les modifications**, **Enregistrer comme nouveau profil**,
    **Renommer le profil** et **Supprimer le profil**. Voir
    [Rendus et profils](looks-and-profiles.md#enregistrer-votre-propre-rendu).

EXTRAS
:   **Caméras fixes**, **Fenêtres d'aperçu** et **Timeline caméra**. Chacune apparaît dès que
    la précédente est activée. Voir [Caméras fixes](static-cameras.md),
    [Fenêtres d'aperçu](preview-windows.md) et [Timeline caméra](timeline.md).

Échelle de l'interface
:   0,75x, 1x ou 1,25x. Redimensionne ensemble le panneau et toutes les fenêtres. 1x
    correspond au HUD du jeu.

Réinitialiser tous les effets
:   Désactive chaque effet et rétablit le rendu d'origine du jeu : flou tilt-shift, flou de
    distance, stop motion, champ de vision personnalisé, vue à plat, décentrement,
    étalonnage, luminosité, netteté et distance de la caméra. Vos profils enregistrés ne
    sont pas touchés.
