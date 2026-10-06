# Looks and profiles

A **look** is a full set of effect settings: the tilt-shift blur, the colours, the lens,
the weather, everything in the panel's effect sections. The mod comes with a few
**built-in looks**, and you can save your own as **profiles**.

![The panel with the TILT SHIFT section open](assets/panel-main.png){ width="480" }

## Built-in looks

Robin 3rd Person
:   The tuned tilt-shift look: tilt-shift blur with Focus Follows Subject, depth-aware blur
    and bokeh. Every other effect is switched off first.

Miniature
:   Distance blur on the background and a strong colour grade.

Miniature + Stop Motion
:   Miniature at 15 frames per second.

Subtle
:   A gentler distance blur and colour grade.

Everything Off
:   Switches every effect off, the same as **Reset All Effects**.

Miniature, Miniature + Stop Motion and Subtle leave the tilt-shift blur and the weather as
they are. You cannot change a built-in look itself, but you can save what it gives you as a
profile of your own.

## Choosing a look

The **Look** row at the top of the TILT SHIFT section shows the look on screen. It lists
the built-in looks first, then your saved profiles.

- **Left / Right** (or the `<` and `>` beside the value) browse through the list. Browsing
  changes nothing on screen yet.
- **Enter**, or a click on the row, applies the look you browsed to. Applying a look also
  turns the effects on.
- Move to another row without applying and the Look row shows the look on screen again.

A saved profile with a hotkey shows its number in front of its name, for example
**2 · Harvest**.

When you change a setting, the Look row adds **(changed)**, for example
**2 · Harvest (changed)**, and the changed values turn green. If you apply another look
while there are unsaved changes, the game asks first: **Discard your unsaved changes and
apply …?** Choose **Apply** to go ahead or **Cancel** to keep your changes.

The Look row shows **Custom** when what is on screen is not one of the listed looks, for
example after you delete the profile it came from.

## Saving your own look

The **SAVED PROFILES** rows under the Look row work on the saved profile that is on screen.
Rows that cannot do anything right now are dimmed.

Save Changes
:   Saves your changes into the profile on screen. Its name is shown at the right of the
    row. Only offered when a saved profile is on screen and has changes.

Save as New Profile
:   Saves what is on screen as a new profile straight away, named **Profile 1**,
    **Profile 2** and so on. The new profile becomes the look on screen.

Rename Profile
:   Opens the game's text box to give the profile on screen a new name of up to 32
    characters. Characters a file name cannot hold (`\ / : * ? " < > |`) are left out, and
    a name another profile already has is refused.

Delete Profile
:   Deletes the profile on screen after you confirm it. What you see stays on screen, as
    **Custom**.

To change a profile that is not on screen, apply it first in the Look row.

On a fresh install the mod saves the default look as **Profile 1**, on hotkey 1.

## Hotkeys

**Right Ctrl + 1** to **Right Ctrl + 9** apply your saved profiles straight away, without
asking, and turn the effects on. Pressing the same number again turns the effects off.

Each profile keeps its number for good: a new profile takes the lowest free number,
deleting a profile frees its number, and renaming a profile keeps it. With more than nine
profiles, the extra ones have no hotkey but are still in the Look row.

## The line under the title

The line under the panel's title tells you what the effect rows are changing and where the
look came from:

| The line reads | Meaning |
| --- | --- |
| Editing: live view | Your own view, with no saved profile or built-in look behind it |
| Editing: live view, from profile Harvest | Your own view, with a saved profile |
| Editing: live view, built-in look Miniature | Your own view, with a built-in look |
| Editing: Camera 1, its own look | A static camera with its own look |
| Editing: Camera 1, uses profile Harvest | A static camera that uses a saved profile |

## Static cameras and profiles

A [static camera](static-cameras.md)'s **Look** row sets whether it has its own look
(**Own**) or uses one of your saved profiles.

- **Own:** changes you make while looking through the camera are kept with the camera. They
  never count as unsaved changes.
- **A profile:** looking through the camera applies the profile. Changes you make there show
  as **(changed)**; **Save Changes** writes them into the profile, so every camera that uses
  it gets them. Changes you do not save are dropped when you switch away.
- Applying another saved profile while looking through a camera that uses a profile makes
  the camera use that profile. On a camera with its own look, the profile's settings are
  copied into the camera's own look instead.
- Applying a built-in look while looking through a camera gives the camera that look as its
  own.
- Renaming a profile renames it for every camera that uses it.
- Deleting a profile leaves its look on the cameras that used it, as their own.

## After a restart

The mod remembers which look was on screen. If you changed a saved profile and did not save
the changes, it still shows **(changed)** the next time you play.
