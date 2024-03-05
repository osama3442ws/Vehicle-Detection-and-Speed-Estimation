# Vehicle-Detection-and-Speed-Estimation

In this tutorial, we will review the concept of VASCAR, a method that police use for measuring the speed of moving objects using distance and timestamps. We’ll also understand how here is a human component that leads to error and how our method can correct the human error.

From there, we’ll design our computer vision system to collect timestamps of cars to measure speed (with a known distance). By eliminating the human component, our system will rely on our knowledge of physics and our software development skills.

Our system relies on a combination of object detection and object tracking to find cars in a video stream at different waypoints. We’ll briefly review these concepts so that we can build out our OpenCV speed estimation driver script.

Finally we’ll deploy and test our system. Calibration is necessary for all speed measurement devices (including RADAR/LIDAR) — ours is no different. We’ll learn to conduct drive tests and how to calibrate our system.
