# Virtual Paint with OpenCV

This Python application allows you to draw on a screen in real-time by tracking a colored object with your webcam. It uses computer vision techniques, primarily color detection, to create a virtual canvas.

---

## How It Works

The application captures video from a webcam, converts the video frames to the HSV color space to reliably detect a specific color, and then tracks the contour of that colored object. The position of the object's tip is used as a virtual paintbrush to draw on the screen.

---

## Requirements

* `opencv-python`
* `numpy`

You can install them using pip:
`pip install opencv-python numpy`

---

## How to Run

1.  Make sure you have a brightly colored object to use as a pen (the code is set up for colors like orange, green, and blue).
2.  Run the script from your terminal:
    ```bash
    python Virtual_Paint.py
    ```
3.  Hold the colored object in front of the camera to start drawing. Press 'q' to quit.
