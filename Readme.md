**🖐️ Sign Language Detection (A, B, C)**
📌 Project Overview

This project is a real-time Sign Language Detection System built using Python, OpenCV, and MediaPipe.
It captures hand gestures through a webcam and detects specific sign language alphabets.

Currently, the model is trained to recognize three alphabets: A, B, and C.
👉 Training all 26 alphabets was avoided because of system compatibility and performance constraints.

**🚀 Features**

✅ Real-time gesture recognition using webcam
✅ Detects A, B, C alphabets from sign language
✅ Uses MediaPipe Hands for keypoint extraction
✅ Lightweight and fast (runs smoothly on local machine)
✅ Scalable: Can be extended to detect more alphabets


**🛠️ Tools & Technologies Used**
1.Python 3.9+
2.OpenCV – for video frame processing
3.MediaPipe – for hand tracking & keypoint extraction
4.NumPy – numerical computations
5.Pandas – dataset handling
6.Scikit-learn – model training utilities
7.Keras / TensorFlow – deep learning model

**📂 Project Structure**
signlangdetect/
│-- app.py             # Main application file (runs detection using webcam)
│-- function.py        # Helper functions (MediaPipe processing, keypoints, etc.)
│-- trainmodel.py      # Script for training the model
│-- model.json         # Model architecture (saved in JSON format)
│-- model.h5           # Model weights
│
├── image/             # Stores sample images
├── Logs/              # Training logs (if any)
├── MP_Data/           # Processed dataset (keypoints for training)
├── sign/              # Virtual environment folder


**▶️ How to Run the Project**
1.Install Python 3.9+ on your system.
2.Open Command Prompt in the project folder and create a virtual environment:python -m venv sign
**3.Activate the virtual environment:**
sign\Scripts\activate     # Windows
source sign/bin/activate  # Linux/Mac
4.Install required dependencies:pip install numpy pandas scikit-learn opencv-python mediapipe tensorflow keras
**5.Run the project:python app.py**
6.A webcam window will open.
Show A, B, or C sign to the camera
The recognized alphabet will be displayed on the screen
Press Q to quit

**📸 Demo:(must see)**
My model is trained on three alphabets (A, B, C). Below are sample demos:
for A  ![image alt](https://github.com/himanshutiwri/sign-language-detection/blob/main/Screenshot%202025-09-29%20222838.png?raw=true)
for B ![image alt](https://github.com/himanshutiwri/sign-language-detection/blob/main/Screenshot%202025-09-29%20222955.png?raw=true)
for C [image alt](https://github.com/himanshutiwri/sign-language-detection/blob/main/Screenshot%202025-09-29%20223030.png?raw=true)



**💡 Key Highlights**

1.Learned how to use MediaPipe for hand landmark detection

2.Understood how to preprocess gestures into keypoint datasets

3.Built and trained a deep learning model for sequence classification

4.Implemented real-time prediction using webcam feed

5.Experienced working with model serialization (model.json, model.h5)

6.Explored challenges of hardware limitations (training only on 3 alphabets due to system constraints)


✨ This project is a small step towards making communication easier for the hearing-impaired.
