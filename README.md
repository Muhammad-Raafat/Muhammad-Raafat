# Head-Pose-Estimation
The objective of this project is to obtain real-time head pose estimation using '2D' landmarks, as opposed to 3D landmarks. Traditionally, this has been accomplished through a fitting technique that involves matching 2D points with a 3D face model. However, this approach is not entirely deterministic and has its limitations. In order to address these challenges, we are leveraging machine learning to replace the need for the 3D fitting assumption, as well as the camera parameters and projection equations.

### Steps:

1- Imports Libraries

2- Get Paths of all images

3- Get Landmarks and angels from images and save them in csv file

4- Read and Perpare Data

5- Train models for each angels

6- using GridSearch and Multioutput Regressor with SVR

7- test and improve model to make best fit

### Libraries:

1- mediapipe

2- cv2

3- numpy

4- pandas

5- mat4py

6- math

