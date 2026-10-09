# Looks und Profile

Ein Look ist ein kompletter Satz an Effekteinstellungen: alles in den Effektabschnitten des
Panels, also zum Beispiel Unschärfe, Farben, Objektiv und Wetter. Die Mod bringt fünf
Vorgabe-Looks mit, und du kannst eigene Looks als Profile speichern.

![Das Panel mit geöffnetem Abschnitt TILT-SHIFT](assets/panel-main.png){ width="480" }

## Vorgabe-Looks

Robin 3rd Person
:   Der empfohlene Look für die dritte Person: die Tilt-Shift-Unschärfe mit „Schärfe folgt
    dem Ziel“, „Unschärfe nach Entfernung“ und Bokeh. Alle anderen Effekte werden
    ausgeschaltet.

Miniatur
:   Die Entfernungsunschärfe des Spiels auf dem Hintergrund und eine kräftige
    Farbkorrektur.

Miniatur + Stop-Motion
:   Miniatur mit 15 Bildern pro Sekunde.

Dezent
:   Eine schwächere Entfernungsunschärfe und Farbkorrektur.

Alles aus
:   Schaltet alle Effekte aus, wie **Alle Effekte zurücksetzen**.

Miniatur, Miniatur + Stop-Motion und Dezent ändern weder die Tilt-Shift-Unschärfe noch
die Wettereinstellungen. Einen Vorgabe-Look kannst du nicht bearbeiten, aber du kannst
seine Einstellungen ändern und das Ergebnis als Profil speichern.

## Einen Look wählen

Die Zeile Look oben im Abschnitt TILT-SHIFT zeigt den aktuellen Look. Die Liste enthält
zuerst die Vorgabe-Looks, danach deine gespeicherten Profile.

Mit Links und Rechts (oder einem Klick auf `<` und `>` neben dem Wert) blätterst du durch
die Liste. Dabei werden nur die Namen angezeigt: Am Bild ändert sich erst etwas, wenn du
Enter drückst oder auf die Zeile klickst. Dann wird der Look angewendet und die Effekte
werden eingeschaltet. Wechselst du zu einer anderen Zeile, ohne anzuwenden, zeigt die Zeile
Look wieder den aktuellen Look.

Gespeicherte Profile mit Tastenkombination zeigen die Nummer vor dem Namen, zum Beispiel
**2 · Ernte**.

Sobald du eine Einstellung änderst, steht in der Zeile Look zusätzlich „(geändert)“, etwa
**2 · Ernte (geändert)**, und die geänderten Werte werden grün und bekommen ein Sternchen.
Wendest du dann einen anderen Look an, fragt das Spiel zuerst: „Ungespeicherte Änderungen
verwerfen und … anwenden?“ Wähle **Anwenden**, um fortzufahren, oder **Abbrechen**, um
deine Änderungen zu behalten. Schließt du stattdessen das Panel, fragt es „Änderungen am
Profil … vor dem Schließen speichern?“: **Speichern** schreibt sie ins Profil,
**Nicht speichern** schließt das Panel und behält sie als ungespeicherte Änderungen auf dem
Bildschirm.

Gehören die aktuellen Einstellungen zu keinem Look in der Liste, zum Beispiel weil du das
Profil gelöscht hast, aus dem sie stammen, zeigt die Zeile Look **Eigener**.

## Einen eigenen Look speichern

Die Zeilen unter GESPEICHERTE PROFILE beziehen sich auf das Profil, das gerade angewendet
ist. Zeilen, die du gerade nicht benutzen kannst, sind ausgegraut.

Änderungen speichern
:   Speichert deine Änderungen im aktuellen Profil. Der Name des Profils steht rechts in
    der Zeile. Nur verfügbar, wenn ein gespeichertes Profil angewendet ist und du etwas
    geändert hast.

Als neues Profil speichern
:   Speichert die aktuellen Einstellungen als neues Profil mit dem Namen Profil 1, Profil 2
    und so weiter und macht es zum aktuellen Look.

