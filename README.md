# Face-Detection
Face Detection using OpenCV

This project uses OpenCV’s Haar Cascade classifier to perform real-time face detection with a webcam.

📂 Project Structure
.
├── face_det.py                  # Main script for face detection
├── haarscade_frontface_default.xml  # Haar Cascade model file
└── README.md                    # Documentation

⚙️ Requirements

Python 3.7+

OpenCV library (cv2)

Install dependencies:

pip install opencv-python

▶️ Steps to Run

Clone the repository

git clone https://github.com/your-username/face-detection.git
cd face-detection


Ensure files are in the same directory

face_det.py

haarscade_frontface_default.xml

Run the script

python face_det.py


Usage

The webcam will open.

A green rectangle will be drawn around detected faces.

Press Esc to exit.

📌 Notes

Ensure your webcam is connected and accessible.

You can adjust detection sensitivity by modifying parameters inside:

faces = face_cascade.detectMultiScale(gray, 1.5, 4)


First value → scale factor (default: 1.5)

Second value → min neighbors (default: 4)
