# Color Detection OpenCV Project 
This is a simple color detection project implemented using the OpenCV library. It allows you to detect and track colors in real-time using a computer's webcam.

Prerequisites
Before running the project, ensure you have the following dependencies installed:

Python 3.7

OpenCV

NumPy

# Usage
1 - Modify the color_detection.py script to include the colors you want to detect. Update the myColors list in the script with the desired colors. Each color should be specified as a BGR (Blue, Green, Red) value.

2 - The webcam will start capturing video, and a separate window will open displaying the live video feed.

3 - The script will detect the specified colors in real-time and draw rectangles around the detected objects of those colors.

# Customization

You can customize the project by modifying the color_detection.py script. Some possible modifications include:

Adding or removing colors: Modify the myColors list in the script to include the colors you want to detect. Each color should be specified as a BGR (Blue, Green, Red) value.

Changing the video source: By default, the script captures video from the webcam. If you want to use a different video source, you can modify the cv2.VideoCapture() function in the script accordingly.

Modifying the rectangle parameters: The script already includes code to draw rectangles around the detected colors. You can modify the rectangle parameters, such as line thickness or color, in the script's draw_rectangles() function.

# License
This project is licensed under the MIT License. Feel free to use and modify it according to your needs.
