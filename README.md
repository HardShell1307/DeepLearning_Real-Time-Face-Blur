# Real-Time Face Blur

Real-Time Face Blur is a Python script that uses OpenCV to capture video from a webcam and apply a Gaussian blur to any detected faces in real-time. It can be used for privacy protection when streaming video or for any application where real-time face blurring is needed.

## Features

- Real-time face detection and Gaussian blur application.
- Displays a text message when no faces are detected in the video stream.
- Option to draw bounding boxes around detected faces (commented-out by default).

## Requirements

- Python 3.x
- OpenCV (cv2) library

## Installation

1. Clone the repository:
```bash
git clone https://github.com/your-username/real-time-face-blur.git
cd real-time-face-blur
```
2.Install the required libraries:
```bash
pip install opencv-python
```
3.Run the script :
```bash
python main.py
```

## Usage 
- Make sure your webcam is connected to the computer.
- A window titled "Face Blur" will open, showing the real-time video stream with face blurring.
- Press the 'q' key to exit the program.

## Customization
- You can customize the appearance of the text message displayed when no face is detected:
- Open the main.py file in a text editor.
- Locate the line with the 'No Face Found!' text:
```bash
cv2.putText(img, 'No Face Found!', (20, 50), cv2.FONT_HERSHEY_SIMPLEX, 1, (0, 0, 255), 2)
```
- Modify the text, font, color, and other parameters as desired.

## Acknowledgments
- The face detection functionality is implemented using the Haar Cascade classifier provided by OpenCV.

## Contributing
- Contributions are welcome! If you have any suggestions, improvements, or bug fixes, please feel free to open an issue or submit a pull request.

## Disclaimer
- This script is intended for educational and demonstration purposes only. Make sure to comply with privacy laws and regulations when using this or similar software in real-world applications.

## Enjoy real-time face blurring with OpenCV!
