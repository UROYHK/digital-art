# digital-art
The project is a real-time virtual painting app that uses hand tracking via MediaPipe and OpenCV. The index finger acts as a brush to draw on a digital canvas. Users can change colors, use an eraser, clear the canvas, and save drawings—all by pointing at the webcam. The eraser size auto-adjusts based on finger distance. Ever wanted to paint without touching anything. This  project turns your webcam into a virtual canvas, where your hand becomes the brush. Just wave your hand in front of the camera, and draw using your index finger no mouse or touchscreen needed .It uses MediaPipe to track your hand and OpenCV to display and draw everything in real time. Your finger becomes the brush, and you can draw in different colors, erase, clear the canvas, or even save your masterpiece — all by pointing at buttons on the screen.

 -->Features
*Draw in real-time just by moving your index finger
*Switch between four colors: Blue, Green, Red, Yellow
*Use an eraser to remove parts of your drawing
*Adjust the eraser size by changing how far your thumb and index finger are
*Clear the whole canvas with one gesture
*Save your artwork as a PNG image with a timestamped name

-->Technologies Used
*Python
*OpenCV – to access your webcam and draw things on screen
*MediaPipe – to detect and track your hand in real time
*NumPy – to help with some calculations

-->How to Use It

* install the required Python libraries:
nginx
Copy
Edit
pip install opencv-python mediapipe numpy

*run the app:
nginx
Copy
Edit
python paint_app.py

*steps:
Move your index finger in front of the webcam to start drawing.
Point at the buttons on top of the screen to:
Change colors
Use the eraser
Clear the canvas
Save your drawing
To resize the eraser, just change the distance between your thumb and index finger.
Press 'q' anytime to exit the app.

*Where Does It Save My work?
Your drawings are saved in the same folder as the script, with names like:
Copy
Edit
painting_20250704_153000.png(with the  date and time you saved it.)

-->Tips for Best-Experience
Use it in a well-lit room so the camera can clearly see your hand.
A plain background (like a white wall) helps improve hand tracking.
Make sure your webcam is working before starting.

