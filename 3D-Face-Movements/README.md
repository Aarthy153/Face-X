# 3D-Face-Movements

## Project Intro
<p>3D face tracking using **Blender**and **OpenCV** is a technique used to detect and track a face in a video stream and create a 3D model of the face. Blender is used to create the 3D model based on the facial features detected by OpenCV, which provides computer vision tools for face detection, landmark detection, and camera calibration. This technique has various applications in fields such as entertainment and biometrics.</p>

--- 
## Working of the Project
- ***Face detection*** : This is the process of locating a face in an image or video frame. OpenCV provides several pre-trained models for face detection, such as the Haar Cascade classifier.

- ***Facial feature detection*** : Once the face is detected, the next step is to locate the facial features such as eyes, nose, mouth, etc. OpenCV provides several pre-trained models for facial landmark detection, such as the dlib library.

- ***3D face model construction*** : In this step, a 3D face model is constructed based on the detected facial features. Blender provides a powerful 3D modeling environment that can be used to create a 3D face model.

- ***Camera calibration*** : The next step is to calibrate the camera used to capture the video stream. This involves determining the intrinsic and extrinsic parameters of the camera.

- ***Pose estimation*** : Once the camera is calibrated, the next step is to estimate the pose of the face in 3D space. This can be done by using the detected facial landmarks and camera calibration parameters.

- ***Face tracking*** : Finally, the 3D face model is tracked as the subject moves their head. This can be done by using the estimated pose and updating the position of the 3D face model in the Blender environment.

---
## - Installation of Dependencies'

* Download [Blender](https://www.blender.org/download/)
* Install Requirement Modules

      pip install opencv-python

      pip install numpy

      pip install bpy

---

## Run the Project

Follow the below command to run the project :

  python run OpenCVAnimOperator.py

  python run OpenCVAnim.py

---
### Final Result

![Alt Text](3D-Face-Movements.gif)
