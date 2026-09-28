# Face Recognition System

A Python project that detects and recognizes faces from images and live webcam video. Built using [OpenCV] and [face_recognition library], developed in PyCharm.

## Features
- Detects faces in real time using webcam
- Recognizes known faces and labels them with names
- Marks unknown faces as "Unknown"
- [Optional: Records attendance in a CSV/Excel file with date and time]
- [Optional: Works on both images and video]

## Tech Stack
- Language: Python 3.[x]
- Libraries: OpenCV, face_recognition, NumPy, [pandas]
- IDE: PyCharm

## How It Works
1. Images of known people are stored in the `images/` folder.
2. The program encodes each face into a numerical face encoding.
3. The webcam captures frames, detects faces and compares their encodings with the known ones.
4. The closest match is displayed with the person's name on the video feed.

## Project Structure

## Installation
```bash
git clone https://github.com/devanshisrivastava08/face-recognition-python.git
cd face-recognition-python
pip install -r requirements.txt
python main.py
```

## Usage
- Add clear, front-facing photos of people in the `images/` folder (file name = person's name).
- Run `main.py`. Press `q` to quit the webcam window.

## Future Improvements
- Improve accuracy in low light
- Add a GUI
- [Add database / attendance dashboard]

## Author
Devanshi Srivastava
B.Tech ECE, MMMUT Gorakhpur
[LinkedIn](https://www.linkedin.com/in/devanshi-srivastava-85638a309)
