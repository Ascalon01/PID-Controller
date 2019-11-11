# **PID-Controller**

#### **Project Overview**
Given a driving simulator which provides the cross track error (CTE) and the velocity (mph), the goal of this project is to develop a PID controller in c++ that successfully drives the vehicle around the track. In order to navigate the car around the track. I have implemented PID controllers for steering angle control.


#### Files in the repository
* Code for the algorithm is contained in the [Source Folder](./src)

* A [writeup](./writeup.md) detailing the results of the project and describing the procedure.

* A [video](./output_videos/output_PID.mp4) output based on driving the vehicle around track using PID Controller.
  
#### Dependencies
This project was developed in C++. 
The project depends on the,
  1. cmake >= 3.5
  2. make >= 4.1
  3. gcc/g++ >= 5.4
  4. uWebSockets
  5. [Simulator](https://github.com/udacity/self-driving-car-sim/releases)
  
### Build Instructions
1. Clone this repo.
2. Make a build directory: mkdir build && cd build
3. Compile: cmake .. && make
4. Run it: ./pid 
