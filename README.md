# Sports Celebrity Image Classifier

This project is a web application that identifies sports celebrities from uploaded images. It uses a machine learning model trained with SVC (Support Vector Classifier) and OpenCV Haarcascades, achieving an accuracy of 90%. The app recognizes five sports celebrities:
- Lionel Messi
- Maria Sharapova
- Roger Federer
- Serena Williams
- Virat Kohli

## Features
- **Image Upload**: Upload a single image using a drag-and-drop interface powered by Dropzone.js.
- **Backend**: Flask-based backend for image classification.
- **Frontend**: A clean and responsive web page built with HTML, CSS, and JavaScript.
- **Result Display**: Shows the most probable match along with classification scores for each celebrity.
- **Model Performance**: Utilizes OpenCV Haarcascades for face detection and an SVC model for classification.

## How It Works
1. Users upload an image through the web interface.
2. The backend processes the image, detects faces, and classifies the detected faces using the trained model.
3. Results are returned and displayed in the frontend with probability scores.

## Setup Instructions
### Prerequisites
- Python 3.6+
- Flask
- OpenCV
- scikit-learn
- Numpy

