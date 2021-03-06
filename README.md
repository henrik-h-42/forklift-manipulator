# forklift-manipulator

This repository consists of most of the matlab scripts used in our semester project in the robotics course ELE306 at the Western Norway Univercity of Applied Sciences. The goal of the project was to design a robot with 3 DOF, and simulate it in MATLAB/simulink. The code her is to a large extend based on Peter Corkes book
"Robotics,Vision and Control". The design challenge our group opted for was to design an autonomus forklift. These scrips shows how we simulated the forklifts robot arm, as well how the mobile base navigated.

### Simulation of the Forklifts Robotic Arm

The scripts are used to simulate the robotic arm, and calculate the forward and inverse kinematics of the robot arm as well as the differential kinematics.

The following link shows how the scripts can be used to simulate the robot arm with joint space motion planning. Where it is simulated that the forklift os picking up a pallet, and then put it on a shelf. 

[![Animation of the Robot arm](https://img.youtube.com/vi/XcspdaYHjw0/0.jpg)](https://www.youtube.com/watch?v=XcspdaYHjw0&)


An additonal animation is also been made where it is simulated that the forklift is moving under the pallet, picking it up, moving, putting the pallet at a shelf, and finally pull away from the pallet.
[![An addition animation of the robot arm](https://youtu.be/Nd98sdwXui4)


### Simulation of The Forklifts Mobile Base

The following pictures depict how the scrips were used to simulate the robots mobile base. 

![Simulation of the mobile base](https://github.com/henrik-h-42/forklift-manipulator/blob/main/animation.gif)

Unfortunately the landmark() function from Peter Corke's toolbax did not work together with an Occupancy map in 
matlab. But a sensor was implemented to depict how the mobile base could scan for landmarks.





