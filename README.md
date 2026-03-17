# Age and Gender Detection using OpenCV and Deep Learning

This project performs **real-time age and gender prediction from webcam video or images** using computer vision and deep learning models.
The system detects human faces and then predicts the **gender and approximate age group** of each detected face.

The project uses **OpenCV's Deep Neural Network (DNN) module** with pretrained convolutional neural network models for face detection and demographic prediction.

---

## Features

* Detects faces from webcam video stream
* Predicts **gender (Male / Female)**
* Predicts **age group** of the detected person
* Displays results in real time on the video frame
* Uses pretrained deep learning models for inference

---

## Technologies Used

* Python
* OpenCV
* Deep Learning (CNN)
* NumPy

---

## Project Structure

```
age-gender-detection
│
├── main.py
├── age_deploy.prototxt
├── gender_deploy.prototxt
├── opencv_face_detector.pbtxt
├── requirements.txt
└── README.md
```

---

## Download Pretrained Models

Due to file size limits on GitHub, the model files are not included in this repository.
Download the following models and place them in the **same directory as `main.py`**.

Required model files:

* `age_net.caffemodel`
* `gender_net.caffemodel`

Download the required model files from the following links and place them in the project folder.
https://drive.google.com/drive/folders/1wVAN4XGMo0shQiEWAie0bet0OGm4supz?usp=drive_link


---

## Installation

1. Clone the repository

```
git clone https://github.com/yourusername/age-gender-detection.git
```

2. Navigate to the project folder

```
cd age-gender-detection
```

3. Install required libraries

```
pip install -r requirements.txt
```

---

## Running the Project

Run the following command:

```
python main.py
```

The webcam will open and the system will start detecting faces and predicting age and gender.

Press **q** to exit the application.

---

## How It Works

1. The system captures frames from the webcam.
2. A pretrained face detection model identifies faces in the frame.
3. Each detected face is processed using age and gender classification models.
4. The predicted **age group and gender** are displayed on the video feed.

---

## Possible Applications

* Retail customer analytics
* Demographic analysis
* Smart surveillance systems
* Interactive applications

---

## Future Improvements

* Improve prediction accuracy
* Support multiple face tracking
* Deploy as a web application
* Optimize performance for real-time systems

---

## Author

Lakshit Patel
