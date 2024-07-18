# Virtual-Strokes-World
virtual-Strokes World is a real-time drawing application that allows users
to create digital artwork using hand gestures captured by a webcam. The
project utilizes computer vision techniques to detect and track the user's
hand movements, translating them into drawing commands on a virtual
canvas. The application provides a user-friendly interface where users can
select different colors and brush sizes, enabling them to draw with ease and
precision.

Algorithm :

Start reading the frames and convert the captured frames to HSV colour space.(Easy for colour detection)
Prepare the canvas frame and put the respective ink buttons on it.
Adjust the values of teh mediapipe intilization to detect one hand only.
Detect teh landmarks by passing the RGB frame to the mediapipe hand detector
Detect the landmarks, find the forefinger coordinates and keep storing them in the array for successive frames .(Arrays for drawing points on canvas)
Finally draw the points stored in array on the frames and canvas .
Requirements: python3 , numpy , opencv, mediapipe installed on your system.
