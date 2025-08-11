# 📸 Face Recognition Using Python

A real-time face recognition system built with **Python**, **OpenCV**, and the **face_recognition** library.

It detects and recognizes faces from a webcam stream, labels known faces, and marks unknown ones.

---

## ✨ Features
✅ Real-time face detection from webcam  
✅ Recognizes faces from stored images in `faces/` folder  
✅ Draws bounding boxes & labels  
✅ Works with `.jpg`, `.jpeg`, `.png`, and `.jfif` images  

---

## 🖼 How It Works
- Encodes all known faces from the faces/ folder.
- Captures frames from the webcam in real-time.
- Detects faces within each frame using the face_recognition library.
- Compares detected faces against stored encodings.
- Labels recognized faces with their names and draws bounding boxes.
- Marks unrecognized faces as "Unknown".  


---


## 📌 Notes
 - 💡 Good lighting greatly improves detection accuracy.
 - 📷 Use high-resolution, clear, front-facing images for best results.
 - 🖼 Keep one face per image in the faces/ folder for more accurate recognition.
 - ⚡ Processing speed depends on your system’s CPU/GPU performance.


  ---

  
## 📦 Requirements
Install dependencies:
```bash
pip install opencv-python face_recognition numpy imutils
