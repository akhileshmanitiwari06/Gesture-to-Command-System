# Gesture-to-Command-System
AI that recognizes your gestures via webcam and maps them to system commands (play, pause, next, scroll, etc.)

🎯 Goal

AI that recognizes your gestures via webcam and maps them to system commands (play, pause, next, scroll, etc.)

💡 Use Case

Contactless control for media players, presentations, etc.

🧩 Architecture

Camera Input (live feed).

Hand Landmark Detection (MediaPipe Hands).

Gesture Classification (train ML model on hand poses).

Action Trigger (system automation using PyAutoGUI).

⚙️ Tech Stack

Python, OpenCV, MediaPipe (hand detection)

Scikit-learn / TensorFlow (gesture classification)

PyAutoGUI (system control)

Tkinter/Streamlit (interface)

🚀 Steps

Capture hand landmarks → store as dataset.

Train ML model to recognize gestures.

Map gestures → actions (volume up, scroll, next slide).

Real-time detection loop to trigger commands instantly.
