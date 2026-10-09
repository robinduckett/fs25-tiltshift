# Prise en main

Caméra Tilt Shift sert à filmer votre ferme. Le mod donne aux vues à la troisième personne
de Farming Simulator 25 l'aspect d'une photographie tilt-shift : une bande horizontale reste
nette et tout ce qui se trouve au-dessus et au-dessous devient flou, ce qui donne à la scène
l'aspect d'une maquette. Par défaut, la bande nette suit le sujet autour duquel tourne votre
caméra : votre tracteur ou votre personnage reste net.

En plus du flou, vous pouvez afficher un bokeh sur les points lumineux, augmenter la
saturation et le contraste et assombrir les coins de l'image. Le panneau propose aussi des
réglages d'objectif (champ de vision, une vue sans perspective, le décentrement et une
distance de caméra plus grande), le flou de distance et l'étalonnage du jeu, ainsi qu'une
limite d'images pour un rendu stop motion. Le mod peut également afficher sa propre pluie,
sa propre neige et sa propre grêle, qui suivent la météo du jeu et deviennent floues avec
le reste de l'image. Vous pouvez enregistrer un rendu qui vous plaît comme profil et le
rappeler avec un raccourci clavier.

Trois extras facultatifs sont désactivés au départ : des [caméras fixes](static-cameras.md)
que vous placez sur la carte, des [fenêtres d'aperçu](preview-windows.md) qui montrent ce
que voit chaque caméra, et une [timeline caméra](timeline.md) qui passe d'une caméra à
l'autre toute seule, par exemple pour filmer un timelapse de vos ouvriers aux champs.

Tout est dessiné en direct dans le jeu : ce que votre enregistreur d'écran capture est
l'image finale. Le mod n'enregistre rien lui-même : utilisez le logiciel d'enregistrement
que vous avez déjà. Voir [Filmer](#filmer) plus bas.

## Démarrage rapide

1. Installez le mod. Copiez `FS25_TiltShift.zip` dans votre dossier de mods
   (`Documents/My Games/FarmingSimulator2025/mods`) ou téléchargez-le depuis le ModHub dans
   le jeu. Activez-le ensuite pour votre partie.
2. Passez à une vue à la troisième personne : à pied à la troisième personne, ou la caméra
   extérieure d'un véhicule. L'effet ne s'applique pas aux autres vues.
3. Appuyez sur **Ctrl droit + J** pour activer les effets. Ils sont toujours désactivés au
   chargement d'une partie, mais vos réglages sont conservés.
4. Appuyez sur **Ctrl droit + K** pour ouvrir le panneau. [Le panneau](panel.md) explique
   comment l'utiliser, [Rendus et profils](looks-and-profiles.md) présente les rendus
   prédéfinis et l'enregistrement de vos propres rendus, et [Effets](effects.md) décrit
   chaque réglage.

![Une cour de ferme vue d'une caméra fixe en hauteur, avec le rendu miniature tilt-shift](assets/hero.jpg)

!!! tip "Où l'effet s'applique"
    L'effet ne s'applique pas aux vues cabine, à la première personne ni aux caméras de
    véhicule non orientables. Il s'applique en revanche aux caméras libres et cinématiques d'autres
    mods, car il suit toujours la caméra active. La boutique, l'atelier, le mode
    construction et la garde-robe affichent toujours le jeu sans l'effet.

## Extras

Les caméras fixes, les fenêtres d'aperçu et la timeline caméra restent désactivées tant que
vous ne les activez pas dans les lignes EXTRAS de la section TILT-SHIFT du panneau. Chaque
extra nécessite le précédent : sa ligne n'apparaît donc qu'une fois le précédent activé.

1. **Caméras fixes**
2. **Fenêtres d'aperçu**, une fois Caméras fixes activé
3. **Timeline caméra**, une fois Fenêtres d'aperçu activé

## Filmer

Le mod prépare l'image ; votre logiciel d'enregistrement d'écran la capture. Quelques points
à connaître avant d'enregistrer :

- **Le rendu est dans le jeu.** Le flou tilt-shift, la météo et les couleurs sont calculés en
  direct : l'enregistrement n'a pas besoin de montage ensuite. **Ctrl droit + 1** à **9**
  changent de profil pendant l'enregistrement.
- **Votre propre travail vu de côté.** Placez une [caméra fixe](static-cameras.md) au bord du
  champ et appuyez sur **Ctrl droit + C** : vous continuez à conduire pendant que la caméra
  vous filme. Le jeu n'est pas mis en pause.
- **Timelapses et vidéos à plusieurs caméras.** Composez une [timeline caméra](timeline.md)
  et appuyez sur **Ctrl droit + T**. Le panneau, toutes les fenêtres et le HUD disparaissent,
  un compte à rebours défile, puis la timeline passe d'une caméra à l'autre sans aucun
  message à l'écran. Lancez l'enregistrement une fois le compte à rebours terminé.
- **Le HUD.** Le jeu lui-même n'a pas de touche pour masquer tout le HUD. La timeline et
  Passer à la caméra sur la carte le masquent pour vous ; quand vous regardez à travers une
  caméra avec **Ctrl droit + C**, le HUD reste à l'écran, et la barre de touches du mod en
  bas de l'écran aussi.

## Multijoueur

Le mod fonctionne en multijoueur. Il ne modifie que l'image sur votre propre écran, et
chaque joueur a ses propres caméras et sa propre timeline.
