# Limitations et FAQ

## Limitations connues

La pluie, la neige et la grêle sont simulées
:   La pluie du jeu ne fait pas partie de l'image sur laquelle travaille l'effet. Le mod
    dessine donc sa propre pluie, sa propre neige et sa propre grêle. Je les ai rendues
    aussi proches que possible de la météo du jeu, mais elles ne sont pas tout à fait
    identiques.

Certains matériaux transparents sont masqués
:   Certains autocollants, le verre et d'autres matériaux transparents ne sont pas visibles
    quand le flou tilt-shift est activé. Cela vient du fait que le flou travaille sur une
    copie de l'image que le jeu crée avant de dessiner les matériaux transparents.

Les fenêtres d'aperçu montrent l'image sans effets
:   Le flou tilt-shift, le flou de distance et les effets météo n'apparaissent que dans la
    vue principale, pas dans les fenêtres d'aperçu ni dans le moniteur de la timeline.

Troisième personne uniquement
:   L'effet ne s'applique qu'aux caméras à la troisième personne. Les vues cabine, la
    première personne et les caméras de véhicule non orientables ne sont pas concernées.

## FAQ

J'ai installé le mod, mais rien ne change.
:   Les effets sont toujours désactivés au chargement d'une partie. Appuyez sur
    **Ctrl droit + J** et vérifiez que vous êtes dans une vue à la troisième personne.

Où sont les caméras fixes ?
:   Elles sont désactivées tant que vous ne les activez pas. Ouvrez le panneau et réglez
    **Caméras fixes** sur OUI dans les lignes EXTRAS. Les fenêtres d'aperçu et la timeline
    caméra s'activent au même endroit, l'une après l'autre.

Pourquoi ma vue est-elle passée de la première à la troisième personne ?
:   Tant que vous regardez à travers une caméra fixe, le mod vous passe à la troisième
    personne à pied pour que votre personnage soit visible, et vous ramène à la première
    personne quand vous revenez à la vue directe. Appuyez sur **Ctrl droit + C** pour
    revenir à la vue directe.

La touche caméra du jeu (C) ne fait rien.
:   Elle est désactivée tant que vous regardez à travers une caméra fixe, pour ne pas vous
    faire quitter la caméra par erreur. Appuyez sur **Ctrl droit + C** pour revenir à la
    vue directe.

Je regarde à travers une caméra et la souris ne fait pas bouger la vue.
:   Une caméra fixe reste là où vous l'avez placée : la souris et les touches font toujours
    bouger votre personnage ou votre véhicule, que vous ne voyez peut-être pas depuis la
    caméra. La barre en bas de l'écran indique comment revenir : **Ctrl droit + C** pour
    votre propre vue. Si vous avez choisi la caméra sur la carte, appuyez sur **Échap**.
    Fermer le panneau vous ramène toujours à la vue depuis laquelle vous l'avez ouvert.

Comment masquer le HUD pour filmer ?
:   Le jeu lui-même n'a pas de touche pour masquer tout le HUD. Lancer la timeline masque
    pour vous le HUD, le panneau et toutes les fenêtres, épinglées comprises. Passer à la
    caméra sur la carte du menu pause masque le HUD, mais les fenêtres d'aperçu épinglées
    restent à l'écran. Quand vous regardez à travers une caméra avec **Ctrl droit + C** ou
    **Ctrl droit + V**, le HUD reste à l'écran, et avec lui la barre de touches en bas, qui
    fait partie du HUD.

Je ne peux pas conduire quand le panneau est ouvert.
:   Tant que le panneau est ouvert, vos touches commandent le panneau. Fermez-le avec
    **Échap** ou **Ctrl droit + K**.

Comment retrouver l'aspect normal du jeu ?
:   **Ctrl droit + J** désactive tous les effets en conservant vos réglages.
    **Réinitialiser tous les effets** dans le panneau désactive tous les effets et rétablit
    l'aspect normal du jeu.

J'ai modifié des réglages puis appuyé sur une touche de profil. Mes modifications sont-elles perdues ?
:   Oui, si vous ne les avez pas enregistrées avant. **Ctrl droit + 1** à **9** appliquent
    le profil immédiatement. Seule la ligne Rendu du panneau demande confirmation avant
    d'abandonner des modifications non enregistrées. Voir
    [Rendus et profils](looks-and-profiles.md).

Le mod enregistre-t-il des vidéos ?
:   Non. Il prépare l'image : le rendu, les caméras et la timeline. Enregistrez avec votre
    logiciel d'enregistrement d'écran habituel. Tout ce que fait le mod est dessiné en
    direct dans le jeu : l'enregistrement est l'image finale.

J'ai copié ma sauvegarde et les caméras ont disparu.
:   Les caméras sont rangées dans le dossier de réglages du mod
    (`Documents/My Games/FarmingSimulator2025/modSettings/FS25_TiltShift`) et liées à
    l'emplacement, à la carte et à la date de création de la partie où vous les avez créées,
    pas au dossier de la sauvegarde. Pour changer de PC, copiez aussi ce dossier. Une
    sauvegarde copiée vers un autre emplacement démarre sans caméras.

Le mod fonctionne-t-il en multijoueur ?
:   Oui. Il ne modifie que l'image sur votre propre écran, et chaque joueur a ses propres
    caméras et sa propre timeline.

Où signaler un problème ?
:   Via [Signaler un problème](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose).
    Joignez si possible votre `log.txt`, qui se trouve dans
    `Documents/My Games/FarmingSimulator2025`.
