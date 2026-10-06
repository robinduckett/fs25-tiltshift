# Caméras fixes

Une caméra fixe reste à un point précis du monde. Vous pouvez en placer plusieurs, par
exemple autour d'un champ, et passer de l'une à l'autre tout en continuant à jouer. Le jeu
n'est pas mis en pause quand vous regardez à travers une caméra fixe.

!!! info "Activez-les d'abord"
    Ouvrez le panneau (**Ctrl droit + K**) et réglez **Caméras fixes** sur OUI dans les
    lignes EXTRAS. La section CAMÉRAS FIXES apparaît alors dans le panneau.

![La section CAMÉRAS FIXES](assets/panel-cameras.png){ width="480" }

![Une caméra fixe sur la carte du menu pause, avec Passer à la caméra et Supprimer la caméra](assets/map-marker.jpg)

## Ajouter et changer de caméra

| Touche | Action |
| --- | --- |
| **Ctrl droit + N** | Ajouter une caméra à votre vue actuelle |
| **Ctrl droit + C** | Passer à la dernière caméra fixe utilisée, ou revenir à la vue directe |
| **Ctrl droit + V** | Passer à la caméra fixe suivante |

Les nouvelles caméras s'appellent Caméra 1, Caméra 2 et ainsi de suite. Quand vous changez
de caméra, un message en haut de l'écran indique à travers quelle caméra vous regardez.

Tant que vous regardez à travers une caméra fixe :

- si vous êtes à pied, le jeu vous passe à la troisième personne pour que votre personnage
  soit visible ;
- la touche caméra du jeu (**C**) est sans effet jusqu'à votre retour à la vue directe,
  afin qu'elle ne vous fasse pas quitter la caméra fixe par erreur ;
- monter dans un véhicule ou en descendre ne change pas la vue ;
- les menus, l'écran de sommeil et les mods de caméra cinématique prennent la main sur
  l'écran comme d'habitude.

## La section CAMÉRAS FIXES

Vue
:   Ce qui est affiché : **Directe** (votre propre vue) ou l'une de vos caméras. Gauche et
    Droite permettent de changer.

Ajouter une caméra ici
:   Ajoute une caméra à votre vue actuelle, comme **Ctrl droit + N**.

Modifier la caméra
:   Choisit la caméra que modifient les lignes en dessous. Le titre au-dessus de la ligne
    affiche le nom de cette caméra. Appuyez sur **Entrée** pour regarder à travers elle.

Rendu
:   **Propres**, si la caméra a ses propres réglages d'effets, ou l'un de vos profils
    enregistrés. Une nouvelle caméra part d'une copie des réglages que vous aviez en
    l'ajoutant. Avec **Propres**, toute modification faite en regardant à travers la
    caméra est enregistrée avec elle. Pour les caméras qui utilisent un profil, voir
    [Rendus et profils](looks-and-profiles.md#cameras-fixes-et-profils).

Déplacer à ma vue
:   Déplace la caméra à votre vue actuelle. Ses réglages d'effets ne changent pas.

Fenêtre d'aperçu
:   Affiche ou masque la [fenêtre d'aperçu](preview-windows.md) de cette caméra.

Placer en vol libre
:   Permet de déplacer la caméra vous-même en vol libre. Voir plus bas.

POSITION ET VISÉE
:   Règle précisément la position et l'orientation de la caméra. Position X, Hauteur et
    Position Z la déplacent par pas de 0,25 m, ou de 2 m avec Page préc. et Page suiv.
    Rotation, Inclinaison et Roulis la font tourner par pas de 1 degré, ou de 10 degrés
    avec Page préc. et Page suiv. Le champ de vision se règle de 5 à 150 degrés.

Supprimer la caméra
:   Supprime la caméra après confirmation dans la boîte de dialogue Oui/Non du jeu.

## Placer une caméra en vol libre

Choisissez **Placer en vol libre** dans le panneau, ou cliquez sur le bouton de vol de la
fenêtre d'aperçu de la caméra. Le panneau se ferme et vous regardez à travers la caméra.
Vos touches de déplacement (**Z Q S D**) déplacent la caméra et la souris la fait tourner.
Maintenez **Maj** pour aller plus vite. **Entrée** enregistre la nouvelle position ;
**Échap** annule et remet la caméra à son ancienne place.

Ensuite, le panneau se rouvre et vous regardez toujours à travers la caméra.

## Sur la carte

Chaque caméra fixe apparaît sur la carte du menu pause et sur la mini-carte. Sélectionnez
une caméra sur la carte du menu pause pour afficher deux options supplémentaires :
**Passer à la caméra** pour regarder à travers elle, et **Supprimer la caméra** pour la
supprimer (après confirmation).

## Sauvegarde

Les caméras font partie de votre partie et sont sauvegardées lorsque vous sauvegardez le
jeu. En multijoueur, chaque joueur a ses propres caméras.

Si vous réglez **Caméras fixes** sur NON dans le panneau, les caméras et tout ce qui s'y
rapporte sont masqués et vous revenez à la vue directe. Vos caméras ne sont pas supprimées :
elles réapparaissent dès que vous réactivez Caméras fixes.
