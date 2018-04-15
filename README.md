# Overview
This is the third project in SDC term 2. We will be using particle filter to localize the car postion by transaforming the car's observation coordinate to lanmark's coordinate, do the data association and calculate the particle weights.
[image0]: error.png "error"


# Compile and Run

1. mkdir build
2. cd build
3. cmake ..
4. make
5. ./UnscentedKF

# Accuracy
All the source code changes are in particle_filter.cpp file and here is the final error shown in simuator:
x: 0.108  y 0.105  yaw rate: 0.004

![alt text][image0]



