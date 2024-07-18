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

![WhatsApp Image 2024-07-18 at 20 51 25_5f60226d](https://github.com/user-attachments/assets/8c52e95c-1478-4518-a654-ae2606cfd25f)


