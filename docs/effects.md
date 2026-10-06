# Effects

Every effect has its own section in the panel. The sections are listed here in the order
the panel shows them. Numbers in brackets are the range of each setting.

!!! tip
    Select a value and press **Enter** to put it back to its default.

## SCREEN-SPACE SHADER

This is the tilt-shift effect itself: a sharp band across the screen with blur growing
above and below it. The weather effects are drawn by it too, so they need it on.

Shader Quad
:   Turns the tilt-shift effect on and off.

### FOCUS BAND

Auto Band
:   The sharp band follows what your camera orbits: your character, your vehicle, or a
    static camera's subject. Zoom out and the band narrows, just like a real miniature
    seen from further away.

Auto Band Scale (0.05 to 2)
:   How wide the automatic band is around the subject.

Focus Centre Y (0 to 1)
:   Where the sharp band sits on the screen. Used when Auto Band is off.

Sharp Band Half-Width (0 to 0.5)
:   How tall the sharp band is. Used when Auto Band is off.

Gradient Power (0.5 to 4)
:   How the blur builds up outside the band. Low values blur soon after the band; high
    values keep the area next to the band sharper and save the blur for the edges.

Focal Plane Tilt (-4 to 4)
:   Tilts the plane that stays in focus, as a tilt-shift lens does. Used with Depth-Aware
    Blur.

### BLUR

Max Blur (0 to 0.06)
:   The strongest blur, at the top and bottom of the screen.

Depth-Aware Blur
:   Blurs by distance from the plane in focus instead of by screen position, so a rooftop
    that pokes into the sharp band still goes soft when it is far behind your subject.

Depth Strength (0.5 to 40)
:   How quickly the blur grows with distance from the plane in focus, when Depth-Aware Blur
    is on.

Bokeh Boost (0 to 8)
:   Makes bright points bloom into soft discs, like the highlights in a macro photo.

High Quality Blur
:   A smoother blur that costs a little more performance.

### LOOK

Shader Saturation (0 to 3), Shader Contrast (0.5 to 2)
:   Colour and contrast of the picture, the toy-like punch of a miniature.

Vignette (0 to 1.5)
:   Darkens the corners of the screen.

## DEPTH OF FIELD

The game's own depth of field, with your distances.

Blur
:   Turns the game's depth of field on and off.

Far Radius (0 to 1.5)
:   How strongly the distance is blurred.

Far Start (5 to 3000 m), Far End (10 to 6000 m)
:   Where the far blur begins and where it reaches full strength.

Near Radius (0 to 1.5), Near End (0 to 200 m)
:   The same for the foreground. The game's near blur shows little or nothing in many
    views.

## COLOUR GRADE

The game's own colour grading, with your values.

Grade
:   Turns the colour grade on and off.

Saturation (0 to 3), Contrast (0.5 to 2), Gamma (0.5 to 2), Gain (0.5 to 2)
:   The grade itself.

Reassert Every Frame
:   The game can put its own grade back while you play. With this on, your grade is applied
    again every frame.

## POST

Brightness (0.5 to 2), Sharpness (0 to 3)
:   The game's own brightness and sharpening.

## LENS + CAMERA

Camera Distance (off, or 1 to 200 m)
:   Lets the orbit camera pull back much further than the game allows, for the classic
    miniature view from high above. Applies to third person on foot and to a vehicle's
    outside camera; cab cameras keep their own distance.

FoV Override, FoV (10 to 110 degrees)
:   Replaces the camera's field of view. A narrow field of view flattens the scene like a
    long lens.

Shift X, Shift Y (-0.5 to 0.5)
:   Lens shift: slides the picture sideways or up and down without turning the camera, as
    the shift of a tilt-shift lens does.

Orthographic, Ortho Height (5 to 400 m)
:   A view with no perspective at all, like an architect's model. Ortho Height is how many
    metres of the world fit on the screen from top to bottom.

## WEATHER

Rain, snow and hail drawn into the miniature, so they blur along with it. The game's own
rain is not part of the picture the effect works on, so the mod draws its own.

Precipitation
:   Turns the mod's rain, snow and hail on and off.

Follow Sky
:   Follows the live weather: it rains in the miniature when it rains in the game,
    including the change from one weather to the next. Turn it off to set the amounts
    yourself.

Rain, Snow, Hail (0 to 2)
:   How much of each falls when Follow Sky is off.

Wind Drift (-2 to 2)
:   How far the wind blows the precipitation sideways. Negative values blow it the other
    way.

Fall Speed (0.1 to 4)
:   How fast it falls. 1 matches the game's own rain.

Blur Blend (0 to 4)
:   How strongly the precipitation melts into the blur and bokeh.

## STOP MOTION

Frame Limit
:   Caps the frame rate for a stop-motion feel.

Target FPS
:   8, 10, 12, 15, 24 or 30 frames per second.
