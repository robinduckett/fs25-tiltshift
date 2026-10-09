# Kamera-Zeitleiste

Die Kamera-Zeitleiste wechselt automatisch zwischen deinen statischen Kameras. Du legst
eine Liste von Clips an, die jeweils eine Kamera für eine bestimmte Zahl von Sekunden
zeigen, und startest dann die Zeitleiste. Das eignet sich zum Beispiel, um einen
Zeitraffer aufzunehmen, während deine Helfer die Feldarbeit erledigen, oder für ein Video,
das zwischen mehreren Blickwinkeln auf den Hof schneidet.

!!! info "Zuerst einschalten"
    Die Zeitleiste setzt [statische Kameras](static-cameras.md) und
    [Vorschaufenster](preview-windows.md) voraus. Wenn beide an sind, stelle
    **Kamera-Zeitleiste** in den EXTRAS-Zeilen des Panels auf AN. Danach erscheinen der
    Abschnitt KAMERA-ZEITLEISTE und das Editor-Fenster.

![Das Editor-Fenster der Kamera-Zeitleiste mit einem Vorschaufenster](assets/timeline-editor.jpg)

## Das Editor-Fenster

Das Fenster KAMERA-ZEITLEISTE öffnet sich neben dem Panel. Von oben nach unten enthält es:

Monitor
:   Zeigt das Bild der Kamera an der Abspielposition. Ein Klick darauf spielt die
    Zeitleiste im Monitor ab oder pausiert sie.

Wiedergabe
:   Die Abspiel-Schaltfläche spielt die Zeitleiste nur im Monitor ab; die Hauptansicht
    ändert sich dabei nicht. Daneben steht die Zeit. Die Wiederholen-Schaltfläche rechts
    wechselt zwischen Schleife und Einmal. Bei Einmal ist das Wiederholen-Symbol
    durchgestrichen.

Kamerapalette
:   Ein Chip pro Kamera. Ein Klick auf einen Chip fügt am Ende der Zeitleiste einen Clip
    mit dieser Kamera hinzu. Ziehst du ihn auf die Spur, wird der Clip an dieser Stelle
    eingefügt.

Lineal und Spur
:   Die Spur zeigt für jeden Clip einen Block, gefärbt nach Kamera. Du kannst:

    - auf einen Block klicken, um ihn auszuwählen und die Abspielposition an seinen Anfang
      zu setzen;
    - einen Block ziehen, um den Clip früher oder später zu legen;
    - die rechte Kante eines Blocks ziehen, um die Länge des Clips in ganzen Sekunden zu
      ändern;
    - auf das × eines Blocks klicken, um den Clip zu löschen.

    Ein Klick auf das Lineal oder eine leere Stelle der Spur setzt die Abspielposition.
    Ziehst du über das Lineal, spulst du durch die Zeitleiste; ziehst du eine leere Stelle
    der Spur, scrollst du sie. Mit dem Mausrad zoomst du um den Mauszeiger herum hinein und
    heraus; beim Hineinzoomen erscheint unter der Spur eine Bildlaufleiste. Du kannst auch
    über das Ende des letzten Clips hinaus zoomen und scrollen.

Zeitleiste starten
:   Spielt die Zeitleiste in der Hauptansicht ab. Die Tastenkombination dafür,
    **Rechts-Strg + T**, steht neben der Schaltfläche.

Das Editor-Fenster verschiebst du an der Titelleiste und änderst seine Größe am Griff in
der rechten unteren Ecke, genau wie ein Vorschaufenster. Die Nadel hält es bei
geschlossenem Panel auf dem Bildschirm, und das × blendet es aus (mit der Zeile
Editor-Fenster im Panel holst du es zurück). Während der Monitor abspielt, hat das
Vorschaufenster der Kamera, die im Monitor zu sehen ist, einen roten Rahmen.

## Der Abschnitt KAMERA-ZEITLEISTE

Alles, was das Fenster kann, geht auch im Panel, mit der Tastatur oder dem Gamepad.

Abspielen
:   Zeigt, ob die Zeitleiste gestoppt ist, oder während der Wiedergabe den aktuellen Clip
    und die verbleibenden Sekunden. Mit **Enter** oder einem Klick auf die
    Zeile startest du die Zeitleiste, wie mit Zeitleiste starten.

Wiederholen
:   **Schleife** oder **Einmal**.

Editor-Fenster
:   **Sichtbar** oder **Ausgeblendet**.

Vorschau im Fenster
:   Spielt die Zeitleiste im Monitor des Editor-Fensters ab oder stoppt sie.

Clip bearbeiten
:   Wählt den Clip, den die Zeilen darunter ändern. Die Überschrift darüber zeigt die Zahl
    der Clips und ihre Gesamtlänge. Drücke **Enter**, um durch die Kamera des Clips zu
    schauen.

Kamera
:   Die Kamera, die der Clip zeigt.

Dauer
:   Wie lange der Clip dauert, von 1 Sekunde bis 1 Stunde, in Schritten von
    1 Sekunde (mit Bild auf und Bild ab in Schritten von 10 Sekunden).

Clip verschieben
:   Legt den Clip früher (Links) oder später (Rechts).

Clip hinzufügen
:   Fügt nach dem ausgewählten Clip einen neuen hinzu, mit derselben Dauer und der nächsten
    Kamera. Drückst du es mehrmals, bekommst du für jede Kamera einen Clip.

Clip löschen
:   Löscht den ausgewählten Clip.

## Die Zeitleiste starten

Um die Zeitleiste zu starten, klicke auf **Zeitleiste starten**, wähle die Zeile Abspielen
oder drücke **Rechts-Strg + T**. Das Panel schließt sich, und alle Fenster werden
ausgeblendet, auch angeheftete, ebenso das HUD des Spiels. Die Meldung „Zeitleiste startet
in 3..“ zählt herunter, darunter steht „Esc drücken, um zurückzukehren“. Danach
verschwinden die Meldungen, und die Zeitleiste läuft in der Hauptansicht. Beim
Kamerawechsel werden keine Meldungen angezeigt. Während die Zeitleiste läuft, ist nichts von
der Mod auf dem Bildschirm. Starte deine Bildschirmaufnahme also, sobald der Countdown
verschwunden ist, und stoppe sie, bevor du Esc drückst.

Bei **Schleife** wiederholt sich die Zeitleiste, bis du sie stoppst. Bei **Einmal** spielt
sie jeden Clip einmal ab und bleibt dann auf der letzten Kamera.

Mit **Esc** oder **Rechts-Strg + T** stoppst du sie. Du kehrst zu deiner vorherigen
Ansicht zurück, das HUD erscheint wieder, und das Panel öffnet sich erneut, wenn es beim
Start offen war.

Die Uhr der Zeitleiste hält an, solange das Spiel pausiert ist oder du schläfst. So laufen
keine Clips ab, während nichts passiert.

## Speichern

Die Zeitleiste wird zusammen mit deinen Kameras im Spielstand gespeichert. Löschst du eine
Kamera, werden auch ihre Clips gelöscht.
