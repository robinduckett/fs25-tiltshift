# Limitations and FAQ

## Known limitations

Rain, snow and hail are simulated
:   The game's own rain is not part of the image the effect works on, so the mod draws its
    own rain, snow and hail. I have made them as close to the game's weather as I can, but
    they do not look exactly the same.

Some transparent materials are hidden
:   Some decals, glass and other transparent materials are not visible while the effects are
    on. This is because the effects work on a copy of the picture that the game makes
    before it draws transparent materials.

Preview windows show the view without effects
:   The tilt-shift blur, the distance blur and the weather effects are only shown in the
    main view, not in the preview windows or the timeline monitor.

Third person only
:   The effect only applies to third-person cameras. Cab views, first person and fixed
    vehicle cameras are not affected.

## FAQ

I installed the mod, but nothing changes.
:   The effects are always off when you load a game. Press **Right Ctrl + J**, and make sure
    you are in a third-person view.

Where are the static cameras?
:   They are off until you switch them on. Open the panel and set **Static Cameras** in the
    EXTRAS rows to ON. Preview windows and the camera timeline are switched on in the same
    place, one after the other.

Why did my view switch from first person to third person?
:   While you look through a static camera, the game switches you to third person on foot
    so that your character is visible. Press **Right Ctrl + C** to go back to the live view.

The game's camera key (C) does nothing.
:   It is disabled while you look through a static camera, so that it cannot switch you
    away by accident. Press **Right Ctrl + C** to go back to the live view.

I can't drive while the panel is open.
:   While the panel is open, your keys control the panel. Close it with **Esc** or
    **Right Ctrl + K**.

How do I get the game's normal look back?
:   **Right Ctrl + J** turns all effects off and keeps your settings. **Reset All Effects**
    in the panel turns every effect off and restores the game's normal look.

I changed some settings and then pressed a profile key. Are my changes lost?
:   Yes, unless you saved them first. **Right Ctrl + 1** to **9** apply the profile straight
    away. Only the Look row in the panel asks before discarding unsaved changes. See
    [Looks and profiles](looks-and-profiles.md).

Does the mod work in multiplayer?
:   Yes. It only changes what you see on your own screen, and each player has their own
    cameras and timeline.

Where do I report a problem?
:   Use [Report an issue](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose).
    Please include your `log.txt` from `Documents/My Games/FarmingSimulator2025`.
