# Camera timeline

The camera timeline switches between your static cameras by itself. You build a list of
shots, each one a camera held for a number of seconds, and start it. While your workers get
on with the fieldwork the view keeps changing, which makes it easy to record a timelapse.

!!! info "Switch it on first"
    The timeline needs [static cameras](static-cameras.md) and
    [preview windows](preview-windows.md). With both on, set **Camera Timeline** in the
    panel's EXTRAS rows to ON. The CAMERA TIMELINE section and the editor window then appear.

![The camera timeline editor with a preview window](assets/timeline-editor.jpg)

## The editor window

The CAMERA TIMELINE window opens beside the panel. From top to bottom it has:

The monitor
:   The picture from the camera at the playhead. Click it to play or pause the cut in the
    monitor.

Transport
:   The play button plays the cut in the monitor only, leaving the main view where it is.
    The time is shown next to it. The repeat button on the right switches between Loop and
    Once; Once shows the repeat icon with a no-entry sign over it.

Camera palette
:   One chip for each camera. Click a chip to add a shot of that camera at the end, or drag
    it onto the track to insert the shot where you drop it.

Ruler and track
:   One block per shot, coloured by camera. On the track you can:

    - click a block to select it, which moves the playhead to its start;
    - drag a block to move it earlier or later;
    - drag its right edge to make it longer or shorter, in whole seconds;
    - click its × to delete it.

    Clicking the ruler or an empty part of the track moves the playhead. Dragging along the
    ruler scrubs through the cut, and dragging an empty part of the track scrolls it. The
    mouse wheel zooms in and out around the pointer, and a scroll bar appears under the
    track while you are zoomed in. You can zoom and scroll past the end of the last shot.

Start Timeline
:   Plays the timeline on the main view. Its shortcut, **Right Ctrl + T**, is shown next to
    it.

The editor window works like a preview window: drag its title bar to move it and the grip
in its bottom-right corner to resize it. The pin keeps it on screen when the panel is
closed, and × hides it (the panel's Editor Window row brings it back). While the monitor is
playing, the preview window of the camera in the monitor gets a red frame.

## The CAMERA TIMELINE section

Everything the window does can also be done from the panel, with the keyboard or a gamepad.

Play
:   Shows whether the timeline is stopped or, while it plays, the shot and the seconds
    left. Press **Enter** or click it to start the timeline, the same as Start Timeline.

Repeat
:   **Loop** or **Once**.

Editor Window
:   **Shown** or **Hidden**.

Preview in Window
:   Plays or stops the cut in the window's monitor.

Edit Shot
:   Picks the shot that the rows below it change. The heading above it shows how many shots
    there are and their total length. Press **Enter** to look through the shot's camera.

Camera
:   The camera the shot shows.

Duration
:   How long the shot lasts, from 1 second to an hour, in steps of 1 second (10 seconds with
    Page Up and Page Down).

Move Shot
:   Moves the shot earlier (Left) or later (Right).

Add Shot
:   Adds a shot after the selected one, with the same duration and the next camera in the
    list. Pressing it a few times gives you one shot of each camera.

Delete Shot
:   Deletes the selected shot.

## Starting the timeline

Press **Start Timeline**, choose the Play row, or press **Right Ctrl + T**. The panel
closes, and every window is hidden (pinned ones too), along with the game's HUD. A message
counts down "Timeline starting in 3..", with "Press Esc to go back" underneath. When it
reaches the end, the messages go away and the timeline plays on the main view. It changes
cameras without showing any messages.

With **Loop** the timeline repeats until you stop it. With **Once** it plays every shot and
then stays on the last camera.

Press **Esc** or **Right Ctrl + T** to go back. You return to the view you had before, the
HUD comes back, and the panel opens again if it was open when you started.

The timeline's clock stops while the game is paused or you are asleep, so no shot gets used
up while nothing is happening.

## Saving

The timeline is saved with your cameras, in the savegame. Deleting a camera also deletes its
shots.
