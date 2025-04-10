# 👤 Face Recognition System using Machine Learning

This project is a **real-time face recognition system** built using **Python**, **OpenCV**, and machine learning techniques. It allows users to detect and recognize faces through live video streams and can be used for applications like **attendance systems**, **security monitoring**, and more.

---

## 🚀 Features

- 🎥 Real-time face detection using OpenCV  
- 🧠 Face recognition from live video feed  
- 🗂️ Add and manage known faces dataset  
- 🧬 Face encoding and matching  
- 🛠️ Simple, modular structure for training and recognition  

---

## 🛠️ Technologies Used

- **Python**  
- **OpenCV**  
- **face_recognition** (dlib-based)  
- **NumPy**  
- **Pickle**

---

## 📁 Project Structure

```
face_recognition-main/
│
├── dataset/                # Stores images of known individuals
├── encodings/              # Stores encoded face data
├── output/                 # Stores output videos (optional)
│
├── detect_faces.py         # Script to detect and collect face data
├── train_model.py          # Script to encode faces from dataset
├── recognize_video.py      # Script to recognize faces in real-time video
├── recognize.py            # Script for image-based recognition
├── requirements.txt        # Python dependencies
└── README.md               # Project documentation (this file)
```

---

## ✅ How to Use

1. **Install dependencies**  
   ```bash
   pip install -r requirements.txt
   ```

2. **Collect face data**  
   Run the script and enter names to label the face images:
   ```bash
   python detect_faces.py
   ```

3. **Train the model**  
   This will encode faces and save them:
   ```bash
   python train_model.py
   ```

4. **Recognize faces via webcam (real-time):**  
   ```bash
   python recognize_video.py
   ```

5. **Recognize faces in static images (optional):**  
   ```bash
   python recognize.py
   ```

---

## 💡 Notes

- Make sure your **webcam is working** for live recognition.
- Store **clear, front-facing images** in `dataset/` for better accuracy.
- You can **add more faces** to `dataset/` at any time and **retrain the model**.

---

## 📬 Contribution

Pull requests are welcome!  
For major changes, please open an issue first to discuss what you’d like to modify.

---
