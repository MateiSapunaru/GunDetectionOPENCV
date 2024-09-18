This project detects the presence of guns in a video feed using a pre-trained Haar Cascade classifier and OpenCV. When a gun is detected, the program highlights it with a rectangle and displays the frame with a timestamp.
Requirements

To run this project, the following libraries are needed:

    opencv-python
    imutils
    matplotlib


How It Works

  The webcam captures frames in real-time.
  Each frame is converted to grayscale.
  A pre-trained Haar Cascade (cascade.xml) is used to detect guns in the frame.
  If a gun is detected, the frame is highlighted, and the detection is logged.
  The program breaks the loop and displays the detected gun.
