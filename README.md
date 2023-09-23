# Drowsiness-detection
Evaluates if a driver's eyes is open or closed in real time. 


# How It's Made
Tech Used: YOLOv5, OpenCV, Pytorch, Python, Jupyter Notebooks

This project is performs real-time object detection by using the Common Objects in Context COCO dataset to identify human faces determine whether the eyes are open or closed. The application utilizes OpenCV to capture real-time video frames, and the frames are then processed by the YOLOv5 trained model to detect faces and eye states.

The core component of the application is a loop that constantly reads frames from the webcam, makes detections on those frames, and then renders the results. This loop reads frames from the webcam until the user presses 'q'.

# Optimizations
Optimizations were made throughout development to ensure efficient and real-time performance. Frame reading and rendering were managed to avoid any lag or delay in displaying the real-time detections. The model was refined and tuned to offer accurate detections with minimal false positives/negatives. Assets and models were optimized and loaded efficiently to ensure quick startup and response times.

# Lessons Learned
Balancing Accuracy and Performance: Achieving a balance between detection accuracy and real-time performance was a crucial lesson. It required constant iteration, testing, and tuning to ensure that the model was accurate without compromising the application’s responsiveness.

Integration Challenges: Integrating various technologies and libraries such as OpenCV, Pytorch, and YOLOv5 had its own set of challenges, which emphasize importance of understanding the compatibility between different tech stacks.

# Acknowledgements
A big thank you to the open-source community for providing valuable resources, libraries, and frameworks that made the development of this project possible. The contributions from the developers of YOLOv5, OpenCV, and PyTorch have been instrumental in bringing this project to fruition.
