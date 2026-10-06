# Rendus et profils

Un rendu est un ensemble complet de réglages d'effets : tout ce que contiennent les sections
d'effets du panneau, du flou tilt-shift aux couleurs, à l'objectif et à la météo. Le mod
fournit quelques rendus prédéfinis, et vous pouvez enregistrer les vôtres sous forme de
profils.

![Le panneau avec la section TILT SHIFT ouverte](assets/panel-main.png){ width="480" }

## Rendus prédéfinis

Robin 3e personne
:   Le rendu tilt-shift déjà réglé : flou tilt-shift avec Netteté suit le sujet,
    flou selon la distance et bokeh. Il désactive d'abord tous les autres effets.

Miniature
:   Flou de distance sur l'arrière-plan et un étalonnage marqué.

Miniature + stop motion
:   Miniature à 15 images par seconde.

Subtil
:   Un flou de distance et un étalonnage plus légers.

Tout désactiver
:   Désactive tous les effets, comme **Réinitialiser tous les effets**.

Miniature, Miniature + stop motion et Subtil laissent le flou tilt-shift et la météo tels
qu'ils étaient. Un rendu prédéfini ne peut pas être modifié, mais vous pouvez enregistrer le
résultat comme profil.

## Choisir un rendu

La ligne Rendu, en haut de la section TILT-SHIFT, affiche le rendu à l'écran. Sa liste
commence par les rendus prédéfinis, suivis de vos profils enregistrés.

Gauche et Droite (ou le `<` et le `>` à côté de la valeur) parcourent la liste sans rien
changer à l'écran. Entrée, ou un clic sur la ligne, applique le rendu sur lequel vous vous
êtes arrêté ; appliquer un rendu active aussi les effets. Si vous passez à une autre ligne
sans appliquer, la ligne Rendu affiche de nouveau le rendu à l'écran.

Un profil enregistré qui a un raccourci affiche son numéro devant son nom, par exemple
**2 · Moisson**.

Dès que vous modifiez un réglage, la ligne Rendu ajoute « (modifié) », comme dans
**2 · Moisson (modifié)**, et les valeurs modifiées passent en vert. Si vous appliquez
ensuite un autre rendu, le jeu demande d'abord « Abandonner les modifications non
enregistrées et appliquer … ? ». **Appliquer** continue, **Annuler** garde vos
modifications.

La ligne affiche **Personnalisé** quand l'image à l'écran ne correspond à aucun rendu de la
liste, par exemple après la suppression du profil dont elle venait.

## Enregistrer votre propre rendu

Les lignes PROFILS ENREGISTRÉS, sous la ligne Rendu, agissent sur le profil enregistré qui
est à l'écran. Une ligne qui ne peut rien faire pour le moment est grisée.

Enregistrer les modifications
:   Enregistre vos modifications dans le profil à l'écran, dont le nom s'affiche à droite de
    la ligne. Elle ne fonctionne que si un profil enregistré est à l'écran et a été modifié.

Enregistrer comme nouveau profil
:   Enregistre aussitôt l'image actuelle comme nouveau profil, nommé Profil 1, Profil 2, et
    ainsi de suite. Le nouveau profil devient le rendu à l'écran.

Renommer le profil
:   Ouvre la zone de texte du jeu pour donner au profil à l'écran un nouveau nom de 32
    caractères au plus. Les caractères interdits dans un nom de fichier
    (`\ / : * ? " < > |`) sont retirés, et un nom déjà pris par un autre profil est refusé.

Supprimer le profil
:   Supprime le profil à l'écran après confirmation. L'image ne change pas ; la ligne Rendu
    l'affiche simplement comme **Personnalisé**.

Pour modifier un profil qui n'est pas à l'écran, appliquez-le d'abord dans la ligne Rendu.

Lors d'une première installation, le mod enregistre son rendu par défaut sous le nom
**Profile 1**, sur le raccourci 1.

## Raccourcis clavier

**Ctrl droit + 1** à **Ctrl droit + 9** appliquent vos profils enregistrés immédiatement,
sans demander, et activent les effets. Appuyer de nouveau sur le même chiffre désactive les
effets.

Un profil garde son numéro tant qu'il existe. Un nouveau profil prend le plus petit numéro
libre, la suppression d'un profil libère son numéro, et le renommer ne le change pas. Au-delà
de neuf profils, les suivants n'ont pas de raccourci mais restent dans la ligne Rendu.

## La ligne sous le titre

La ligne sous le titre du panneau indique ce que modifient les lignes d'effets et d'où vient
le rendu :

| La ligne indique | Signification |
| --- | --- |
| Modification : vue en direct | Votre propre vue, sans profil enregistré ni rendu prédéfini derrière |
| Modification : vue en direct, profil Moisson | Votre propre vue, issue d'un profil enregistré |
| Modification : vue en direct, rendu prédéfini Miniature | Votre propre vue, issue d'un rendu prédéfini |
| Modification : Caméra 1, son propre rendu | Une caméra fixe avec son propre rendu |
| Modification : Caméra 1, utilise le profil Moisson | Une caméra fixe qui utilise un profil enregistré |

## Caméras fixes et profils

Une [caméra fixe](static-cameras.md) a sa propre ligne Rendu, réglée soit sur **Propres**
(la caméra garde ses propres réglages), soit sur l'un de vos profils enregistrés.

Avec **Propres**, tout ce que vous modifiez en regardant par la caméra est enregistré avec
elle, et ne compte donc jamais comme une modification non enregistrée.

Avec un profil, regarder par la caméra applique ce profil. Les modifications faites à ce
moment s'affichent comme « (modifié) », et **Enregistrer les modifications** les écrit dans
le profil, ce qui met à jour toutes les caméras qui l'utilisent. Ce que vous n'enregistrez
pas est perdu quand vous passez à une autre vue.

Appliquer un rendu en regardant par une caméra se passe ainsi :

- Un autre profil enregistré, sur une caméra qui utilise un profil : la caméra utilise
  désormais ce profil.
- Un profil enregistré, sur une caméra avec son propre rendu : les réglages du profil sont
  copiés dans le rendu propre de la caméra.
- Un rendu prédéfini, sur n'importe quelle caméra : la caméra reçoit ce rendu comme le sien.

Renommer un profil le renomme pour toutes les caméras qui l'utilisent. Supprimer un profil
laisse son rendu à ces caméras, comme leur rendu propre.

## Après un redémarrage

Le mod retient le rendu qui était à l'écran. Si vous aviez modifié un profil enregistré sans
l'enregistrer, la ligne Rendu affiche toujours « (modifié) » la fois suivante.
