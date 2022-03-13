# Tracking-mouse
Tracking a mouse cursor with Kalman filter.

Our demo will implement the following sequence of operations:
  1. Start by initializing a black image and a Kalman filter. Show the black image in a window.
  2. Every time the windowed application prcosses input events, use the Kalman filter to predict the mouse's position.
     Then, correct the Kalman filter's model based on the actual mouse coordinates. On top of the black image, draw a red
     line from the old predicted position to the new predicted position, and then draw a green line from the old actual position
     to the new actual position. Show the drawing in the window.
  3. When the user hits the <i>Esc</i> key, exit and save the drawing to a file.

