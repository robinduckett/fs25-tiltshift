# Das Panel

Alles in der Mod wird in einem Panel am Bildschirmrand eingestellt. Mit **Rechts-Strg + K**
öffnest du es, mit **Rechts-Strg + K** oder **Esc** schließt du es. Solange es offen ist,
läuft das Spiel weiter, aber deine Tasten steuern das Panel statt deiner Figur oder deines
Fahrzeugs.

## Aufbau

- **Die Titelleiste** zeigt TILT-SHIFT-KAMERA-KONFIGURATION. Der Schalter mit dem Augensymbol
  rechts darin schaltet alle Effekte ein und aus, genau wie **Rechts-Strg + J**.
- **Die Zeile unter dem Titel** sagt dir, wessen Look die Effektzeilen gerade ändern und
  woher er stammt: die Live-Ansicht mit einem gespeicherten Profil oder einem Vorgabe-Look,
  eine statische Kamera mit eigenem Look oder eine Kamera, die ein gespeichertes Profil
  nutzt.
- **Abschnitte** wie TILT-SHIFT, VISUELLE EFFEKTE oder WETTER lassen sich ein- und
  ausklappen. Nur der erste ist anfangs offen; das Panel merkt sich, welche du geöffnet hast.
- **Die Legende** unten zeigt die Tasten, die für die gewählte Zeile gelten.

Werte, die du seit dem letzten Anwenden eines Looks oder Speichern eines Profils geändert
hast, erscheinen grün.

<!-- screenshot: das Panel mit geöffnetem Abschnitt TILT-SHIFT (docs/assets/) -->

## Tastatur und Gamepad

| Taste | Funktion |
| --- | --- |
| Pfeiltasten **Hoch / Runter** | Zeile darüber oder darunter wählen |
| Pfeiltasten **Links / Rechts** | Gewählten Wert oder Option ändern |
| **Bild-auf / Bild-ab** | Wert in großen Schritten ändern |
| **Enter** oder **Leertaste** | Abschnitt ein- / ausklappen, Aktion ausführen, Schalter umlegen oder Wert auf den Standard zurücksetzen |
| **Esc** | Panel schließen |

Auch der Ziffernblock funktioniert bei offenem Panel: **8** und **2** bewegen die Auswahl,
**4** und **6** ändern den Wert, **7** und **9** machen große Schritte und **5** wirkt wie
Enter.

Am Gamepad bewegt das Steuerkreuz die Auswahl und ändert Werte, die Bestätigen-Taste wirkt
wie Enter und die Zurück-Taste schließt das Panel.

## Maus

- **Klick auf eine Abschnittsüberschrift** klappt sie ein oder aus.
- **Klick auf eine Zeile** wählt sie. Schalter und Aktionen werden beim Klick ausgeführt.
- **Klick auf `<` oder `>`** neben einem Wert verstellt ihn um einen Schritt. Mit gedrückter
  **Umschalt**-Taste sind es große Schritte.
- **Einen Wert seitlich ziehen** verstellt ihn fortlaufend.
- **Das Mausrad** scrollt die Liste. Um eine Einstellung mit dem Mausrad zu ändern, klicke
  zuerst ihre Zeile an: Ein grüner Balken markiert sie, und das Mausrad verstellt jetzt
  diesen Wert. Ein erneuter Klick auf die Zeile gibt das Mausrad wieder zum Scrollen frei.
- **Klick auf die Tastensymbole** in der Legende für Esc und Rechts-Strg + J schließt das
  Panel bzw. schaltet alle Effekte ein und aus.

Über der Spielwelt, außerhalb des Panels, zoomt das Mausrad weiterhin deine Kamera.

## Der Abschnitt TILT-SHIFT

Der erste Abschnitt enthält die Steuerungen, die du am häufigsten brauchst:

Alle Effekte
:   Der Hauptschalter für den gesamten Look, wie **Rechts-Strg + J**. Ausschalten behält
    alle Einstellungen, gespeichert oder nicht.

Look
:   Einen Vorgabe-Look oder eines deiner gespeicherten Profile wählen. Siehe
    [Looks und Profile](looks-and-profiles.md).

GESPEICHERTE PROFILE
:   **Änderungen speichern**, **Als neues Profil speichern**, **Profil umbenennen** und
    **Profil löschen**. Siehe [Looks und Profile](looks-and-profiles.md#einen-eigenen-look-speichern).

EXTRAS
:   **Statische Kameras**, **Vorschaufenster** und **Kamera-Zeitleiste**. Jede Zeile
    erscheint, sobald die vorherige an ist. Siehe [Statische Kameras](static-cameras.md),
    [Vorschaufenster](preview-windows.md) und [Kamera-Zeitleiste](timeline.md).

UI-Skalierung
:   0,75x, 1x oder 1,25x. Ändert Panel und alle Fenster gemeinsam. 1x entspricht dem HUD des
    Spiels.

Alle Effekte zurücksetzen
:   Schaltet jeden Effekt aus und stellt den normalen Look des Spiels wieder her:
    Tilt-Shift-Unschärfe, Entfernungsunschärfe, Stop-Motion, eigenes Sichtfeld, flache
    Ansicht, Objektiv-Verschiebung, Farbkorrektur, Helligkeit, Schärfe und Kameradistanz.
    Deine gespeicherten Profile bleiben unberührt.
