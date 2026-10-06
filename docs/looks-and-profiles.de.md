# Looks und Profile

Ein Look ist ein vollständiger Satz an Effekteinstellungen: alles in den Effektabschnitten
des Panels, von der Tilt-Shift-Unschärfe über die Farben bis zu Objektiv und Wetter. Die Mod
bringt einige Vorgabe-Looks mit, und eigene Looks speicherst du als Profile.

![Das Panel mit geöffnetem Abschnitt TILT SHIFT](assets/panel-main.png){ width="480" }

## Vorgabe-Looks

Robin 3rd Person
:   Der abgestimmte Tilt-Shift-Look: Tilt-Shift-Unschärfe mit „Schärfe folgt dem Ziel“,
    Unschärfe nach Entfernung und Bokeh. Vorher schaltet er alle anderen Effekte aus.

Miniatur
:   Entfernungsunschärfe im Hintergrund und eine kräftige Farbkorrektur.

Miniatur + Stop-Motion
:   Miniatur mit 15 Bildern pro Sekunde.

Dezent
:   Eine schwächere Entfernungsunschärfe und Farbkorrektur.

Alles aus
:   Schaltet jeden Effekt aus, wie **Alle Effekte zurücksetzen**.

Miniatur, Miniatur + Stop-Motion und Dezent lassen Tilt-Shift-Unschärfe und Wetter, wie sie
waren. Einen Vorgabe-Look kannst du nicht bearbeiten, aber du kannst das Ergebnis als
eigenes Profil speichern.

## Einen Look wählen

Die Zeile Look oben im Abschnitt TILT-SHIFT zeigt den Look, der gerade auf dem Bildschirm
ist. Ihre Liste beginnt mit den Vorgabe-Looks, danach kommen deine gespeicherten Profile.

Mit Links und Rechts (oder `<` und `>` neben dem Wert) blätterst du durch die Liste, ohne
dass sich auf dem Bildschirm etwas ändert. Enter oder ein Klick auf die Zeile wendet den
Look an, bei dem du stehst; dabei werden auch die Effekte eingeschaltet. Gehst du ohne
Anwenden in eine andere Zeile, zeigt die Look-Zeile wieder den Look auf dem Bildschirm.

Ein gespeichertes Profil mit Taste hat seine Nummer vor dem Namen, zum Beispiel
**2 · Ernte**.

Sobald du eine Einstellung änderst, ergänzt die Look-Zeile „(geändert)“, etwa
**2 · Ernte (geändert)**, und die geänderten Werte werden grün. Willst du dann einen anderen
Look anwenden, fragt das Spiel zuerst: „Ungespeicherte Änderungen verwerfen und … anwenden?“
**Anwenden** macht weiter, **Abbrechen** behält deine Änderungen.

Die Zeile zeigt **Eigener**, wenn das Bild keinem Look aus der Liste entspricht, zum
Beispiel nachdem du das Profil gelöscht hast, aus dem es stammt.

## Einen eigenen Look speichern

Die Zeilen unter GESPEICHERTE PROFILE wirken auf das gespeicherte Profil, das gerade auf dem
Bildschirm ist. Eine Zeile, die im Moment nichts tun kann, ist abgeblendet.

Änderungen speichern
:   Speichert deine Änderungen in das Profil auf dem Bildschirm, dessen Name rechts in der
    Zeile steht. Das geht nur, wenn ein gespeichertes Profil auf dem Bildschirm ist und
    Änderungen hat.

Als neues Profil speichern
:   Speichert das aktuelle Bild sofort als neues Profil mit dem Namen Profil 1, Profil 2
    und so weiter. Das neue Profil wird zum Look auf dem Bildschirm.

Profil umbenennen
:   Öffnet das Textfeld des Spiels, in dem du dem Profil auf dem Bildschirm einen neuen
    Namen mit bis zu 32 Zeichen gibst. Zeichen, die in einem Dateinamen nicht erlaubt sind
    (`\ / : * ? " < > |`), fallen weg, und einen Namen, den schon ein anderes Profil hat,
    lehnt die Mod ab.

