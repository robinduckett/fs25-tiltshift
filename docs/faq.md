# Limitations and FAQ

## Known limitations

Rain, snow and hail are simulated
:   The game's own rain is not part of the image the effect works on, so the mod draws its
    own rain, snow and hail. I have made them as close to the game's weather as I can, but
    they do not look exactly the same.

Some transparent materials are hidden
:   Some decals, glass and other transparent materials are not visible while the tilt-shift
    blur is on. This is because the blur works on a copy of the picture that the game makes
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
:   While you look through a static camera, the mod switches you to third person on foot so
    that your character is visible, and back to first person when you return to the live
    view. Press **Right Ctrl + C** to go back to the live view.

The game's camera key (C) does nothing.
:   It is disabled while you look through a static camera, so that it cannot switch you
    away by accident. Press **Right Ctrl + C** to go back to the live view.

I'm looking through a camera and my mouse doesn't move the view.
:   A static camera stays where you put it: your mouse and keys still move your character
    or vehicle, which you may not see from the camera. The bar at the bottom of the screen
    shows the way back: **Right Ctrl + C** for your own view. If you picked the camera on
    the map, press **Esc**. Closing the panel always takes you back to the view you opened
    it from.

How do I hide the HUD while I film?
:   The game itself has no key to hide the whole HUD. Start Timeline hides the HUD, the
    panel and all windows for you, pinned ones included. Switch to Camera on the pause-menu
    map hides the HUD, but pinned preview windows stay on screen. While you look through a
    camera with **Right Ctrl + C** or **Right Ctrl + V**, the HUD stays on screen, and so
    does the bar of keys at the bottom, which is part of the HUD.

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

Does the mod record video?
:   No. It sets up the picture: the look, the cameras and the timeline. Record with your
    usual screen recording software. Everything the mod does is drawn live in the game, so
    the recording is the finished picture.

I copied my savegame and the cameras are gone.
:   Cameras are kept in the mod's own settings folder
    (`Documents/My Games/FarmingSimulator2025/modSettings/FS25_TiltShift`), tied to the slot,
    the map and the start date of the savegame you made them in, not in the savegame
    folder. When you move to another PC, copy that folder as well. A savegame copied to
    another slot starts without cameras.

Does the mod work in multiplayer?
:   Yes. It only changes what you see on your own screen, and each player has their own
    cameras and timeline.

Where do I report a problem?
:   Use [Report an issue](https://github.com/robinduckett/fs25-tiltshift/issues/new/choose).
    Please include your `log.txt` from `Documents/My Games/FarmingSimulator2025`.
