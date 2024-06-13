# Monocular-Camera-Calibration-and-Distance-Measurement

**Introduction**: This project involves calibrating a monocular camera using a checkerboard pattern and then using the calibrated camera to compute distances from the checkerboard. The checkerboard's known size and structure make it ideal for learning and applying camera calibration techniques.

**Prerequisites**
  Software Requirements
    Python 3.x
    OpenCV library
    NumPy library
  Hardware Requirements
    Monocular camera (e.g., a webcam)
    
**Calibration Process**
  Checkerboard Pattern
    The checkerboard pattern used has a known size and square width, essential for the calibration process.
  Intrinsic Calibration
    Intrinsic calibration involves finding the distortion parameters of the camera, including the focal length, optical center, and distortion coefficients.

**Steps to Perform Calibration**
  Capture multiple images of the checkerboard from different angles.
  Detect the corners of the checkerboard in each image.
  Use the detected corners to compute the camera matrix and distortion coefficients.
  
**Pose Estimation**
  Checkerboard Pose Detection
    Using the intrinsic parameters obtained from calibration, detect the pose of the checkerboard. This involves determining the rotation and translation vectors that map the checkerboard        from the camera's perspective.
