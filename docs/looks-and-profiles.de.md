# Looks und Profile

Ein **Look** ist ein vollständiger Satz von Effekteinstellungen: die Tilt-Shift-Unschärfe,
die Farben, das Objektiv, das Wetter, alles in den Effektabschnitten des Panels. Die Mod
bringt einige **Vorgabe-Looks** mit, und eigene Looks speicherst du als **Profile**.

<!-- screenshot: die Look-Zeile und die Zeilen GESPEICHERTE PROFILE (docs/assets/) -->

## Vorgabe-Looks

Robin 3rd Person
:   Der abgestimmte Tilt-Shift-Look: Tilt-Shift-Unschärfe mit „Schärfe folgt dem Ziel“,
    Unschärfe nach Entfernung und Bokeh. Alle anderen Effekte werden vorher ausgeschaltet.

Miniatur
:   Entfernungsunschärfe im Hintergrund und eine kräftige Farbkorrektur.

Miniatur + Stop-Motion
:   Miniatur mit 15 Bildern pro Sekunde.

Dezent
:   Eine sanftere Entfernungsunschärfe und Farbkorrektur.

Alles aus
:   Schaltet jeden Effekt aus, wie **Alle Effekte zurücksetzen**.

Miniatur, Miniatur + Stop-Motion und Dezent lassen Tilt-Shift-Unschärfe und Wetter, wie sie
sind. Einen Vorgabe-Look selbst kannst du nicht ändern, aber du kannst speichern, was er dir
gibt, als eigenes Profil.

## Einen Look wählen

Die Zeile **Look** oben im Abschnitt TILT-SHIFT zeigt den Look auf dem Bildschirm. Sie
listet zuerst die Vorgabe-Looks, dann deine gespeicherten Profile.

- **Links / Rechts** (oder `<` und `>` neben dem Wert) blättern durch die Liste. Das Blättern
  ändert noch nichts auf dem Bildschirm.
- **Enter** oder ein Klick auf die Zeile wendet den Look an, bei dem du stehst. Das Anwenden
  eines Looks schaltet auch die Effekte ein.
- Wechselst du ohne Anwenden in eine andere Zeile, zeigt die Look-Zeile wieder den Look auf
  dem Bildschirm.

Ein gespeichertes Profil mit Tastenkombination zeigt seine Nummer vor dem Namen, zum
Beispiel **2 · Ernte**.

Änderst du eine Einstellung, ergänzt die Look-Zeile **(geändert)**, zum Beispiel
**2 · Ernte (geändert)**, und die geänderten Werte werden grün. Wendest du einen anderen Look
an, während es ungespeicherte Änderungen gibt, fragt das Spiel zuerst: **Ungespeicherte
Änderungen verwerfen und … anwenden?** Wähle **Anwenden**, um fortzufahren, oder
**Abbrechen**, um deine Änderungen zu behalten.

Die Look-Zeile zeigt **Eigener**, wenn das, was auf dem Bildschirm ist, keiner der
aufgelisteten Looks ist, zum Beispiel nachdem du das Profil gelöscht hast, aus dem es stammt.

## Einen eigenen Look speichern

Die Zeilen unter **GESPEICHERTE PROFILE** arbeiten mit dem gespeicherten Profil, das gerade
auf dem Bildschirm ist. Zeilen, die gerade nichts tun können, sind abgeblendet.

Änderungen speichern
:   Speichert deine Änderungen in das Profil auf dem Bildschirm. Sein Name steht rechts in
    der Zeile. Nur verfügbar, wenn ein gespeichertes Profil auf dem Bildschirm ist und
    Änderungen hat.

Als neues Profil speichern
:   Speichert sofort, was auf dem Bildschirm ist, als neues Profil mit dem Namen
    **Profil 1**, **Profil 2** und so weiter. Das neue Profil wird der Look auf dem
    Bildschirm.