Profil umbenennen
:   Öffnet das Texteingabefeld des Spiels, in dem du das aktuelle Profil umbenennen kannst.
    Namen dürfen bis zu 32 Zeichen lang sein. Zeichen, die in Dateinamen nicht erlaubt
    sind (`\ / : * ? " < > |`), werden entfernt, und einen Namen, den schon ein anderes
    Profil trägt, kannst du nicht verwenden.

Profil löschen
:   Löscht das aktuelle Profil, nachdem du bestätigt hast. Die Einstellungen auf dem
    Bildschirm bleiben erhalten, und die Zeile Look zeigt **Eigener**.

Um ein Profil zu ändern, das gerade nicht angewendet ist, wende es zuerst in der Zeile Look
an.

Beim ersten Start nach der Installation speichert die Mod ihre Standardeinstellungen als
**Profil 1** auf der Tastenkombination 1.

## Tastenkombinationen

**Rechts-Strg + 1** bis **Rechts-Strg + 9** wenden deine gespeicherten Profile sofort an,
ohne nach ungespeicherten Änderungen zu fragen, und schalten die Effekte ein. Drückst du
dieselbe Zahl noch einmal, werden die Effekte ausgeschaltet.

Jedes Profil behält seine Nummer, bis du es löschst. Ein neues Profil bekommt die
niedrigste freie Nummer, und beim Umbenennen bleibt die Nummer gleich. Hast du mehr als
neun Profile, haben die übrigen keine Tastenkombination, stehen aber trotzdem in der Zeile
Look.

## Die Zeile unter dem Titel

Die Zeile unter dem Titel des Panels zeigt, worauf sich die Effekteinstellungen gerade
beziehen und von welchem Look sie stammen:

| Die Zeile lautet | Bedeutung |
| --- | --- |
| Bearbeitung: Live-Ansicht | Deine eigene Ansicht, ohne gespeichertes Profil oder Vorgabe-Look |
| Bearbeitung: Live-Ansicht, aus Profil Ernte | Deine eigene Ansicht, auf Grundlage eines gespeicherten Profils |
| Bearbeitung: Live-Ansicht, Vorgabe-Look Miniatur | Deine eigene Ansicht, auf Grundlage eines Vorgabe-Looks |
| Bearbeitung: Kamera 1, eigener Look | Eine statische Kamera mit eigenen Einstellungen |
| Bearbeitung: Kamera 1, nutzt Profil Ernte | Eine statische Kamera, die ein gespeichertes Profil nutzt |

## Statische Kameras und Profile

Jede [statische Kamera](static-cameras.md) hat eine eigene Einstellung Look. Sie steht
entweder auf **Eigene**, dann hat die Kamera ihre eigenen Einstellungen, oder auf einem
deiner gespeicherten Profile.

Bei **Eigene** wird jede Änderung, die du beim Blick durch die Kamera machst, mit der
Kamera gespeichert. Sie gilt deshalb nie als ungespeicherte Änderung.

Bei einem Profil wird beim Blick durch die Kamera dieses Profil angewendet. Änderungen
werden als „(geändert)“ angezeigt, und **Änderungen speichern** speichert sie im Profil.
Damit ändern sich auch alle anderen Kameras, die dieses Profil nutzen. Wechselst du die
Ansicht, ohne zu speichern, gehen die Änderungen verloren.

Wendest du einen Look an, während du durch eine Kamera schaust, gilt:

- ein gespeichertes Profil auf einer Kamera, die ein Profil nutzt: Die Kamera wechselt zum
  neuen Profil;
- ein gespeichertes Profil auf einer Kamera mit eigenen Einstellungen: Die Einstellungen
  des Profils werden in die Kamera übernommen;
- ein Vorgabe-Look auf einer beliebigen Kamera: Die Kamera übernimmt diesen Look als ihre
  eigenen Einstellungen.

Benennst du ein Profil um, ändert sich der Name bei allen Kameras, die es nutzen. Löschst
du ein Profil, behalten diese Kameras seine Einstellungen als eigene.

## Nach einem Neustart

Die Mod merkt sich beim Beenden den aktuellen Look. Hast du ein gespeichertes Profil
geändert, ohne zu speichern, zeigt die Zeile Look beim nächsten Spielen weiterhin
„(geändert)“.
