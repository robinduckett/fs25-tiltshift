---
hide:
  - navigation
  - toc
---

<div class="ts-hero" markdown>

![Tilt Shift Kamera](assets/logo.png){ .ts-logo }

<div class="ts-hero-text" markdown>

# Tilt Shift Kamera

<p class="ts-lead">Tilt Shift Kamera fügt den Third-Person-Ansichten einen Tilt-Shift-Effekt hinzu. Ein Streifen quer über den Bildschirm bleibt scharf, alles darüber und darunter wird unscharf. Dadurch wirkt die Szene wie ein Miniaturmodell. Standardmäßig folgt der scharfe Streifen dem, worum deine Kamera kreist. Außerdem kannst du helle Punkte als Bokeh darstellen, die Farben kräftiger machen und die Bildecken abdunkeln, das Sichtfeld ändern, die Perspektive entfernen, das Objektiv verschieben, die Kamera weiter herauszoomen und die Bildrate für einen Stop-Motion-Look begrenzen. Die Mod kann eigenen Regen, Schnee und Hagel darstellen, der dem Wetter im Spiel folgt und mit dem restlichen Bild unscharf wird. Looks, die dir gefallen, speicherst du als Profile.</p>

[Erste Schritte](getting-started.md){ .md-button .md-button--primary }
[:material-bug-outline: Problem melden](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose){ .md-button }

</div>

</div>

![Ein Hof von einer erhöhten statischen Kamera, im Miniatur-Tilt-Shift-Look](assets/hero.jpg){ .ts-shot }

## Was die Mod macht

Der Effekt wirkt nur bei Third-Person-Kameras. Kabinenansichten, die Ego-Perspektive und feste Fahrzeugkameras sind nicht betroffen. Er funktioniert auch mit freien und filmischen Kameras anderer Mods, weil er immer der aktiven Kamera folgt.

Alle Einstellungen befinden sich in einem Panel (Rechts-Strg + K), das du mit Tastatur, Gamepad oder Maus bedienen kannst. Ein Klick auf einen Abschnitt klappt ihn ein oder aus, ein Klick auf eine Zeile wählt sie. Werte änderst du mit den Pfeiltasten, mit einem Klick auf &lt; und &gt; daneben oder indem du sie zur Seite ziehst. Nachdem du eine Zeile angeklickt hast, ändert das Mausrad ihren Wert. Der Schalter im Titel des Panels schaltet alle Effekte ein und aus. Die UI-Skalierung (0,75x, 1x oder 1,25x) ändert die Größe des Panels und aller Fenster der Mod.

## Extras

Drei Extras sind ausgeschaltet, bis du sie nacheinander in den EXTRAS-Zeilen des Panels einschaltest.

<div class="ts-cards" markdown>

<div class="ts-card" markdown>

### Statische Kameras

Rechts-Strg + N fügt an deiner aktuellen Ansicht eine Kamera hinzu, die fest in der Welt steht. Mit Rechts-Strg + C wechselst du zu ihr und zurück, mit Rechts-Strg + V zur nächsten Kamera, während du weiterfährst oder weitergehst. Jede Kamera hat ihre eigenen Effekteinstellungen oder nutzt eines deiner Profile. Du kannst eine Kamera im Panel ausrichten oder mit Maus und W A S D in Position fliegen. Kameras werden mit deinem Spielstand gespeichert, und im Mehrspielermodus hat jeder Spieler seine eigenen. Jede Kamera erscheint außerdem auf der Karte im Pausenmenü und auf der Minikarte, wo du sie auswählen kannst, um zu ihr zu wechseln oder sie zu löschen.

[Mehr](static-cameras.md)

</div>

<div class="ts-card" markdown>

### Vorschaufenster

Das Livebild jeder Kamera, neben dem Panel angezeigt. Du kannst ein Fenster an der Titelleiste verschieben, an der Ecke in der Größe ändern, anheften, damit es bei geschlossenem Panel sichtbar bleibt, ausblenden, seine Kamera an eine neue Position fliegen oder die Kamera löschen (nach einer Rückfrage). Die Kamera, die du bearbeitest, hat einen grünen Rahmen, die Kamera auf Sendung einen roten.

[Mehr](preview-windows.md)

</div>

<div class="ts-card" markdown>

### Kamera-Zeitleiste

Ein Editor-Fenster, das automatisch zwischen deinen Kameras wechselt, zum Beispiel für einen Zeitraffer deiner Helfer bei der Feldarbeit. Ziehe Kameras aus der Palette auf die Spur, verschiebe Einstellungen, um ihre Reihenfolge zu ändern, und ziehe an ihren Kanten, um ihre Länge zu ändern. Mit dem Mausrad zoomst du, und im Monitor siehst du eine Vorschau. Zeitleiste starten (oder Rechts-Strg + T) blendet das Panel, alle Fenster und das HUD aus, zählt von 3 herunter und spielt die Zeitleiste dann in der Hauptansicht ab, entweder in Schleife oder einmal, wobei am Ende die letzte Kamera stehen bleibt. Mit Esc kehrst du zurück. Die Zeitleiste wird mit deinen Kameras gespeichert.

[Mehr](timeline.md)

</div>

</div>

## Tastenkombinationen

| Taste | Funktion |
| --- | --- |
| **Rechts-Strg + K** | Panel öffnen oder schließen |
| **Rechts-Strg + J** | Alle Effekte ein- oder ausschalten (deine Einstellungen bleiben erhalten, ob gespeichert oder nicht) |
| **Rechts-Strg + 1-9** | Profil 1-9 anwenden und die Effekte einschalten; dieselbe Zahl noch einmal schaltet sie aus |
| **Rechts-Strg + N** | Statische Kamera an deiner aktuellen Ansicht hinzufügen |
| **Rechts-Strg + C** | Zu einer statischen Kamera wechseln oder zurück zur Live-Ansicht |
| **Rechts-Strg + V** | Zur nächsten statischen Kamera wechseln |
| **Rechts-Strg + T** | Kamera-Zeitleiste starten; Rechts-Strg + T oder Esc stoppt sie |
| **Kamera fliegen** | W A S D bewegen sie, die Maus dreht sie, Umschalt fliegt schneller, Enter speichert, Esc bricht ab |
| **Pfeiltasten oder Ziffernblock** | Zeilen im Panel wählen; Links und Rechts ändern den Wert (Bild auf und Bild ab für große Schritte) |
| **Enter** | Abschnitt ein- oder ausklappen oder die gewählte Zeile ausführen; Esc: Panel schließen |
| **Gamepad** | Das Steuerkreuz wählt Zeilen und ändert Werte, solange das Panel offen ist |

!!! note "Bekannte Einschränkungen"

    - Regen, Schnee und Hagel sind wegen Grenzen der Spiel-Engine nachgebildet. Ich habe sie dem Wetter im Spiel so weit wie möglich angeglichen.
    - Einige Decals, Glas und andere transparente Materialien sind nicht sichtbar, solange die Effekte an sind. Die Effekte arbeiten auf einer Kopie des Bildes, die das Spiel anlegt, bevor es transparente Materialien zeichnet.
    - Vorschaufenster zeigen das Bild jeder Kamera ohne die Effekte. Tilt-Shift-Unschärfe und Wetter sind nur in der Hauptansicht zu sehen.
    - Solange du durch eine statische Kamera schaust, schaltet das Spiel dich zu Fuß von der Ego-Perspektive in die dritte Person, damit deine Spielfigur zu sehen ist, und die Kamerataste des Spiels (C) hat keine Wirkung, bis du zur Live-Ansicht zurückkehrst.
