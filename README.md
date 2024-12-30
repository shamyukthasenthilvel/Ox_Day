# Hand-Gesture Presentation Control

This project is a hand-gesture-controlled presentation system built using Python, OpenCV, and the CVZone library. It allows users to navigate through slides, annotate on them, and interact with the presentation using simple hand gestures.

---

## Features

1. **Gesture Recognition:**
   - Swipe left (thumb up) to move to the previous slide.
   - Swipe right (little finger up) to move to the next slide.
   - Draw annotations on slides using the index finger.
   - Undo the last annotation by showing the middle, ring, and little fingers.

2. **Real-Time Display:**
   - Shows the live camera feed in a small corner of the presentation slide.

3. **Annotation Capabilities:**
   - Draw and save annotations directly on the slides.

4. **Slide Navigation:**
   - Navigate through slides in the specified folder (`folderPath`).

---

## Requirements

- Python 3.7+
- OpenCV
- Numpy
- CVZone Library

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/yourusername/Hand-Gesture-Presentation-Control.git
   cd Hand-Gesture-Presentation-Control
   ```

2. Install the required packages:
   ```bash
   pip install -r requirements.txt
   ```

3. Ensure you have a folder containing presentation images. Update the `folderPath` variable in the script to the path of this folder.

---

## Usage

1. Run the script:
   ```bash
   python main.py
   ```

2. Use the following gestures to control the presentation:
   - **Left Swipe (Thumb Up):** Move to the previous slide.
   - **Right Swipe (Little Finger Up):** Move to the next slide.
   - **Index Finger Up:** Draw annotations on the slide.
   - **Three Fingers Up (Middle, Ring, Little):** Undo the last annotation.

3. Press `q` to exit the application.

---

## Folder Structure

```
Hand-Gesture-Presentation-Control/
├── main.py               # Main script
├── requirements.txt      # Dependencies
├── Presentation/         # Folder containing presentation images
└── README.md             # Documentation
```

---

## Customization

- **Gesture Threshold:**
  Modify the `gestureThreshold` variable to adjust the detection height.

- **Presentation Images:**
  Add your presentation images to the folder specified in the `folderPath` variable.

- **Resolution:**
  Change the `width` and `height` variables to set the desired resolution for the camera feed.

---

## Troubleshooting

1. **No Images Found:**
   - Ensure the folder specified in `folderPath` contains valid image files.

2. **Camera Not Detected:**
   - Check if your webcam is connected and accessible.

3. **Gesture Recognition Issues:**
   - Adjust the `gestureThreshold` or ensure good lighting for better detection.

---

## Contributions

Contributions are welcome! Feel free to fork this repository and submit a pull request.

---

## License

This project is licensed under the MIT License. See the LICENSE file for details.

---

## Acknowledgments

- [CVZone](https://github.com/cvzone/cvzone) - Library for computer vision tasks.
- OpenCV - Real-time computer vision.

---

Happy Presenting! 🎉
