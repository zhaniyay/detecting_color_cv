Summary

This project demonstrates how to detect a specific color (yellow) in real-time using a webcam feed. The application uses OpenCV and PIL libraries to process frames and highlight areas containing the target color.

How It Works

Opens the webcam and captures video frames.

Converts each frame from BGR to HSV color space for easier color detection.

Calculates the HSV range for the color yellow.

Creates a binary mask to isolate areas of the frame containing the target color.

Detects the bounding box around the detected yellow area using PIL.

Draws a rectangle around the detected area in the original frame.

Displays the result in a window.

Ends the application when the user presses 'q'.

