# Face-Recognization-System

 ## Overview

This project is a Face Recognition System built using Python, OpenCV, and the `face_recognition` library. The system detects faces in an image, extracts facial embeddings, and compares them with a known reference face to identify whether the person is authorized or unknown.

The project demonstrates practical applications of Computer Vision, Image Processing, and Machine Learning in identity verification systems.

## Features

* Face detection from images
* Face encoding and feature extraction
* Face matching using facial embeddings
* Authorized vs Unknown person classification
* Bounding box visualization with labels
* Easy-to-use Python implementation

## Technologies Used

* Python
* OpenCV
* face_recognition
* NumPy
* Google Colab / Jupyter Notebook

## Project Structure

```text
Face-Recognition-System/
│
├── images/
│   ├── known_face.jpg
│   └── test_image.jpg
│
├── face_recognition_system.py
├── requirements.txt
├── README.md
└── output.png
```

## Installation

1. Clone the repository:

```bash
git clone https://github.com/yourusername/Face-Recognition-System.git
cd Face-Recognition-System
```

2. Install the required dependencies:

```bash
pip install -r requirements.txt
```

## Required Libraries

```bash
pip install opencv-python
pip install face-recognition
pip install numpy
```

## Usage

1. Place the reference image inside the project directory.
2. Provide the path of the known face image.
3. Provide the path of the image to be verified.
4. Run the script:

```bash
python face_recognition_system.py
```

## How It Works

1. Load the known reference image.
2. Generate facial encodings for the reference face.
3. Detect faces in the input image.
4. Generate facial encodings for detected faces.
5. Compare facial embeddings using distance metrics.
6. Label matching faces as **Authorized Person** and non-matching faces as **Unknown**.
7. Display the results with bounding boxes.

## Sample Output

* Green Bounding Box → Authorized Person
* Red Bounding Box → Unknown Person

(Add your project screenshot here)

## Applications

* Smart Attendance Systems
* Access Control Systems
* Security & Surveillance
* Identity Verification
* Visitor Management Systems

## Future Enhancements

* Real-time webcam recognition
* Multiple authorized users database
* Attendance logging using CSV/Excel
* Streamlit web application deployment
* Face mask and emotion detection
* Cloud deployment

## Learning Outcomes

Through this project, I gained practical experience in:

* Computer Vision
* Image Processing
* Facial Recognition
* OpenCV
* Python Development
* Machine Learning Applications

## Author

**Arogya Surannavar**

B.E. Computer Science & Engineering (Data Science)
New Horizon College of Engineering, Bangalore
