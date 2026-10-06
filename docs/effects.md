# Effects

Each effect has its own section in the panel. This page follows the panel's order. The
numbers in brackets are each setting's range.

!!! tip
    Select a value and press **Enter** to put it back to its default.

![The VISUAL EFFECTS section](assets/panel-effects.png){ width="480" }

## VISUAL EFFECTS

This is the tilt-shift effect: a sharp area across the screen, with blur that grows above
and below it. The mod's weather is drawn as part of it, so the weather needs it switched
on.

Tilt-Shift Blur
:   Turns the tilt-shift effect on and off.

### FOCUS

Focus Follows Subject
:   Keeps the sharp area on whatever your camera orbits: your character, your vehicle, or a
    static camera's subject. As you zoom out the sharp area gets narrower, the way a real
    miniature looks from further away.

Subject Focus Size (0.05 to 2)
:   The size of the sharp area around the subject when Focus Follows Subject is on.

Focus Height (0 to 1)
:   Where the sharp area sits on the screen when Focus Follows Subject is off.

Focus Size (0 to 0.5)
:   How tall the sharp area is when Focus Follows Subject is off.

Blur Falloff (0.5 to 4)
:   How quickly the blur builds up outside the sharp area. Low values start blurring close
    to it. High values keep more of the picture sharp and leave the strongest blur for the
    edges of the screen.

Focus Tilt (-4 to 4)
:   Tilts the plane that stays in focus, as a real tilt-shift lens does. It works together
    with Blur by Distance.

### BLUR

Blur Strength (0 to 0.06)
:   The strongest blur, reached at the top and bottom of the screen.

Blur by Distance
:   Blurs by how far things are from the plane in focus rather than by where they are on
    the screen. A rooftop far behind your subject stays soft even where it pokes into the
    sharp area.

Distance Effect (0.5 to 40)
:   How fast the blur grows with distance from the plane in focus, when Blur by Distance is
    on.

Bokeh Highlights (0 to 8)
:   Spreads bright points into soft discs, like the highlights in a macro photo.

High Quality Blur
:   A smoother blur that costs a little more performance.

### COLOUR

Saturation (0 to 3), Contrast (0.5 to 2)
:   The colour and contrast of the picture. Raising both gives the bright look of a painted
    model.

Vignette (0 to 1.5)
:   Darkens the corners of the screen.

## DISTANCE BLUR

The game's own depth of field, set to your distances.

Distance Blur
:   Turns the game's depth of field on and off.

Background Blur (0 to 1.5)
:   How strongly the background is blurred.

Background Blur From (5 to 3000 m), Background Fully Blurred At (10 to 6000 m)
:   Where the background starts to blur and where the blur reaches full strength.

Foreground Blur (0 to 1.5), Foreground Blur Until (0 to 200 m)
:   The same for the foreground, although the game's foreground blur shows little or
    nothing in many views.

## COLOUR

The game's own colour grading, with your values.

Colour Grading
:   Turns the colour grade on and off.

Saturation (0 to 3), Contrast (0.5 to 2), Midtones (0.5 to 2), Highlights (0.5 to 2)
:   The grade itself.

Keep Applied
:   The game sometimes puts its own grade back while you play. With this on, the mod applies
    your grade again on every frame.

## IMAGE

Brightness (0.5 to 2), Sharpness (0 to 3)
:   The game's own brightness and sharpening.

## CAMERA AND LENS

Camera Distance (off, or 1 to 200 m)
:   Lets the orbit camera pull back much further than the game normally allows, so you can
    look down on the farm from high above. It works in third person on foot and on a
    vehicle's outside camera; cab cameras keep their own distance.

Custom Field of View, Field of View (10 to 110 degrees)
:   Replaces the camera's field of view. A narrow field of view flattens the scene, like a
    long lens.

Lens Shift Sideways, Lens Shift Up/Down (-0.5 to 0.5)
:   Slides the picture sideways or up and down without turning the camera, like the shift
    on a tilt-shift lens.

Flat View, Flat View Size (5 to 400 m)
:   A view without perspective, like an architect's model. Flat View Size is how many
    metres of the world fit on screen from top to bottom.

## WEATHER

The mod draws its own rain, snow and hail into the picture so that they blur along with the
miniature. It has to: the game's rain isn't part of the image the effect works on.

Weather Effects
:   Turns the mod's rain, snow and hail on and off.

Match Game Weather
:   Follows the game's weather. When it rains in the game it rains in the miniature,
    including the changeover from one kind of weather to the next. Turn it off to set the
    amounts yourself.

Rain, Snow, Hail (0 to 2)
:   How much of each falls when Match Game Weather is off.

Wind (-2 to 2)
:   How far the wind pushes the rain, snow or hail sideways. Negative values push it the
    other way.

Fall Speed (0.1 to 4)
:   How fast it falls. At 1 it falls as fast as the game's own rain.

Blur With Scene (0 to 4)
:   How strongly the rain, snow or hail blends into the blur and bokeh.

## STOP MOTION

Stop Motion
:   Caps the frame rate so the picture moves like stop-motion animation.

Frames per Second
:   8, 10, 12, 15, 24 or 30.
