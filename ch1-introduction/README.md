# Introduction

In robotics, two important branches are (1) state estimation and (2) control. This book focuses on state estimation.
+   The state of a robot is a set of quantities, such as position, orientation, and velocity.
+   The states can fully describe a robot's motion over time. 

# Two types of sensors
+   Interoceptive / Proprioceptive (stimuli arising within the body - velocity or acceleration)
    +   **Accelerometer** -> translation acceleration
    +   **Gyroscope** -> angular rate
    +   **Wheel odometer** -> angular rate
    +   **IMU** -> 3 linear accelerometers and 3 rate gyros
+   Exteroceptive (stimuli received by an organism from outside - position and orientation)
    +   **Cameras**
    +   Time-of-flight transmitter / receiver -> **laser**, **GPS**

# Other books
+   ***Probabilistic Robotics (2006) by Thrun***
    +   State estimation w.r.t. mapping and localization
    +   Robots operating in the 2D, horizontal plane
    +   Details of extending to 3D are not provided
+   ***Robotics, Vision, and Control (2011) by Corke***
    +   State estimation for robotics including 3D
    +   The breadth of this book necessitates that it not delve too deeply into state estimation
+   ***Many others***
    +   see the text

# Probability Preliminary

Bayes' rule, derived from joint probability definition:

![equation](https://latex.codecogs.com/svg.latex?p%28x%2C%20y%29%3Dp%28x%7Cy%29p%28y%29%20%3D%20p%28y%7Cx%29p%28x%29)

![equation](https://latex.codecogs.com/svg.latex?p%28x%7Cy%29%20%3D%20%5Cfrac%7Bp%28y%7Cx%29p%28x%29%7D%7Bp%28y%29%7D%3D%5Cfrac%7Bp%28y%7Cx%29p%28x%29%7D%7B%5Cint%20p%28y%7Cx%29p%28x%29dx%7D)

Some key notations in Bayesian inference:
+   **prior**: p(x)
+   **posterior**: p(x|y)

# How should I organize?
+   Not cover everything from beginning to end
+   Instead, focus on the methods directly, e.g. SVO, DSO, DSM, ORB-SLAM, and then reference to certain topics if necessary, then we only cover those needed in the references in detail





