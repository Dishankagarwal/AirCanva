# Project Title: AirCanva

## Description:
This project is a hand gesture-based drawing application that allows users to create digital artwork using hand movements tracked by a webcam. Leveraging computer vision techniques, this interactive application provides an intuitive and fun way to draw colorful patterns and designs on a canvas.

## Key Features:

- #### Hand Tracking: 
  The application utilizes the MediaPipe library to accurately track the user's hand movements in real-time.
- #### Gesture Recognition: 
  Users can interact with the drawing canvas by performing specific hand gestures. Key gestures include:
- #### Multiple Color Selection: 
  By positioning the hand over predefined color zones, users can switch between different colors (teal, yellow, purple, and green).
- #### Canvas Clear: 
  A "CLEAR" button gesture erases the canvas, providing a clean slate for new artwork.
- #### Drawing Canvas: 
  A canvas is displayed on the screen where users can draw with their hands. The application records and displays drawings in real-time.
- #### Flexible Drawing: 
  Users can draw freehand on the canvas by moving their hand in various directions, creating colorful strokes and patterns.
 
## Technical Stack:

- #### Python: 
  The project is implemented in Python, utilizing its extensive libraries and tools for computer vision and user interface development.
- #### OpenCV: 
  OpenCV is used for webcam access, video frame manipulation, and rendering.
- #### NumPy: 
  NumPy is employed for efficient array operations and data handling.
- #### MediaPipe: 
  MediaPipe is the backbone for hand tracking and landmark detection.
- #### Deque: 
  Deques are used for managing and storing the coordinates of drawing points.
- #### GitHub: 
  The project is hosted on GitHub, providing version control, collaboration, and code sharing.

## Usage:

This project can be used as an interactive educational tool, an art creation platform, or a demonstration of hand gesture recognition and computer vision concepts. Users can explore their creativity by drawing with their hands in a novel and engaging way.

## How to run?

### Prerequisites:

- Python installed on your system.
- Required Python libraries (OpenCV, NumPy, and MediaPipe) installed. You can install them using pip if not already installed.
  
### Instructions:

#### Clone the Repository:
- Open a terminal or command prompt.
- Navigate to the directory where you want to clone the project.
- Run the following command to clone the GitHub repository:
  
```bash
git clone https://github.com/imaayushisingh/hand-gesture-based-drawing-application.git
```

#### Navigate to the Project Directory:
- Change your working directory to the project folder:
  
```bash
cd hand-gesture-drawing-app
```

#### Install Dependencies:
- Ensure you have the required Python dependencies installed. You can install them using pip:

```bash
pip install opencv-python numpy mediapipe
```

#### Run the Application:
- Execute the Python script to run the drawing application:

```bash
python app.py
```

#### Interact with the Application:
- Once the application is running, your webcam feed should appear, and you can start using your hand gestures to draw on the canvas.
