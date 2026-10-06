# Limitations and FAQ

## Known limitations

The weather is simulated
:   The game's own rain isn't part of the image the effect works on, so the mod draws its
    own rain, snow and hail. I've made them as close to the game's as I can, but they aren't
    the same.

Some transparent materials disappear
:   Some decals, glass and other transparent materials can't be seen while the effects are
    on. The effects work on a copy of the picture that the game makes before it draws
    transparent materials.

Preview windows show the plain world
:   The tilt-shift look, the distance blur and the weather only appear in the main view, not
    in the preview windows or the timeline monitor.

Third person only
:   The effect works on orbit cameras. Cab views, first person and fixed vehicle cameras are
    left alone.

## FAQ

I installed the mod, but nothing changes.
:   The effects are off each time you load a game. Press **Right Ctrl + J**, and check that
    you are in a third-person view.

Where are the static cameras?
:   They are off until you switch them on. Open the panel and set **Static Cameras** in the
    EXTRAS rows to ON. Preview windows and the camera timeline are switched on the same way,
    one after the other.

Why did my first-person view switch to third person?
:   While a static camera is on screen, the game puts you in third person on foot so that
    you can be seen in the shot. **Right Ctrl + C** takes you back to the live view.

The game's camera key (C) does nothing.
:   The mod takes it over while a static camera is on screen, so that it can't pull you out
    of the shot. **Right Ctrl + C** takes you back to the live view.

I can't drive while the panel is open.
:   Your keys control the panel while it is open. Close it with **Esc** or
    **Right Ctrl + K**.

How do I get the game's normal look back?
:   **Right Ctrl + J** turns all effects off and keeps your settings. **Reset All Effects**
    in the panel switches every effect off and restores the game's own look.

I changed some settings and pressed a profile key. Are my changes gone?
:   Yes, unless you saved them first. The **Right Ctrl + 1** to **9** keys apply the profile
    straight away. Only the panel's Look row asks before it discards unsaved changes. See
    [Looks and profiles](looks-and-profiles.md).

Does it work in multiplayer?
:   Yes. It only changes your own screen, and each player has their own cameras and
    timeline.
