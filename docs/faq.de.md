# Einschränkungen und FAQ

## Bekannte Einschränkungen

Regen, Schnee und Hagel sind nachgebildet
:   Der Regen des Spiels ist nicht Teil des Bildes, auf das der Effekt wirkt. Deshalb
    zeichnet die Mod eigenen Regen, Schnee und Hagel. Ich habe sie dem Wetter im Spiel so
    weit wie möglich angeglichen, aber sie sehen nicht genau gleich aus.

Manche transparenten Materialien sind ausgeblendet
:   Einige Decals, Glas und andere transparente Materialien sind nicht sichtbar, solange die
    Tilt-Shift-Unschärfe an ist. Das liegt daran, dass die Unschärfe auf einer Kopie des
    Bildes arbeitet, die das Spiel anlegt, bevor es transparente Materialien zeichnet.

Vorschaufenster zeigen das Bild ohne Effekte
:   Tilt-Shift-Unschärfe, Entfernungsunschärfe und Wettereffekte sind nur in der
    Hauptansicht zu sehen, nicht in den Vorschaufenstern oder im Monitor der Zeitleiste.

Nur dritte Person
:   Der Effekt wirkt nur bei Third-Person-Kameras. Kabinenansichten, die Ego-Perspektive
    und feste Fahrzeugkameras sind nicht betroffen.

## FAQ

Ich habe die Mod installiert, aber nichts ändert sich.
:   Beim Laden eines Spielstands sind die Effekte immer ausgeschaltet. Drücke
    **Rechts-Strg + J** und achte darauf, dass du in einer Third-Person-Ansicht bist.

Wo sind die statischen Kameras?
:   Sie sind ausgeschaltet, bis du sie einschaltest. Öffne das Panel und stelle
    **Statische Kameras** in den EXTRAS-Zeilen auf AN. Vorschaufenster und
    Kamera-Zeitleiste schaltest du an derselben Stelle ein, eines nach dem anderen.

Warum hat meine Ansicht von der Ego-Perspektive in die dritte Person gewechselt?
:   Solange du durch eine statische Kamera schaust, schaltet die Mod dich zu Fuß in die
    dritte Person, damit deine Spielfigur zu sehen ist, und zurück in die Ego-Perspektive,
    wenn du zur Live-Ansicht zurückkehrst. Mit **Rechts-Strg + C** kehrst du zur
    Live-Ansicht zurück.

Die Kamerataste des Spiels (C) funktioniert nicht.
:   Sie ist deaktiviert, solange du durch eine statische Kamera schaust, damit sie dich
    nicht versehentlich wegschaltet. Mit **Rechts-Strg + C** kehrst du zur Live-Ansicht
    zurück.

Ich schaue durch eine Kamera, und die Maus bewegt die Ansicht nicht.
:   Eine statische Kamera bleibt, wo du sie hingestellt hast: Maus und Tasten bewegen
    weiterhin deine Spielfigur oder dein Fahrzeug, die du von der Kamera aus vielleicht nicht
    siehst. Die Leiste unten am Bildschirm zeigt den Weg zurück: **Rechts-Strg + C** für
    deine eigene Ansicht. Hast du die Kamera auf der Karte gewählt, drücke **Esc**. Schließt
    du das Panel, kehrst du immer zu der Ansicht zurück, von der aus du es geöffnet hast.

Wie blende ich das HUD zum Filmen aus?
:   Das Spiel selbst hat keine Taste, um das ganze HUD auszublenden. Zeitleiste starten
    blendet HUD, Panel und alle Fenster für dich aus, auch angeheftete. Zur Kamera wechseln
    auf der Karte im Pausenmenü blendet das HUD aus, angeheftete Vorschaufenster bleiben
    aber auf dem Bildschirm. Schaust du mit **Rechts-Strg + C** oder **Rechts-Strg + V**
    durch eine Kamera, bleibt das HUD auf dem Bildschirm, und mit ihm die Tastenleiste
    unten, die zum HUD gehört.

Ich kann nicht fahren, während das Panel offen ist.
:   Solange das Panel offen ist, steuern deine Tasten das Panel. Schließe es mit **Esc**
    oder **Rechts-Strg + K**.

Wie bekomme ich das normale Aussehen des Spiels zurück?
:   **Rechts-Strg + J** schaltet alle Effekte aus und behält deine Einstellungen.
    **Alle Effekte zurücksetzen** im Panel schaltet alle Effekte aus und stellt das normale
    Aussehen des Spiels wieder her.

Ich habe Einstellungen geändert und dann eine Profiltaste gedrückt. Sind meine Änderungen weg?
:   Ja, wenn du sie nicht vorher gespeichert hast. **Rechts-Strg + 1** bis **9** wenden das
    Profil sofort an. Nur die Zeile Look im Panel fragt nach, bevor ungespeicherte
    Änderungen verworfen werden. Siehe [Looks und Profile](looks-and-profiles.md).

Nimmt die Mod Videos auf?
:   Nein. Sie richtet das Bild ein: den Look, die Kameras und die Zeitleiste. Aufgenommen
    wird mit deiner gewohnten Aufnahmesoftware. Alles, was die Mod macht, wird live im Spiel
    gezeichnet, die Aufnahme ist also das fertige Bild.

Ich habe meinen Spielstand kopiert, und die Kameras sind weg.
:   Kameras liegen im eigenen Einstellungsordner der Mod
    (`Dokumente/My Games/FarmingSimulator2025/modSettings/FS25_TiltShift`) und sind an Slot,
    Karte und Startdatum des Spielstands gebunden, in dem du sie angelegt hast, nicht an den
    Ordner des Spielstands. Beim Umzug auf einen anderen PC kopiere auch diesen Ordner. Ein
    in einen anderen Slot kopierter Spielstand startet ohne Kameras.

Funktioniert die Mod im Mehrspielermodus?
:   Ja. Sie verändert nur das Bild auf deinem eigenen Bildschirm, und jeder Spieler hat
    seine eigenen Kameras und seine eigene Zeitleiste.

Wo melde ich ein Problem?
:   Über [Problem melden](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose).
    Bitte hänge deine `log.txt` aus `Dokumente/My Games/FarmingSimulator2025` an.
