Sign Language Gesture Detector
==============================

Project Overview:
-----------------
This is a simple **one-hand gesture detection project** using **MediaPipe Hands** and JavaScript. 
The app detects specific hand gestures and displays them in real-time. It uses your webcam to track hand movements
and overlays the detected hand landmarks on a canvas.

Current Gestures Detected:
--------------------------
1. Hello / Thank You 👋🙏  - Open palm, all fingers extended
2. Peace ✌️               - Index + Middle fingers up
3. Thumbs Up 👍            - Only thumb up
4. L Gesture ✋            - Thumb + Index fingers out
5. YO Gesture 🤟           - Index + Pinky fingers out

Setup & Running:
----------------
1. Open the project folder on your computer.
2. Make sure you have `index.html` and `style.css` in the same folder.
3. Open `index.html` in a modern browser (Chrome/Edge/Firefox recommended).
4. Allow the browser to access your camera when prompted.
5. The canvas will show your hand with landmarks, and the detected gesture will appear in the "Detected Sign" area.

How It Works:
-------------
- Uses **MediaPipe Hands** to detect 21 hand landmarks.
- Each finger is analyzed to determine if it is “up” or “down”.
- Specific **finger combinations** are matched to predefined gestures.
- The detected gesture is updated in real-time as you move your hand.

Future Improvements:
--------------------
- Add more gestures (e.g., numeric signs, emojis).
- Recognize gestures from both hands.
- Add movement-based gestures like waving or clapping.
- Integrate text-to-speech to “say” gestures out loud.

Author:
-------
Sairaj Naik

