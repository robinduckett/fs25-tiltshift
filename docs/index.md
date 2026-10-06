---
hide:
  - navigation
  - toc
---

<div class="ts-hero" markdown>

![Tilt Shift Camera](assets/logo.png){ .ts-logo }

<div class="ts-hero-text" markdown>

# Tilt Shift Camera

<p class="ts-lead">Turn your farm into a living miniature. Tilt Shift Camera adds a live, fully tweakable tilt-shift effect to third-person views: a depth-aware blur band that tracks whatever your camera orbits, luminance-weighted bokeh, saturation and contrast grading, an optional stop-motion frame limit and extra lens controls (FoV override, orthographic view, extended camera distance). An optional procedural weather layer adds rain, snow and hail that blur along with the miniature and can follow the live sky. Save your favourite looks as profiles.</p>

[Getting started](getting-started.md){ .md-button .md-button--primary }
[:material-bug-outline: Report an issue](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose){ .md-button }

</div>

</div>

![A farmyard from a raised static camera, with the miniature tilt-shift look](assets/hero.jpg){ .ts-shot }

## What it does

The effect applies to third-person cameras only: cab views, first person and fixed vehicle cameras stay untouched. It also works with free and cinematic cameras from other mods, since it follows the active camera.

The panel (Right Ctrl + K) works with keyboard, gamepad and mouse: click a section to fold it, click a row to select it, step values with the arrow keys, by clicking the &lt; and &gt; beside them or by dragging them sideways, and once a row is clicked the mouse wheel adjusts it. The switch in its title turns all effects on and off. UI Scale (0.75x, 1x, 1.25x) sizes the panel and every window together.

## Extras

Off until you switch them on in the panel's EXTRAS rows, one after the other.

<div class="ts-cards" markdown>

<div class="ts-card" markdown>

### Static cameras

Right Ctrl + N plants a camera exactly where your view is, anchored to the world. Switch to it and back with Right Ctrl + C, step through your cameras with Right Ctrl + V, and keep driving or walking while they film. Each camera keeps its own tilt-shift look (or a profile), and can be aimed from the panel or flown into place with the mouse and W A S D. Cameras belong to your savegame, and in multiplayer each player keeps their own. Every camera also appears on the pause-screen map and the minimap: select it on the map to switch to it or to delete it.

[More](static-cameras.md)

</div>

<div class="ts-card" markdown>

### Preview windows

A live picture from each camera beside the panel. Drag a window by its title, resize it by its corner, pin it to keep it on screen with the panel closed, hide it, fly its camera into a new position, or delete it (after a confirmation). The camera being edited has a green frame, the camera on air a red one.

[More](preview-windows.md)

</div>

<div class="ts-card" markdown>

### Camera timeline

An editor window to cut between your cameras automatically, made for timelapses of your workers in the field. Drag cameras from its palette onto the track, drag shots to reorder them and their edges to time them, zoom with the mouse wheel, and preview the cut in its monitor. Start Timeline (or Right Ctrl + T) hides the panel, every window and the HUD, counts down from 3 and plays the timeline on the main view, in a loop or once, holding the last camera at the end. Press Esc to go back. The timeline is saved with your cameras.

[More](timeline.md)

</div>

</div>

## Hotkeys

| Key | What it does |
| --- | --- |
| **Right Ctrl + K** | Open / close the configuration panel |
| **Right Ctrl + J** | All effects on / off (your current settings are kept, saved or not) |
| **Right Ctrl + 1-9** | Apply profile 1-9 and turn the effects on; the same number again turns them off |
| **Right Ctrl + N** | Add a static camera at the current view |
| **Right Ctrl + C** | Static camera on / off (back to the live view) |
| **Right Ctrl + V** | Next static camera |
| **Right Ctrl + T** | Start the camera timeline; Right Ctrl + T or Esc goes back |
| **Flying a camera** | W A S D move it, the mouse turns it, Shift is fast, Enter saves, Esc cancels |
| **Arrow keys or numpad** | Navigate the panel; Left / Right adjust (Page Up / Page Down for big steps) |
| **Enter** | Fold / unfold a section or run the selected row; Esc: close the panel |
| **Gamepad** | The d-pad navigates and adjusts while the panel is open |

!!! note "Known limitations"

    - Weather effects are simulated because of fundamental limitations in the game engine; they are as close as I can get them.
    - Some decals, glass and other transparent materials are not visible while the effects are applied: the effects use the refraction map, which is rendered before transparent materials.
    - Preview windows show the plain world from each camera: the tilt-shift look and the weather appear on the main view only.
    - While a static camera is active, first person on foot is switched to third person so that you stay visible, and the game's own camera key (C) is overridden until you return to the live view.
