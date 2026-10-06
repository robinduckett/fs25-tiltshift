# Kamera-Zeitleiste

Die Kamera-Zeitleiste schaltet von selbst zwischen deinen statischen Kameras um. Du legst
eine Liste von Einstellungen an, jede eine Kamera für eine bestimmte Anzahl Sekunden, und
startest sie. Während deine Helfer die Feldarbeit erledigen, wechselt die Ansicht ständig,
und du kannst ganz einfach einen Zeitraffer aufnehmen.

!!! info "Zuerst einschalten"
    Die Zeitleiste braucht [statische Kameras](static-cameras.md) und
    [Vorschaufenster](preview-windows.md). Sind beide an, stelle **Kamera-Zeitleiste** in
    den EXTRAS-Zeilen des Panels auf AN. Danach erscheinen der Abschnitt KAMERA-ZEITLEISTE
    und das Editor-Fenster.

![Das Editor-Fenster der Kamera-Zeitleiste mit einem Vorschaufenster](assets/timeline-editor.jpg)

## Das Editor-Fenster

Das Fenster KAMERA-ZEITLEISTE öffnet sich neben dem Panel. Von oben nach unten enthält es:

Der Monitor
:   Das Bild der Kamera am Abspielkopf. Ein Klick darauf spielt den Schnitt im Monitor ab
    oder hält ihn an.

Transportleiste
:   Die Abspiel-Schaltfläche spielt den Schnitt nur im Monitor ab; die Hauptansicht bleibt,
    wie sie ist. Daneben steht die Zeit. Die Wiederholen-Schaltfläche rechts wechselt
    zwischen Schleife und Einmal; bei Einmal liegt ein Verbotszeichen über dem
    Wiederholen-Symbol.

Kamerapalette
:   Ein Chip pro Kamera. Ein Klick auf einen Chip hängt eine Einstellung mit dieser Kamera
    am Ende an. Ziehst du ihn auf die Spur, wird die Einstellung dort eingefügt, wo du ihn
    loslässt.

Lineal und Spur
:   Ein Block pro Einstellung, gefärbt nach Kamera. Auf der Spur kannst du:

    - einen Block anklicken, um ihn zu wählen, wobei der Abspielkopf an seinen Anfang
      springt;
    - einen Block ziehen, um ihn früher oder später zu legen;
    - seine rechte Kante ziehen, um ihn in ganzen Sekunden länger oder kürzer zu machen;
    - sein × anklicken, um ihn zu löschen.

    Ein Klick auf das Lineal oder eine leere Stelle der Spur setzt den Abspielkopf. Ziehst
    du über das Lineal, spulst du durch den Schnitt, und ziehst du eine leere Stelle der
    Spur, scrollst du sie. Das Mausrad zoomt um den Mauszeiger herum hinein und heraus, und
    solange du hineingezoomt bist, erscheint unter der Spur eine Bildlaufleiste. Du kannst
    über das Ende der letzten Einstellung hinaus zoomen und scrollen.

Zeitleiste starten
:   Spielt die Zeitleiste in der Hauptansicht ab. Das Kürzel **Rechts-Strg + T** steht
    daneben.

Das Editor-Fenster funktioniert wie ein Vorschaufenster: Du verschiebst es an der
Titelleiste und änderst seine Größe am Griff unten rechts. Die Nadel hält es bei
geschlossenem Panel auf dem Bildschirm, und × blendet es aus (die Zeile Editor-Fenster im
Panel holt es zurück). Solange der Monitor abspielt, bekommt das Vorschaufenster der Kamera
im Monitor einen roten Rahmen.

## Der Abschnitt KAMERA-ZEITLEISTE

Alles, was das Fenster kann, geht auch im Panel, mit Tastatur oder Gamepad.

Abspielen
:   Zeigt, ob die Zeitleiste gestoppt ist, oder während sie läuft die Einstellung und die
    verbleibenden Sekunden. **Enter** oder ein Klick startet die Zeitleiste, genau wie
    Zeitleiste starten.

Wiederholen
:   **Schleife** oder **Einmal**.

Editor-Fenster
:   **Sichtbar** oder **Ausgeblendet**.

Vorschau im Fenster
:   Spielt den Schnitt im Monitor des Fensters ab oder stoppt ihn.

Einstellung bearbeiten
:   Wählt die Einstellung, die die Zeilen darunter ändern. Die Überschrift darüber zeigt,
    wie viele Einstellungen es gibt und wie lang sie zusammen sind. Mit **Enter** schaust
    du durch die Kamera der Einstellung.

Kamera
:   Die Kamera, die die Einstellung zeigt.

Dauer
:   Wie lange die Einstellung dauert, von 1 Sekunde bis zu einer Stunde, in Schritten von
    1 Sekunde (10 Sekunden mit Bild-auf und Bild-ab).

Einstellung verschieben
:   Legt die Einstellung früher (Links) oder später (Rechts).

Einstellung hinzufügen
:   Fügt nach der gewählten Einstellung eine neue mit derselben Dauer und der nächsten
    Kamera der Liste ein. Drückst du es ein paar Mal, hast du eine Einstellung pro Kamera.

Einstellung löschen
:   Löscht die gewählte Einstellung.

## Die Zeitleiste starten

Drücke **Zeitleiste starten**, wähle die Zeile Abspielen oder drücke **Rechts-Strg + T**.
Das Panel schließt sich, und alle Fenster verschwinden (auch angeheftete), ebenso das HUD
des Spiels. Eine Meldung zählt „Zeitleiste startet in 3..“ herunter, darunter steht „Esc
drücken, um zurückzukehren“. Danach verschwinden die Meldungen, und die Zeitleiste läuft in
der Hauptansicht. Beim Kamerawechsel erscheinen keine Meldungen.

Mit **Schleife** wiederholt sich die Zeitleiste, bis du sie stoppst. Mit **Einmal** spielt
sie jede Einstellung ab und bleibt dann bei der letzten Kamera stehen.

Mit **Esc** oder **Rechts-Strg + T** kehrst du zurück. Du landest wieder in der Ansicht von
vorher, das HUD kommt zurück, und das Panel öffnet sich wieder, wenn es beim Start offen
war.

Die Uhr der Zeitleiste hält an, solange das Spiel pausiert ist oder du schläfst. So läuft
keine Einstellung ab, während nichts passiert.

## Speichern

Die Zeitleiste wird mit deinen Kameras im Spielstand gespeichert. Löschst du eine Kamera,
werden auch ihre Einstellungen gelöscht.
