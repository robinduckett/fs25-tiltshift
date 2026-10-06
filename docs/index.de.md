---
hide:
  - navigation
  - toc
---

<div class="ts-hero" markdown>

![Tilt Shift Kamera](assets/logo.png){ .ts-logo }

<div class="ts-hero-text" markdown>

# Tilt Shift Kamera

<p class="ts-lead">Verwandle deinen Hof in eine lebendige Miniaturwelt. Tilt Shift Kamera fügt den Third-Person-Ansichten einen live einstellbaren Tilt-Shift-Effekt hinzu: ein tiefenbasiertes Schärfeband, das dem Ziel deiner Kamera folgt, helligkeitsgewichtetes Bokeh, Sättigungs- und Kontrastkorrektur, ein optionales Stop-Motion-Bildratenlimit sowie zusätzliche Objektivsteuerungen (Sichtfeld, orthografische Ansicht, erweiterte Kameradistanz). Eine optionale prozedurale Wetterebene fügt Regen, Schnee und Hagel hinzu, die mit der Miniatur unscharf werden und dem echten Himmel folgen können. Speichere deine Lieblings-Looks als Profile.</p>

[Erste Schritte](getting-started.md){ .md-button .md-button--primary }
[:material-bug-outline: Problem melden](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose){ .md-button }

</div>

</div>

![Ein Hof von einer erhöhten statischen Kamera, im Miniatur-Tilt-Shift-Look](assets/hero.jpg){ .ts-shot }

## Was die Mod macht

Der Effekt gilt nur für Third-Person-Kameras: Kabinenansichten, First-Person- und feste Fahrzeugkameras bleiben unberührt. Er funktioniert auch mit freien und filmischen Kameras anderer Mods, da er der aktiven Kamera folgt.

Das Panel (Rechts-Strg + K) lässt sich mit Tastatur, Gamepad und Maus bedienen: Klick auf einen Abschnitt klappt ihn ein oder aus, Klick auf eine Zeile wählt sie, Werte stellst du mit den Pfeiltasten, per Klick auf &lt; und &gt; oder durch seitliches Ziehen ein, und nach einem Klick auf eine Zeile verstellt das Mausrad ihren Wert. Der Schalter im Titel schaltet die Effekte ein und aus. Die UI-Skalierung (0,75x, 1x, 1,25x) ändert Panel und alle Fenster gemeinsam.

## Extras

Ausgeschaltet bis du sie im Bereich EXTRAS des Panels nacheinander einschaltest.

<div class="ts-cards" markdown>

<div class="ts-card" markdown>

### Statische Kameras

Rechts-Strg + N setzt eine Kamera genau dort, wo dein Blick ist, verankert in der Welt. Mit Rechts-Strg + C wechselst du zu ihr und zurück, mit Rechts-Strg + V durch deine Kameras, während du weiterfährst oder weitergehst. Jede Kamera behält ihren eigenen Tilt-Shift-Look (oder ein Profil) und lässt sich im Panel ausrichten oder mit Maus und W A S D an ihren Platz fliegen. Kameras gehören zum Spielstand, im Mehrspielermodus behält jeder Spieler seine eigenen. Jede Kamera erscheint auch auf der Karte im Pausenmenü und auf der Minikarte: wähle sie auf der Karte aus, um zu ihr zu wechseln oder sie zu löschen.

[Mehr](static-cameras.md)

</div>

<div class="ts-card" markdown>

### Vorschaufenster

Ein Livebild jeder Kamera neben dem Panel. Ein Fenster am Titel verschieben, an der Ecke in der Größe ändern, anheften, damit es bei geschlossenem Panel sichtbar bleibt, ausblenden, seine Kamera neu einfliegen oder sie (nach einer Rückfrage) löschen. Die bearbeitete Kamera hat einen grünen Rahmen, die Kamera auf Sendung einen roten.

[Mehr](preview-windows.md)

</div>

<div class="ts-card" markdown>

### Kamera-Zeitleiste

Ein Editor-Fenster, das automatisch zwischen deinen Kameras schneidet, gemacht für Zeitraffer deiner Helfer bei der Feldarbeit. Kameras aus der Palette auf die Spur ziehen, Einstellungen zum Umordnen ziehen und an der Kante die Dauer ändern, mit dem Mausrad zoomen und den Schnitt im Monitor ansehen. Zeitleiste starten (oder Rechts-Strg + T) blendet Panel, alle Fenster und das HUD aus, zählt von 3 herunter und spielt die Zeitleiste in der Hauptansicht ab, in Schleife oder einmal, wobei am Ende die letzte Kamera stehen bleibt. Mit Esc kehrst du zurück. Die Zeitleiste wird mit deinen Kameras gespeichert.

[Mehr](timeline.md)

</div>

</div>

## Tastenkombinationen

| Taste | Funktion |
| --- | --- |
| **Rechts-Strg + K** | Konfigurationspanel öffnen / schließen |
| **Rechts-Strg + J** | Alle Effekte ein / aus (die aktuellen Einstellungen bleiben erhalten, auch ungespeicherte) |
| **Rechts-Strg + 1-9** | Profil 1-9 anwenden und Effekte einschalten; dieselbe Zahl erneut schaltet sie aus |
| **Rechts-Strg + N** | Statische Kamera an der aktuellen Ansicht hinzufügen |
| **Rechts-Strg + C** | Statische Kamera ein / aus (zurück zur Live-Ansicht) |
| **Rechts-Strg + V** | Nächste statische Kamera |
| **Rechts-Strg + T** | Kamera-Zeitleiste starten; Rechts-Strg + T oder Esc kehrt zurück |
| **Kamera fliegen** | W A S D bewegen sie, die Maus dreht sie, Umschalt ist schnell, Enter speichert, Esc bricht ab |
| **Pfeiltasten oder Ziffernblock** | Im Panel navigieren; Links / Rechts verstellen (Bild-auf / Bild-ab für große Schritte) |
| **Enter** | Abschnitt ein- / ausklappen oder gewählte Zeile ausführen; Esc: Panel schließen |
| **Gamepad** | Steuerkreuz navigiert und verstellt, solange das Panel offen ist |

!!! note "Bekannte Einschränkungen"

    - Die Wettereffekte sind simuliert, da die Spiel-Engine hier grundlegende Grenzen setzt; sie sind so nah am Original, wie ich sie hinbekomme.
    - Einige Decals, Glas und andere transparente Materialien sind bei aktivem Effekt nicht sichtbar: Die Effekte nutzen die Refraction-Map, die vor den transparenten Materialien gerendert wird.
    - Vorschaufenster zeigen die Welt ohne Effekt: Tilt-Shift-Look und Wetter erscheinen nur in der Hauptansicht.
    - Solange eine statische Kamera aktiv ist, wird die Ego-Perspektive zu Fuß auf die Third-Person-Ansicht umgeschaltet, damit du sichtbar bleibst, und die Kamerataste des Spiels (C) ist bis zur Rückkehr in die Live-Ansicht überschrieben.
