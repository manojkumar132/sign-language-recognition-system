# Sign Language Recognition System

This is a Sign Language Recognition System built using Python, OpenCV, MediaPipe, and TensorFlow.  
The system captures hand gestures through a webcam and recognizes the corresponding sign using a trained machine learning model.  
A graphical user interface (GUI) is implemented using CustomTkinter for easy interaction.

## 📌 Features

- Real-time hand gesture detection using webcam  
- Keypoint extraction using MediaPipe  
- Sign classification using a trained TensorFlow model  
- User-friendly GUI using CustomTkinter  
- Supports image and video-based recognition  
- Displays predicted sign output in real-time  

## 🛠️ Technologies Used

- Python  
- OpenCV  
- MediaPipe  
- TensorFlow / Keras  
- NumPy  
- Pillow  
- Tkinter & CustomTkinter  

## 📁 Project Structure

sign-language-recognition-system/

app.py  
requirements.txt  
model_train.ipynb  

assets/  
demo.mp4  
signs.png  

model/  
keypoint_classifier/  
keypoint_classifier.py  
coord.csv  
label.csv  
model.hdf5  
model.tflite 

## ⚙️ How to Run the Project
pip install -r requirements.txt


2. Run the application:


python app.py


The webcam will open and start detecting hand gestures.

## 🧠 Model Training

- Model training is done in the file: model_train.ipynb  
- Training data is stored in coord.csv  
- Labels are stored in label.csv  
- Final trained models:
  - model.hdf5  
  - model.tflite  

## 🎯 Use Case

- Helps hearing-impaired people communicate  
- Useful for learning sign language  
- Can be used in schools and training centers  

## 🚀 Future Improvements

- Add more sign classes  
- Improve accuracy  
- Add sentence formation  
- Add voice output  

## 👨‍💻 Author

Manoj Kumar J  
Department of Artificial Intelligence & Data Science  
Nitte Meenakshi Institution of Technology

1. Install all required libraries:
