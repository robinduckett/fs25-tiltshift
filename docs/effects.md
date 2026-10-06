# Effects

Every effect has its own section in the panel. The sections are listed here in the order
the panel shows them. Numbers in brackets are the range of each setting.

!!! tip
    Select a value and press **Enter** to put it back to its default.

<!-- screenshot: the VISUAL EFFECTS section open in the panel (docs/assets/) -->

## VISUAL EFFECTS

This is the tilt-shift effect itself: a sharp area across the screen with blur growing
above and below it. The weather effects are drawn by it too, so they need it on.

Tilt-Shift Blur
:   Turns the tilt-shift effect on and off.

### FOCUS

Focus Follows Subject
:   The sharp area follows what your camera orbits: your character, your vehicle, or a
    static camera's subject. Zoom out and the sharp area narrows, just like a real miniature
    seen from further away.

Subject Focus Size (0.05 to 2)
:   How large the sharp area is around the subject, when Focus Follows Subject is on.

Focus Height (0 to 1)
:   Where the sharp area sits on the screen. Used when Focus Follows Subject is off.

Focus Size (0 to 0.5)
:   How tall the sharp area is. Used when Focus Follows Subject is off.

Blur Falloff (0.5 to 4)
:   How the blur builds up outside the sharp area. Low values blur soon after it; high
    values keep the area next to it sharper and save the blur for the edges.

Focus Tilt (-4 to 4)
:   Tilts the plane that stays in focus, as a tilt-shift lens does. Used with Blur by
    Distance.

### BLUR

Blur Strength (0 to 0.06)
:   The strongest blur, at the top and bottom of the screen.

Blur by Distance
:   Blurs by distance from the plane in focus instead of by screen position, so a rooftop
    that pokes into the sharp area still goes soft when it is far behind your subject.

Distance Effect (0.5 to 40)
:   How quickly the blur grows with distance from the plane in focus, when Blur by Distance
    is on.

Bokeh Highlights (0 to 8)
:   Makes bright points bloom into soft discs, like the highlights in a macro photo.

High Quality Blur
:   A smoother blur that costs a little more performance.

### COLOUR

Saturation (0 to 3), Contrast (0.5 to 2)
:   Colour and contrast of the picture, the toy-like punch of a miniature.

Vignette (0 to 1.5)
:   Darkens the corners of the screen.

## DISTANCE BLUR

The game's own depth of field, with your distances.

Distance Blur
:   Turns the game's depth of field on and off.

Background Blur (0 to 1.5)
:   How strongly the distance is blurred.

Background Blur From (5 to 3000 m), Background Fully Blurred At (10 to 6000 m)
:   Where the background blur begins and where it reaches full strength.

Foreground Blur (0 to 1.5), Foreground Blur Until (0 to 200 m)
:   The same for the foreground. The game's foreground blur shows little or nothing in many
    views.

## COLOUR

The game's own colour grading, with your values.

Colour Grading
:   Turns the colour grade on and off.

Saturation (0 to 3), Contrast (0.5 to 2), Midtones (0.5 to 2), Highlights (0.5 to 2)
:   The grade itself.

Keep Applied
:   The game can put its own grade back while you play. With this on, your grade is applied
    again every frame.

## IMAGE

Brightness (0.5 to 2), Sharpness (0 to 3)
:   The game's own brightness and sharpening.

## CAMERA AND LENS

Camera Distance (off, or 1 to 200 m)
:   Lets the orbit camera pull back much further than the game allows, for the classic
    miniature view from high above. Applies to third person on foot and to a vehicle's
    outside camera; cab cameras keep their own distance.

Custom Field of View, Field of View (10 to 110 degrees)
:   Replaces the camera's field of view. A narrow field of view flattens the scene like a
    long lens.

Lens Shift Sideways, Lens Shift Up/Down (-0.5 to 0.5)
:   Slides the picture sideways or up and down without turning the camera, as the shift of
    a tilt-shift lens does.

Flat View, Flat View Size (5 to 400 m)
:   A view with no perspective at all, like an architect's model. Flat View Size is how many
    metres of the world fit on the screen from top to bottom.

## WEATHER

Rain, snow and hail drawn into the miniature, so they blur along with it. The game's own
rain is not part of the picture the effect works on, so the mod draws its own.

Weather Effects
:   Turns the mod's rain, snow and hail on and off.

Match Game Weather
:   Follows the live weather: it rains in the miniature when it rains in the game,
    including the change from one weather to the next. Turn it off to set the amounts
    yourself.

Rain, Snow, Hail (0 to 2)
:   How much of each falls when Match Game Weather is off.

Wind (-2 to 2)
:   How far the wind blows the precipitation sideways. Negative values blow it the other
    way.

Fall Speed (0.1 to 4)
:   How fast it falls. 1 matches the game's own rain.

Blur With Scene (0 to 4)
:   How strongly the precipitation melts into the blur and bokeh.

## STOP MOTION

Stop Motion
:   Caps the frame rate for a stop-motion feel.

Frames per Second
:   8, 10, 12, 15, 24 or 30 frames per second.
