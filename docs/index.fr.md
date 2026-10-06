# Caméra Tilt Shift

Transformez votre ferme en miniature vivante. Caméra Tilt Shift ajoute aux vues à la
troisième personne de Farming Simulator 25 un effet tilt-shift réglable en direct : une
bande nette en travers de l'écran qui suit la cible de votre caméra, un flou doux au-dessus
et en dessous qui augmente avec la profondeur, des points lumineux qui s'épanouissent en
disques de bokeh, et un étalonnage qui donne à tout l'air d'une maquette peinte.

Autour de l'effet, vous disposez de réglages d'objectif supplémentaires (champ de vision,
vue à plat sans perspective, décentrement, distance de caméra étendue), du flou de distance
et de l'étalonnage du jeu, d'une limite d'images façon stop motion, ainsi que de pluie,
neige et grêle qui se floutent avec la miniature et peuvent suivre le ciel réel.
Enregistrez les rendus qui vous plaisent comme profils et passez de l'un à l'autre d'une
touche.

Pour aller plus loin, trois extras sont à portée d'interrupteur :
des [caméras fixes](static-cameras.md) à poser autour de la ferme, des
[fenêtres d'aperçu](preview-windows.md) qui montrent chaque caméra en direct, et une
[timeline caméra](timeline.md) qui alterne toute seule entre elles, pensée pour les
timelapses de vos ouvriers aux champs.

## Démarrage rapide

1. **Installez le mod.** Copiez `FS25_TiltShift.zip` dans votre dossier de mods
   (`Documents/My Games/FarmingSimulator2025/mods`) ou téléchargez-le depuis le ModHub dans
   le jeu. Activez-le pour votre partie comme d'habitude.
2. **Passez à une vue à la troisième personne.** L'effet ne s'applique qu'aux caméras
   orbitales : à pied à la troisième personne, ou la caméra extérieure d'un véhicule.
3. **Appuyez sur Ctrl droit + J** pour activer les effets. Ils sont désactivés à chaque
   chargement d'une partie, pour que le rendu ne vous surprenne jamais ; vos réglages sont
   conservés.
4. **Appuyez sur Ctrl droit + K** pour ouvrir le panneau et régler le rendu. Voir
   [Le panneau](panel.md) pour s'y déplacer, [Rendus et profils](looks-and-profiles.md) pour
   les rendus prêts à l'emploi et vos propres profils, et [Effets](effects.md) pour le rôle
   de chaque réglage.

<!-- screenshot: une scène de ferme avec le rendu tilt-shift (docs/assets/) -->

!!! tip "Où l'effet s'applique"
    Les vues cabine, la première personne et les caméras fixes des véhicules restent
    intactes. L'effet fonctionne aussi avec les caméras libres et cinématiques d'autres
    mods, car il suit la caméra active. La boutique, l'atelier, le mode construction et
    l'écran de sommeil affichent toujours le jeu normal.

## Extras

Les caméras fixes, les fenêtres d'aperçu et la timeline caméra sont désactivées jusqu'à ce
que vous les activiez dans les lignes **EXTRAS** de la section **TILT-SHIFT** du panneau.
Elles s'appuient l'une sur l'autre : chaque interrupteur apparaît dès que le précédent est
activé.

1. **Caméras fixes**
2. **Fenêtres d'aperçu** (nécessite les caméras fixes)
3. **Timeline caméra** (nécessite les fenêtres d'aperçu)

## Multijoueur

Le mod fonctionne en multijoueur. Tout ce qu'il fait reste local à votre écran, et chaque
joueur garde ses propres caméras et sa propre timeline.
