📸 Face Recognition Using Python
A real-time face recognition system built with Python, OpenCV, and the face_recognition library.

It detects and recognizes faces from a webcam stream, labels known faces, and marks unknown ones.

✨ Features
✅ Real-time face detection from webcam
✅ Recognizes faces from stored images in faces/ folder
✅ Draws bounding boxes & labels
✅ Works with .jpg, .jpeg, .png, and .jfif images

📦 Requirements
Install dependencies:
pip install opencv-python face_recognition numpy imutils

🖼 How It Works
Encodes all known faces from faces/ folder.
Captures frames from webcam.
Compares detected faces with known encodings.
Labels matches or marks as "Unknown".

📌 Notes
Good lighting improves accuracy.
Use high-resolution, clear, front-facing images.
Works best with one face per reference image.
