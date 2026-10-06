# Effekte

Jeder Effekt hat einen eigenen Abschnitt im Panel. Die Abschnitte stehen hier in der
Reihenfolge, in der das Panel sie zeigt. Zahlen in Klammern sind der Bereich der jeweiligen
Einstellung.

!!! tip
    Wähle einen Wert und drücke **Enter**, um ihn auf den Standard zurückzusetzen.

## SCREEN-SPACE-SHADER

Das ist der eigentliche Tilt-Shift-Effekt: ein scharfes Band quer über den Bildschirm, mit
Unschärfe, die darüber und darunter zunimmt. Auch die Wettereffekte werden von ihm
gezeichnet und brauchen ihn deshalb.

Shader-Quad
:   Schaltet den Tilt-Shift-Effekt ein und aus.

### SCHÄRFEBAND

Auto-Schärfeband
:   Das scharfe Band folgt dem, was deine Kamera umkreist: deiner Figur, deinem Fahrzeug
    oder dem Motiv einer statischen Kamera. Zoomst du heraus, wird das Band schmaler, wie
    bei einer echten Miniatur aus größerer Entfernung.

Bandskalierung (0,05 bis 2)
:   Wie breit das automatische Band um das Motiv ist.

Fokuszentrum Y (0 bis 1)
:   Wo das scharfe Band auf dem Bildschirm liegt. Gilt, wenn das Auto-Schärfeband aus ist.

Schärfeband-Halbbreite (0 bis 0,5)
:   Wie hoch das scharfe Band ist. Gilt, wenn das Auto-Schärfeband aus ist.

Verlaufsstärke (0,5 bis 4)
:   Wie sich die Unschärfe außerhalb des Bands aufbaut. Niedrige Werte machen gleich nach dem
    Band unscharf; hohe Werte lassen den Bereich neben dem Band schärfer und heben die
    Unschärfe für die Ränder auf.

Fokusebenen-Neigung (-4 bis 4)
:   Neigt die scharf abgebildete Ebene, wie ein Tilt-Shift-Objektiv. Wirkt zusammen mit der
    tiefenbasierten Unschärfe.

### UNSCHÄRFE

Max. Unschärfe (0 bis 0,06)
:   Die stärkste Unschärfe, oben und unten im Bild.

Tiefenbasierte Unschärfe
:   Macht nach dem Abstand zur scharfen Ebene unscharf statt nach der Bildschirmposition.
    So wird ein Dach, das ins scharfe Band ragt, trotzdem weich, wenn es weit hinter deinem
    Motiv liegt.

Tiefenstärke (0,5 bis 40)
:   Wie schnell die Unschärfe mit dem Abstand zur scharfen Ebene zunimmt, wenn die
    tiefenbasierte Unschärfe an ist.

Bokeh-Verstärkung (0 bis 8)
:   Lässt helle Punkte zu weichen Scheiben aufblühen, wie die Lichter in einem Makrofoto.

Hochwertige Unschärfe
:   Eine weichere Unschärfe, die etwas mehr Leistung kostet.

### LOOK

Shader-Sättigung (0 bis 3), Shader-Kontrast (0,5 bis 2)
:   Farbe und Kontrast des Bilds, der spielzeughafte Pep einer Miniatur.

Vignette (0 bis 1,5)
:   Dunkelt die Bildecken ab.

## TIEFENSCHÄRFE

Die Tiefenschärfe des Spiels, mit deinen Entfernungen.

Unschärfe
:   Schaltet die Tiefenschärfe des Spiels ein und aus.

Fern-Radius (0 bis 1,5)
:   Wie stark die Ferne unscharf wird.

Fern-Beginn (5 bis 3000 m), Fern-Ende (10 bis 6000 m)
:   Wo die Unschärfe in der Ferne beginnt und wo sie ihre volle Stärke erreicht.

Nah-Radius (0 bis 1,5), Nah-Ende (0 bis 200 m)
:   Dasselbe für den Vordergrund. Die Nah-Unschärfe des Spiels zeigt in vielen Ansichten
    wenig oder nichts.

## FARBKORREKTUR

Die Farbkorrektur des Spiels, mit deinen Werten.

Farbkorrektur
:   Schaltet die Farbkorrektur ein und aus.

Sättigung (0 bis 3), Kontrast (0,5 bis 2), Gamma (0,5 bis 2), Gain (0,5 bis 2)
:   Die Korrektur selbst.

Jeden Frame erneuern
:   Das Spiel kann während des Spielens seine eigene Farbkorrektur zurücksetzen. Ist diese
    Option an, wird deine Korrektur in jedem Frame neu angewendet.

## NACHBEARBEITUNG

Helligkeit (0,5 bis 2), Schärfe (0 bis 3)
:   Helligkeit und Nachschärfen des Spiels.

## OBJEKTIV + KAMERA

Kameradistanz (aus oder 1 bis 200 m)
:   Lässt die Orbit-Kamera viel weiter zurückfahren, als das Spiel erlaubt, für den
    klassischen Miniaturblick von hoch oben. Gilt für die Third-Person-Ansicht zu Fuß und
    für die Außenkamera eines Fahrzeugs; Kabinenkameras behalten ihre eigene Distanz.

Sichtfeld überschreiben, Sichtfeld (10 bis 110 Grad)
:   Ersetzt das Sichtfeld der Kamera. Ein enges Sichtfeld macht die Szene flacher, wie ein
    Teleobjektiv.

Shift X, Shift Y (-0,5 bis 0,5)
:   Objektiv-Shift: verschiebt das Bild seitlich oder nach oben und unten, ohne die Kamera zu
    drehen, wie der Shift eines Tilt-Shift-Objektivs.

Orthografisch, Ortho-Höhe (5 bis 400 m)
:   Eine Ansicht ganz ohne Perspektive, wie ein Architekturmodell. Die Ortho-Höhe gibt an,
    wie viele Meter der Welt von oben bis unten auf den Bildschirm passen.

## WETTER

Regen, Schnee und Hagel, in die Miniatur gezeichnet, damit sie mit ihr unscharf werden. Der
Regen des Spiels ist nicht Teil des Bilds, mit dem der Effekt arbeitet, deshalb zeichnet die
Mod ihren eigenen.

Niederschlag
:   Schaltet Regen, Schnee und Hagel der Mod ein und aus.

Himmel folgen
:   Folgt dem echten Wetter: In der Miniatur regnet es, wenn es im Spiel regnet,
    einschließlich des Übergangs von einem Wetter zum nächsten. Schalte es aus, um die Mengen
    selbst einzustellen.

Regen, Schnee, Hagel (0 bis 2)
:   Wie viel davon fällt, wenn „Himmel folgen“ aus ist.

Winddrift (-2 bis 2)
:   Wie weit der Wind den Niederschlag seitlich treibt. Negative Werte treiben ihn in die
    andere Richtung.

Fallgeschwindigkeit (0,1 bis 4)
:   Wie schnell er fällt. 1 entspricht dem Regen des Spiels.

Unschärfe-Mischung (0 bis 4)
:   Wie stark der Niederschlag mit Unschärfe und Bokeh verschmilzt.

## STOP-MOTION

Bildratenlimit
:   Begrenzt die Bildrate für einen Stop-Motion-Look.

Ziel-FPS
:   8, 10, 12, 15, 24 oder 30 Bilder pro Sekunde.
