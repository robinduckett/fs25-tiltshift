# Camera timeline

The camera timeline cuts between your static cameras on its own. Build a list of shots,
each one a camera held for a number of seconds, then start it and let your workers do the
fieldwork while the views change by themselves: ready to record a timelapse.

!!! info "Switch it on first"
    The timeline needs [static cameras](static-cameras.md) and
    [preview windows](preview-windows.md). With both on, set **Camera Timeline** in the
    panel's EXTRAS rows to ON. The CAMERA TIMELINE section and the editor window then appear.

## The editor window

The CAMERA TIMELINE window opens beside the panel. From top to bottom:

The monitor
:   A picture of the camera at the playhead. Click it to play or pause the cut in the
    monitor.

Transport
:   The **play** button plays the cut in the monitor only: the main view stays where it is.
    Next to it is the time. The **repeat** button at the right switches between **Loop** and
    **Once** (the repeat icon with a no-entry sign).

Camera palette
:   One chip per camera. **Click** a chip to add a shot of that camera at the end, or
    **drag** it onto the track to insert the shot where you drop it.

Ruler and track
:   One block per shot, coloured by camera.

    - **Click** a block to select it; the playhead jumps to its start.
    - **Drag** a block to move it earlier or later.
    - **Drag its right edge** to change how long it lasts, in whole seconds.
    - Click its **×** to delete it.
    - **Click** the ruler or an empty part of the track to move the playhead. **Drag** along
      the ruler to scrub through the cut; drag an empty part of the track to scroll.
    - The **mouse wheel** zooms in and out around the pointer. When zoomed in, a scroll bar
      appears under the track. You can zoom and scroll past the end of the last shot.

Start Timeline
:   Plays the timeline for real, on the main view. Its shortcut, **Right Ctrl + T**, is
    shown beside it.

Like a preview window, the editor moves by its title bar and resizes by the grip in its
bottom-right corner. The **pin** keeps it on screen with the panel closed, and the **×**
hides it (the panel's **Editor Window** row shows it again). While the monitor plays, the
preview window of the camera in the monitor gets a red frame.

## The CAMERA TIMELINE section

Everything in the window can be done from the panel too, with the keyboard or a gamepad.

Play
:   Shows where the timeline is (Stopped, or the shot and the seconds left). **Enter** or a
    click starts it, the same as Start Timeline.

Repeat
:   **Loop** or **Once**.

Editor Window
:   **Shown** or **Hidden**.

Preview in Window
:   Plays or stops the cut in the window's monitor.

Edit Shot
:   Picks the shot the rows below change. The heading above it counts your shots and their
    total length. Press **Enter** to look through the shot's camera.

Camera
:   The camera this shot shows.

Duration
:   How long the shot lasts, from 1 second to an hour, in steps of 1 second (10 seconds with
    Page Up and Page Down).

Move Shot
:   Moves the shot earlier (left) or later (right).

Add Shot
:   Adds a shot after the selected one, as long as it and showing the next camera, so
    pressing it a few times walks through all your cameras.

Delete Shot
:   Deletes the selected shot.

## Starting the timeline

Press **Start Timeline**, choose the **Play** row, or press **Right Ctrl + T**:

1. The panel closes and every window is hidden, pinned ones too, along with the game's HUD.
2. "Timeline starting in 3.." counts down from 3, above "Press Esc to go back".
3. The messages disappear and the timeline plays on the main view, switching cameras
   without any messages on screen.

With **Loop**, it keeps going until you stop it. With **Once**, it plays every shot and then
stays on the last camera.

Press **Esc** or **Right Ctrl + T** to go back: you return to the view you had before, the
HUD comes back, and the panel opens again if it was open.

The timeline's clock stops while the game is paused or you are sleeping, so a shot never
runs out while nothing happens.

## Saving

The timeline is saved with your cameras, in your savegame. Deleting a camera also removes
its shots.
