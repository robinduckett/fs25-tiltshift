# Looks and profiles

A look is a complete set of effect settings: everything in the panel's effect sections,
from the tilt-shift blur to the colours, the lens and the weather. The mod comes with a few
built-in looks, and you can save your own as profiles.

![The panel with the TILT SHIFT section open](assets/panel-main.png){ width="480" }

## Built-in looks

Robin 3rd Person
:   The tuned tilt-shift look: tilt-shift blur with Focus Follows Subject, blur by distance
    and bokeh. It switches every other effect off first.

Miniature
:   Distance blur on the background and a strong colour grade.

Miniature + Stop Motion
:   Miniature at 15 frames per second.

Subtle
:   A lighter distance blur and colour grade.

Everything Off
:   Switches every effect off, like **Reset All Effects**.

Miniature, Miniature + Stop Motion and Subtle leave the tilt-shift blur and the weather as
they were. A built-in look can't be edited, but you can save what it gives you as one of
your own profiles.

## Choosing a look

The Look row at the top of the TILT SHIFT section shows the look on screen. Its list starts
with the built-in looks, followed by your saved profiles.

Left and Right (or the `<` and `>` beside the value) move through the list without
changing anything on screen. Press Enter, or click the row, to apply the look you have
moved to; applying a look also turns the effects on. If you move to another row without
applying, the Look row goes back to showing the look on screen.

A saved profile with a hotkey has its number in front of its name, for example
**2 · Harvest**.

Once you change a setting, the Look row adds "(changed)", as in **2 · Harvest (changed)**,
and the values you changed turn green. If you then apply a different look, the game asks
"Discard your unsaved changes and apply …?" first. **Apply** goes ahead and **Cancel**
keeps your changes.

The row shows **Custom** when what is on screen isn't one of the listed looks, for example
after you delete the profile it came from.

## Saving your own look

The SAVED PROFILES rows under the Look row act on the saved profile that is on screen. A
row that can't do anything at the moment is dimmed.

Save Changes
:   Saves your changes into the profile on screen, whose name is shown at the right of the
    row. It only works when a saved profile is on screen and has changes.

Save as New Profile
:   Saves what is on screen as a new profile right away, named Profile 1, Profile 2 and so
    on. The new profile becomes the look on screen.

Rename Profile
:   Opens the game's text box so you can give the profile on screen a new name, up to 32
    characters long. Characters that can't be used in a file name (`\ / : * ? " < > |`)
    are dropped, and a name that another profile already has is refused.

Delete Profile
:   Deletes the profile on screen once you confirm. The picture doesn't change; the Look
    row just shows it as **Custom**.

To change a profile that isn't on screen, apply it in the Look row first.

On a fresh install the mod saves its default look as **Profile 1**, on hotkey 1.

## Hotkeys

**Right Ctrl + 1** to **Right Ctrl + 9** apply your saved profiles immediately, without
asking, and turn the effects on. Press the same number again to turn the effects off.

A profile keeps its number for as long as it exists. A new profile gets the lowest free
number, deleting a profile frees its number, and renaming a profile doesn't change it. If
you have more than nine profiles, the extra ones have no hotkey but still appear in the
Look row.

## The line under the title

The line under the panel's title tells you what the effect rows are changing and where the
look came from:

| The line reads | Meaning |
| --- | --- |
| Editing: live view | Your own view, not based on a saved profile or built-in look |
| Editing: live view, from profile Harvest | Your own view, based on a saved profile |
| Editing: live view, built-in look Miniature | Your own view, based on a built-in look |
| Editing: Camera 1, its own look | A static camera with its own look |
| Editing: Camera 1, uses profile Harvest | A static camera that uses a saved profile |

## Static cameras and profiles

A [static camera](static-cameras.md) has its own Look row, which is either **Own** (the
camera keeps its own settings) or one of your saved profiles.

With **Own**, anything you change while looking through the camera is stored with the
camera, so it never counts as an unsaved change.

With a profile, looking through the camera applies that profile. Changes you make there
show as "(changed)", and **Save Changes** writes them into the profile, which updates every
camera that uses it. Changes you don't save are lost when you switch to another view.

Applying a look while looking through a camera works like this:

- Another saved profile on a camera that uses a profile: the camera switches to that
  profile.
- A saved profile on a camera with its own look: the profile's settings are copied into the
  camera's own look.
- A built-in look on any camera: the camera gets that look as its own.

Renaming a profile renames it for every camera that uses it. Deleting a profile leaves its
look on those cameras as their own.

## After a restart

The mod remembers which look was on screen. If you changed a saved profile and didn't save
it, the Look row still shows "(changed)" the next time you play.
