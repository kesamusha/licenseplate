# License Plate Detection with OpenCV

This project demonstrates a simple real-time license plate detection system using Python and OpenCV.  
It leverages Haar Cascade classifiers to detect license plates from a webcam feed.

---

## Features
- Real-time video capture from the webcam.
- Detects license plates using Haar Cascade (`haarcascade_russian_plate_number.xml`).
- Draws bounding boxes around detected plates.
- Labels detected plates with text.
- Press **'q'** to quit the application.

---

## How It Works
1. The program loads a pre-trained Haar Cascade classifier for Russian license plates.
2. Captures frames from the webcam using `cv2.VideoCapture(0)`.
3. Converts each frame to grayscale for detection.
4. Applies `detectMultiScale` to locate license plates.
5. Draws rectangles and labels around detected plates.
6. Displays the processed video stream in a window.

---

## Example Usage
```bash
$ python license_plate_detection.py
🚗 License Plate Detection Started... Press 
