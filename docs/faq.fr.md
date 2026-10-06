# Limitations et FAQ

## Limitations connues

La météo est simulée
:   La pluie du jeu ne fait pas partie de l'image sur laquelle travaille l'effet, donc le
    mod dessine sa propre pluie, sa neige et sa grêle. Je les ai rendues aussi proches que
    possible de celles du jeu, mais elles ne sont pas identiques.

Certains matériaux transparents disparaissent
:   Certains décalques, le verre et d'autres matériaux transparents ne sont pas visibles
    quand les effets sont activés. Les effets travaillent sur une copie de l'image que le
    jeu fait avant de dessiner les matériaux transparents.

Les fenêtres d'aperçu montrent le monde sans effet
:   Le rendu tilt-shift, le flou de distance et la météo n'apparaissent que dans la vue
    principale, pas dans les fenêtres d'aperçu ni dans le moniteur de la timeline.

Troisième personne uniquement
:   L'effet s'applique aux caméras orbitales. Les vues cabine, la première personne et les
    caméras fixes des véhicules ne sont pas modifiées.

## FAQ

J'ai installé le mod, mais rien ne change.
:   Les effets sont désactivés à chaque chargement d'une partie. Appuyez sur
    **Ctrl droit + J** et vérifiez que vous êtes dans une vue à la troisième personne.

Où sont les caméras fixes ?
:   Elles sont désactivées tant que vous ne les activez pas. Ouvrez le panneau et réglez
    **Caméras fixes** sur OUI dans les lignes EXTRAS. Les fenêtres d'aperçu et la timeline
    caméra s'activent de la même façon, l'une après l'autre.

Pourquoi ma vue à la première personne passe-t-elle en troisième personne ?
:   Tant qu'une caméra fixe est à l'écran, le jeu vous passe en troisième personne à pied
    pour que vous soyez visible dans le plan. **Ctrl droit + C** vous ramène à la vue en
    direct.

La touche caméra du jeu (C) ne fait rien.
:   Le mod la prend en charge tant qu'une caméra fixe est à l'écran, pour qu'elle ne vous
    sorte pas du plan. **Ctrl droit + C** vous ramène à la vue en direct.

Je ne peux pas conduire quand le panneau est ouvert.
:   Pendant que le panneau est ouvert, vos touches le pilotent. Fermez-le avec **Échap** ou
    **Ctrl droit + K**.

Comment retrouver le rendu normal du jeu ?
:   **Ctrl droit + J** désactive tous les effets en conservant vos réglages.
    **Réinitialiser tous les effets** dans le panneau désactive chaque effet et rétablit le
    rendu d'origine du jeu.

J'ai modifié des réglages puis appuyé sur une touche de profil. Mes modifications sont-elles perdues ?
:   Oui, sauf si vous les aviez enregistrées. Les touches **Ctrl droit + 1** à **9**
    appliquent le profil immédiatement. Seule la ligne Rendu du panneau demande
    confirmation avant d'abandonner des modifications non enregistrées. Voir
    [Rendus et profils](looks-and-profiles.md).

Le mod fonctionne-t-il en multijoueur ?
:   Oui. Il ne modifie que votre propre écran, et chaque joueur a ses propres caméras et sa
    propre timeline.