Profil umbenennen
:   Öffnet das Textfeld des Spiels, um dem Profil auf dem Bildschirm einen neuen Namen mit
    bis zu 32 Zeichen zu geben. Zeichen, die ein Dateiname nicht enthalten kann
    (`\ / : * ? " < > |`), werden weggelassen, und ein Name, den schon ein anderes Profil
    hat, wird abgelehnt.

Profil löschen
:   Löscht das Profil auf dem Bildschirm, nachdem du es bestätigt hast. Was du siehst, bleibt
    auf dem Bildschirm, als **Eigener**.

Um ein Profil zu ändern, das nicht auf dem Bildschirm ist, wende es zuerst in der Look-Zeile
an.

Bei einer Neuinstallation speichert die Mod den Standard-Look als **Profile 1** auf der
Taste 1.

## Tastenkombinationen

**Rechts-Strg + 1** bis **Rechts-Strg + 9** wenden deine gespeicherten Profile sofort an,
ohne Rückfrage, und schalten die Effekte ein. Dieselbe Zahl erneut schaltet die Effekte aus.

Jedes Profil behält seine Nummer dauerhaft: Ein neues Profil bekommt die niedrigste freie
Nummer, Löschen gibt die Nummer frei, und Umbenennen behält sie. Bei mehr als neun Profilen
haben die zusätzlichen keine Taste, stehen aber weiter in der Look-Zeile.

## Die Zeile unter dem Titel

Die Zeile unter dem Titel des Panels sagt dir, was die Effektzeilen gerade ändern und woher
der Look stammt:

| Die Zeile lautet | Bedeutung |
| --- | --- |
| Bearbeitung: Live-Ansicht | Deine eigene Ansicht, ohne gespeichertes Profil oder Vorgabe-Look dahinter |
| Bearbeitung: Live-Ansicht, aus Profil Ernte | Deine eigene Ansicht, mit einem gespeicherten Profil |
| Bearbeitung: Live-Ansicht, Vorgabe-Look Miniatur | Deine eigene Ansicht, mit einem Vorgabe-Look |
| Bearbeitung: Kamera 1, eigener Look | Eine statische Kamera mit eigenem Look |
| Bearbeitung: Kamera 1, nutzt Profil Ernte | Eine statische Kamera, die ein gespeichertes Profil nutzt |

## Statische Kameras und Profile

Die Zeile **Look** einer [statischen Kamera](static-cameras.md) legt fest, ob sie einen
eigenen Look hat (**Eigene**) oder eines deiner gespeicherten Profile nutzt.

- **Eigene:** Änderungen, die du beim Blick durch die Kamera machst, bleiben bei der Kamera.
  Sie zählen nie als ungespeicherte Änderungen.
- **Ein Profil:** Der Blick durch die Kamera wendet das Profil an. Änderungen, die du dort
  machst, erscheinen als **(geändert)**; **Änderungen speichern** schreibt sie in das
  Profil, sodass jede Kamera, die es nutzt, sie bekommt. Nicht gespeicherte Änderungen gehen
  verloren, wenn du wegschaltest.
- Wendest du beim Blick durch eine Kamera mit Profil ein anderes gespeichertes Profil an,
  nutzt die Kamera danach dieses Profil. Bei einer Kamera mit eigenem Look werden die
  Einstellungen des Profils stattdessen in ihren eigenen Look kopiert.
- Wendest du beim Blick durch eine Kamera einen Vorgabe-Look an, bekommt die Kamera diesen
  Look als eigenen.
- Benennst du ein Profil um, gilt der neue Name für jede Kamera, die es nutzt.
- Löschst du ein Profil, behalten die Kameras, die es genutzt haben, seinen Look als eigenen.

## Nach einem Neustart

Die Mod merkt sich, welcher Look auf dem Bildschirm war. Hast du ein gespeichertes Profil
geändert und die Änderungen nicht gespeichert, zeigt es beim nächsten Spielen weiterhin
**(geändert)**.
