# Air Canvas
Air Canvas is an innovative computer vision-based application that enables users to draw on a virtual canvas using hand gestures. Developed as a minor project by students of the CSE branch, CS-2 section, at Shri Ram Institute of Technology, under the guidance of Prof. Ruchi K Patel, this project leverages the power of OpenCV and MediaPipe libraries for accurate hand detection and tracking.

## Features

- Gesture-Based Drawing: Draw freely on a virtual canvas using natural hand movements. 
- Multi-Color Support: Choose from a palette of colors including blue, green, red, yellow, and pink for your artistic creations. 
- Canvas Clearing: Easily clear the entire canvas with a simple hand gesture. 
- Save Functionality: Preserve your artwork by saving the canvas drawing as an image file on your local machine. 
- Real-time Processing: Experience smooth and responsive drawing with real-time hand tracking and gesture recognition. 
- User-Friendly Interface: Intuitive design makes it easy for users of all skill levels to create digital art. 
 
## Prerequisites
Before you begin, ensure you have the following installed:

- Python 3.7 or higher 
- OpenCV (cv2) : for computer vision
- MediaPipe    : for hand tracking
- NumPy        : for numerical computing

## Installation

Clone the repository to your local machine:

```bash
git clone https://github.com/Yogesh061202/Air_Canvas.git
```

Navigate to the project directory:

```bash
git Copycd Air_Canvas
```

Install the required dependencies:

```bash
pip install opencv-python mediapipe numpy
```


## Usage

Start the application by running:

```bash
python Air_Canvas.py
 ```

Once the application window opens, you'll see two main areas:

- The webcam feed on the left
- The virtual canvas on the right


## Drawing Instructions:

Raise your hand in front of the webcam.
Use your index finger to draw on the canvas.
Move your hand to the top of the screen to access the color selection menu.


### - Color Selection:

Hover your finger over the color buttons at the top of the screen to change drawing colors.
Available colors: Blue, Green, Red, Yellow, and Pink.


### - Clearing the Canvas:

To clear the entire canvas, hover your finger over the "CLEAR" button located at the top-right corner of the canvas.


### - Saving Your Artwork:

Press the "S" key on your keyboard while the application is running to save your current canvas as an image file.
The image will be saved in the project directory with a timestamp in the filename.


### - Exiting the Application:

Press the "Q" key to quit the application.


### - Troubleshooting

If the hand detection is not working properly, ensure you have adequate lighting and a clear background.
Ensure your hand is visible in the webcam feed for optimal tracking.

## Future Enhancements

- Implement brush size adjustment feature
- Add more drawing tools (e.g., shapes, text)
- Introduce a gallery to browse and edit previous drawings
- Develop collaborative drawing features for multiple users

## Contribution
We welcome contributions to improve Air Canvas! If you'd like to contribute:

- Fork the repository
- Create a new branch 
```bash
git checkout -b feature/AmazingFeature
```
- Commit your changes
```bash
git commit -m 'Add some AmazingFeature'
```
- Push to the branch 
```bash
git push origin feature/AmazingFeature
```
- Open a Pull Request

Please ensure your code adheres to the project's coding standards and includes appropriate documentation for new features.

## Acknowledgements

Shri Ram Institute of Technology for providing the platform and resources for this project.
Prof. Ruchi K Patel for her valuable guidance and support throughout the development process.
The OpenCV and MediaPipe teams for their excellent libraries that made this project possible.

## Contact
For any queries or suggestions, please contact:

- Project Maintainer: Yogesh - yogeshjharbade0612@gmail.com
- GitHub Repository: https://github.com/Yogesh061202/Air_Canvas

Thank you for your interest in Air Canvas! We hope you enjoy creating art in the air!
