# HAND::WIRE

HAND::WIRE is a single-page browser experiment that uses your webcam to track your hand in real time and render it as a glowing wireframe.

## How to Use

1. Open `hand-wireframe.html` in a browser.
2. Allow camera access when the browser asks.
3. Put your hand in view of the camera.
4. Move your hand closer to the camera and extend your index finger to enter draw mode.
5. Trace shapes with your index fingertip. Move back or leave draw mode to commit the shape.
6. Press `C` to clear all drawn shapes.

The HUD shows live FPS, detected hands, tracking confidence, landmark coordinates, and proximity. The app runs locally in the browser, but it loads MediaPipe and font assets from public CDNs, so an internet connection is required.
