# Touch_gesture
Gesture detection library for the Arduino Giga Display.

Users can register various types of gesture within a defined region on the screen:
- tap
- long press
- drag
- swipe (a fast drag or flick)
- pinch without rotation (two scale factors) or with rotation (one scale and angle)

The example program draws a rectangle on the screen and responds to:
- taps in the box (draws circle where tapped)
- long presses in the box (draws filled circle)
- dragging the box around
- swiping to clear the screen and reset the box
- pinching of two kinds on the box

Dependencies:
- Giga GFX library
- Giga touch library
