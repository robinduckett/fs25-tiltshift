# The panel

Everything in the mod is set up in one panel at the side of the screen. Press
**Right Ctrl + K** to open it and **Right Ctrl + K** or **Esc** to close it. While it is
open the game keeps running, but your keys drive the panel instead of your character or
vehicle.

## Layout

- **The title bar** reads TILT SHIFT CAMERA CONFIG. The switch with the eye icon at its
  right turns all effects on and off, just like **Right Ctrl + J**.
- **The line under the title** tells you whose look the effect rows are changing right now
  and where it came from: the live view with a saved profile or a built-in look, a static
  camera with its own look, or a camera that uses a saved profile.
- **Sections** such as TILT SHIFT, VISUAL EFFECTS or WEATHER fold and unfold. Only the
  first one starts open; the panel remembers which ones you opened.
- **The legend** at the bottom shows the keys that work on the selected row.

Values you have changed since you last applied a look or saved a profile are shown in
green.

<!-- screenshot: the panel with the TILT SHIFT section open (docs/assets/) -->

## Keyboard and gamepad

| Key | What it does |
| --- | --- |
| **Up / Down** arrows | Select the row above or below |
| **Left / Right** arrows | Change the selected value or option |
| **Page Up / Page Down** | Change the value in big steps |
| **Enter** or **Space** | Fold or unfold a section, run an action, flip a switch, or put a value back to its default |
| **Esc** | Close the panel |

The number pad works too while the panel is open: **8** and **2** move the selection,
**4** and **6** change the value, **7** and **9** take big steps, and **5** is the same as
Enter.

On a gamepad, the d-pad moves the selection and changes values, the confirm button works
like Enter and the back button closes the panel.

## Mouse

- **Click a section header** to fold or unfold it.
- **Click a row** to select it. Switches and actions run on the click.
- **Click the `<` or `>`** beside a value to step it. Hold **Shift** for big steps.
- **Drag a value sideways** to step it continuously.
- **The mouse wheel** scrolls the list. To change a setting with the wheel, click its row
  first: a green bar marks it and the wheel now adjusts that value. Click the row again
  to give the wheel back to scrolling.
- **Click the key chips** in the legend for Esc and Right Ctrl + J to close the panel or
  turn all effects on and off.

Over the game world, outside the panel, the mouse wheel still zooms your camera.

## The TILT SHIFT section

The first section holds the controls you use most:

All Effects
:   The master switch for the whole look, the same as **Right Ctrl + J**. Turning it off
    keeps every setting, saved or not.

Look
:   Pick a built-in look or one of your saved profiles. See
    [Looks and profiles](looks-and-profiles.md).

SAVED PROFILES
:   **Save Changes**, **Save as New Profile**, **Rename Profile** and **Delete Profile**. See
    [Looks and profiles](looks-and-profiles.md#saving-your-own-look).

EXTRAS
:   **Static Cameras**, **Preview Windows** and **Camera Timeline**. Each one appears once the
    one before it is on. See [Static cameras](static-cameras.md),
    [Preview windows](preview-windows.md) and [Camera timeline](timeline.md).

UI Scale
:   0.75x, 1x or 1.25x. It sizes the panel and every window together. 1x matches the game's
    own HUD.

Reset All Effects
:   Switches every effect off and puts the game's own look back: tilt-shift blur, distance
    blur, stop motion, custom field of view, flat view, lens shift, colour grading,
    brightness, sharpness and camera distance. Your saved profiles are not touched.
