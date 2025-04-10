Face Recognition System using Machine Learning
This project is a real-time face recognition system built using Python, OpenCV, and machine learning techniques. It allows users to detect and recognize faces through live video streams and can be used for applications like attendance systems, security monitoring, and more.

🚀 Features
Real-time face detection using OpenCV

Face recognition from live video feed

Add and manage known faces dataset

Face encoding and matching

User-friendly structure for training and recognition

🛠️ Technologies Used
Python

OpenCV

face_recognition (dlib-based)

NumPy

pickle

📁 Project Structure
bash
Copy
Edit
face_recognition-main/
│
├── dataset/                # Stores images of known individuals
├── encodings/              # Stores encoded face data
├── output/                 # Stores output videos (optional)
├── detect_faces.py         # Script to detect and collect face data
├── train_model.py          # Script to encode faces from dataset
├── recognize_video.py      # Script to recognize faces in real-time video
├── recognize.py            # Script for image-based recognition
└── requirements.txt        # Python dependencies
✅ How to Use
Install dependencies:

bash
Copy
Edit
pip install -r requirements.txt
Collect face data:

Run the following command and enter names to label the face images:

bash
Copy
Edit
python detect_faces.py
Train the model:

This will generate face encodings and save them for recognition:

bash
Copy
Edit
python train_model.py
Recognize faces via webcam (video feed):

bash
Copy
Edit
python recognize_video.py
Recognize faces in static images (optional):

bash
Copy
Edit
python recognize.py
💡 Notes
Ensure your webcam is working for live recognition.

Store clear, front-facing images for best results during face encoding.

You can add more individuals to the dataset/ folder anytime and retrain the model.

📬 Contribution
Pull requests are welcome. For major changes, please open an issue first to discuss what you would like to change.
