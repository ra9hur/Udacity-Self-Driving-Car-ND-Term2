# Udacity-Self-Driving-Car-ND-Term 2
To build the core robotic functions of an autonomous vehicle system: sensor fusion, localization and control. All projects are implemented using C++ as programming language.

GitHub repository links to Term 2 projects are as given below.

## Projects

-------------

**1. Bi-cycle Tracking using Extended Kalman Filters (EKF)**

![ekf](https://cloud.githubusercontent.com/assets/17127066/25771038/7c53935a-3263-11e7-8574-fd1fa97235d7.png)

Simulated lidar and radar measurements are provided to detect a bicycle that travels around the vehicle. EKF implementation uses the method called first order Taylor expansion to obtain linear approximation of the non-linear systems. 

Here is the link for the completed project - [SDC-P6-Extended-Kalman-Filter][1]

-------------

**2. Bi-cycle Tracking using Unscented Kalman Filters (UKF)**

![ukf](https://cloud.githubusercontent.com/assets/17127066/25771039/7c5a8d90-3263-11e7-8703-6bf2db5a957a.png)

As in project 1, simulated lidar and radar measurements are provided to detect a bicycle that travels around the vehicle. The Unscented Kalman Filter (UKF) is a novel development in the field. UKF implementation locates objects with better accuracy in highly non-linear systems. 

Here is the link for the completed project - [SDC-P7-Unscented-Kalman-Filter][2]

-------------

**3. Kidnapped Vehicle**

![particle_filter](https://cloud.githubusercontent.com/assets/17127066/26500210/b84170fe-4252-11e7-9ba7-fb149f03fb7b.png)

Implement a particle filter to take real-world data and localize a lost vehicle using,

- (noisy) GPS estimate of its initial location, 
- lots of (noisy) sensor and control data.

Here is the link for the completed project - [SDC-P8-Particle-Filter][3]

-------------

**4. Lane Keeping - PID Controller Project**

![pid-git](https://user-images.githubusercontent.com/17127066/27775891-da02bd5e-5fc3-11e7-8ed7-8e81138da41b.png)

Implement a PID Controller to race around the lake track and to keep a simulated vehicle in its lane. For an extra challenge, use computer vision techniques to identify the lane lines and estimate the cross-track error.

Here is the link for the completed project - [SDC-P9-PID-Controller][4]

-------------

**5. Model Predictive Control**

![mpc-git](https://user-images.githubusercontent.com/17127066/27775894-e13f8674-5fc3-11e7-91db-1b6018a6a5e9.png)

Implement a sophisticated control algorithm for stabilizing the vehicle in a noisy environment.

Here is the link for the completed project - [SDC-P10-MPC-Controller][5]

-------------

[1]: https://github.com/ra9hur/SDC-P6-Extended-Kalman-Filter
[2]: https://github.com/ra9hur/SDC-P7-Unscented-Kalman-Filter
[3]: https://github.com/ra9hur/SDC-P8-Particle-Filter
[4]: https://github.com/ra9hur/SDC-P9-PID-Controller
[5]: https://github.com/ra9hur/SDC-P10-MPC-Controller
