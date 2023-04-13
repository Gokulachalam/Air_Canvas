# AIR CANVAS
The Air Canvas project is an interactive and immersive digital art platform that allows users to create and display artwork in a virtual environment using their body movements.

## PROJECT DESCRIPTION
The platform utilizes motion tracking technology to capture the user's movements and translate them into virtual brush strokes on a digital canvas. Users can choose from a variety of brush types and colors to create their artwork, and can also collaborate with others in real-time to create collaborative pieces.

One of the unique features of the Air Canvas project is its ability to display the artwork in a 3D environment, providing a more immersive and engaging experience for both the creator and the audience. The artwork can be viewed from multiple angles, and users can even walk around and explore the virtual space to get a closer look at the artwork.

## Libraries Used

* PYTHON3
* Numpy
* Open cv

# Steps Done

1.Install OpenCV: Install OpenCV library on your system. You can download and install OpenCV from the official website https://opencv.org/.

2.Set up the camera: Set up the camera or webcam that you will use to track the user's movements. You can use the OpenCV VideoCapture function to initialize the camera.

3.Create a canvas: Create a blank canvas using the OpenCV Mat function. You can specify the canvas size and color.

4.Track user's movements: Use the OpenCV functions for motion tracking to detect and track the user's movements. You can use functions such as cv2.findContours to detect the contours of the user's movements.

5.Draw on the canvas: Use the OpenCV functions for drawing to draw on the canvas. You can use functions such as cv2.circle or cv2.line to draw different shapes and strokes.

6.Display the canvas: Display the canvas in a window using the OpenCV imshow function.