Profil löschen
:   Löscht das Profil auf dem Bildschirm, nachdem du bestätigt hast. Das Bild bleibt gleich;
    die Look-Zeile zeigt es dann als **Eigener**.

Willst du ein Profil ändern, das nicht auf dem Bildschirm ist, wendest du es zuerst in der
Look-Zeile an.

Bei einer Neuinstallation speichert die Mod ihren Standard-Look als **Profile 1** auf
Taste 1.

## Tastenkombinationen

**Rechts-Strg + 1** bis **Rechts-Strg + 9** wenden deine gespeicherten Profile sofort an,
ohne Rückfrage, und schalten die Effekte ein. Dieselbe Zahl noch einmal schaltet die Effekte
aus.

Ein Profil behält seine Nummer, solange es existiert. Ein neues Profil bekommt die
niedrigste freie Nummer, beim Löschen wird die Nummer frei, und beim Umbenennen bleibt sie
gleich. Hast du mehr als neun Profile, haben die übrigen keine Taste, stehen aber trotzdem
in der Look-Zeile.

## Die Zeile unter dem Titel

Die Zeile unter dem Titel des Panels zeigt, was die Effektzeilen gerade ändern und woher der
Look kommt:

| In der Zeile steht | Bedeutung |
| --- | --- |
| Bearbeitung: Live-Ansicht | Deine eigene Ansicht, nicht aus einem gespeicherten Profil oder Vorgabe-Look |
| Bearbeitung: Live-Ansicht, aus Profil Ernte | Deine eigene Ansicht, aus einem gespeicherten Profil |
| Bearbeitung: Live-Ansicht, Vorgabe-Look Miniatur | Deine eigene Ansicht, aus einem Vorgabe-Look |
| Bearbeitung: Kamera 1, eigener Look | Eine statische Kamera mit eigenem Look |
| Bearbeitung: Kamera 1, nutzt Profil Ernte | Eine statische Kamera, die ein gespeichertes Profil nutzt |

## Statische Kameras und Profile

Eine [statische Kamera](static-cameras.md) hat eine eigene Look-Zeile. Dort steht entweder
**Eigene** (die Kamera behält ihre eigenen Einstellungen) oder eines deiner gespeicherten
Profile.

Bei **Eigene** wird alles, was du beim Blick durch die Kamera änderst, bei der Kamera
gespeichert. Das zählt deshalb nie als ungespeicherte Änderung.

Bei einem Profil wird beim Blick durch die Kamera dieses Profil angewendet. Änderungen, die
du dort machst, erscheinen als „(geändert)“, und **Änderungen speichern** schreibt sie ins
Profil, womit jede Kamera, die es nutzt, sie bekommt. Was du nicht speicherst, geht
verloren, sobald du in eine andere Ansicht wechselst.

Wendest du beim Blick durch eine Kamera einen Look an, passiert Folgendes:

- Ein anderes gespeichertes Profil bei einer Kamera mit Profil: Die Kamera nutzt danach
  dieses Profil.
- Ein gespeichertes Profil bei einer Kamera mit eigenem Look: Die Einstellungen des Profils
  werden in den eigenen Look der Kamera kopiert.
- Ein Vorgabe-Look bei einer beliebigen Kamera: Die Kamera bekommt diesen Look als eigenen.

Benennst du ein Profil um, gilt der neue Name für jede Kamera, die es nutzt. Löschst du ein
Profil, behalten diese Kameras seinen Look als eigenen.

## Nach einem Neustart

Die Mod merkt sich, welcher Look auf dem Bildschirm war. Hast du ein gespeichertes Profil
geändert und nicht gespeichert, zeigt die Look-Zeile beim nächsten Spielen weiterhin
„(geändert)“.
