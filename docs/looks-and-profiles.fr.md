# Rendus et profils

Un rendu est un ensemble complet de réglages d'effets : tout ce que contiennent les sections
d'effets du panneau, par exemple le flou, les couleurs, l'objectif et la météo. Le mod
propose cinq rendus prédéfinis, et vous pouvez enregistrer vos propres rendus sous forme de
profils.

![Le panneau avec la section TILT-SHIFT ouverte](assets/panel-main.png){ width="480" }

## Rendus prédéfinis

Robin 3e personne
:   Le rendu recommandé pour la troisième personne : le flou tilt-shift avec « Netteté suit
    le sujet », « Flou selon la distance » et le bokeh. Tous les autres effets sont
    désactivés.

Miniature
:   Le flou de distance du jeu sur l'arrière-plan et un étalonnage marqué.

Miniature + stop motion
:   Miniature à 15 images par seconde.

Subtil
:   Un flou de distance et un étalonnage plus légers.

Tout désactiver
:   Désactive tous les effets, comme **Réinitialiser tous les effets**.

Miniature, Miniature + stop motion et Subtil ne modifient ni le flou tilt-shift ni les
réglages météo. Vous ne pouvez pas modifier un rendu prédéfini, mais vous pouvez changer
ses réglages et enregistrer le résultat comme profil.

## Choisir un rendu

La ligne Rendu, en haut de la section TILT-SHIFT, affiche le rendu actuel. Sa liste
commence par les rendus prédéfinis, suivis de vos profils enregistrés.

Gauche et Droite (ou un clic sur `<` et `>` à côté de la valeur) parcourent la liste. Seuls
les noms changent : l'image ne change que lorsque vous appuyez sur Entrée ou cliquez sur la
ligne, ce qui applique le rendu et active les effets. Si vous passez à une autre ligne sans
appliquer, la ligne Rendu affiche de nouveau le rendu actuel.

Les profils enregistrés qui ont un raccourci affichent leur numéro devant leur nom, par
exemple **2 · Moisson**.

Dès que vous modifiez un réglage, la ligne Rendu ajoute « (modifié) », par exemple
**2 · Moisson (modifié)**, et les valeurs modifiées passent en vert et reçoivent un
astérisque. Si vous appliquez ensuite un autre rendu, le jeu demande d'abord « Abandonner
les modifications non enregistrées et appliquer … ? ». Choisissez **Appliquer** pour
continuer ou **Annuler** pour garder vos modifications. Si vous fermez plutôt le panneau, il
demande « Enregistrer vos modifications du profil … avant de fermer ? » : **Enregistrer**
les écrit dans le profil, **Ne pas enregistrer** ferme le panneau et les garde à l'écran
comme modifications non enregistrées.

Si les réglages actuels ne correspondent à aucun rendu de la liste, par exemple parce que
vous avez supprimé le profil dont ils venaient, la ligne Rendu affiche **Personnalisé**.

## Enregistrer votre propre rendu

Les lignes PROFILS ENREGISTRÉS, sous la ligne Rendu, s'appliquent au profil actuellement
appliqué. Les lignes inutilisables pour le moment sont grisées.

Enregistrer les modifications
:   Enregistre vos modifications dans le profil actuel. Le nom du profil est affiché à
    droite de la ligne. Disponible uniquement lorsqu'un profil enregistré est appliqué et
    que vous avez modifié quelque chose.

Enregistrer comme nouveau profil
:   Enregistre les réglages actuels dans un nouveau profil, nommé Profil 1, Profil 2 et
    ainsi de suite, qui devient le rendu actuel.

Renommer le profil
:   Ouvre la zone de saisie du jeu pour renommer le profil actuel. Un nom peut compter
    jusqu'à 32 caractères. Les caractères interdits dans les noms de fichier
    (`\ / : * ? " < > |`) sont supprimés, et vous ne pouvez pas reprendre le nom d'un autre
    profil.

Supprimer le profil
:   Supprime le profil actuel après confirmation. Les réglages à l'écran ne changent pas, et
    la ligne Rendu affiche **Personnalisé**.

Pour modifier un profil qui n'est pas le profil actuel, appliquez-le d'abord dans la ligne
Rendu.

Au premier lancement après l'installation, le mod enregistre ses réglages par défaut sous
le nom **Profil 1**, sur le raccourci 1.

## Raccourcis clavier

**Ctrl droit + 1** à **Ctrl droit + 9** appliquent vos profils enregistrés immédiatement,
sans poser de question sur les modifications non enregistrées, et activent les effets. Une
nouvelle pression sur le même chiffre désactive les effets.

Chaque profil garde son numéro jusqu'à sa suppression. Un nouveau profil reçoit le plus
petit numéro libre, et renommer un profil ne change pas son numéro. Au-delà de neuf
profils, les suivants n'ont pas de raccourci mais restent dans la liste de la ligne Rendu.

## La ligne sous le titre

La ligne sous le titre du panneau indique à quoi s'appliquent actuellement les réglages des
effets et de quel rendu ils proviennent :

| La ligne indique | Signification |
| --- | --- |
| Modification : vue en direct | Votre propre vue, sans profil enregistré ni rendu prédéfini |
| Modification : vue en direct, profil Moisson | Votre propre vue, à partir d'un profil enregistré |
| Modification : vue en direct, rendu prédéfini Miniature | Votre propre vue, à partir d'un rendu prédéfini |
| Modification : Caméra 1, son propre rendu | Une caméra fixe avec ses propres réglages |
| Modification : Caméra 1, utilise le profil Moisson | Une caméra fixe qui utilise un profil enregistré |

## Caméras fixes et profils

Chaque [caméra fixe](static-cameras.md) a son propre réglage Rendu. Il vaut soit
**Propres**, et la caméra a alors ses propres réglages, soit l'un de vos profils
enregistrés.

Avec **Propres**, toute modification faite en regardant à travers la caméra est
enregistrée avec elle. Elle ne compte donc jamais comme une modification non enregistrée.

Avec un profil, regarder à travers la caméra applique ce profil. Vos modifications
s'affichent comme « (modifié) », et **Enregistrer les modifications** les enregistre dans
le profil, ce qui met aussi à jour toutes les autres caméras qui l'utilisent. Si vous
changez de vue sans enregistrer, les modifications sont perdues.

Si vous appliquez un rendu en regardant à travers une caméra :

- un profil enregistré, sur une caméra qui utilise un profil : la caméra passe au nouveau
  profil ;
- un profil enregistré, sur une caméra qui a ses propres réglages : les réglages du profil
  sont copiés dans la caméra ;
- un rendu prédéfini, sur n'importe quelle caméra : la caméra reprend ce rendu comme ses
  propres réglages.

Renommer un profil le renomme pour toutes les caméras qui l'utilisent. Supprimer un profil
laisse ses réglages à ces caméras, qui les gardent comme leurs propres réglages.

## Après un redémarrage

Le mod mémorise le rendu actuel quand vous quittez. Si vous avez modifié un profil
enregistré sans l'enregistrer, la ligne Rendu affiche toujours « (modifié) » à la partie
suivante.
