# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY: 
  
Forward Kinematics

A manipulator is composed of serial links which are affixed to each other revolute or prismatic joints from the base frame through the endeffector. 
Calculating the position and orientation of the endeffector in terms of the joint variables is called as forward kinematics. 
In order to have forward kinematics for a robot mechanism in a systematic manner, one should use a suitable kinematics model. 
Denavit-Hartenberg method that uses four parameters is the most common method for describing the robot kinematics. 
These parameters ai1, α −,1idi and θ the link length, link twist, link offset and joint angle, respectively. 
A coordinate frame is attached to each joint to determine DH parameters. Zi axis of the coordinate frame is pointing along the rotary or sliding direction general manipulator.

Denavit Hartenberg Parameters
With DH Parameters, solving for the Forward Kinematics is easy.  only need to take four parameters for each joint 
i: θifor the joint angle, 
αi for the link twist, 
difor the link offset, and 
ai for the link length. Once I’ve obtained them, I can just plug them in to this transformation matrix:


![image](https://user-images.githubusercontent.com/36288975/170172719-ed7befc9-2894-4344-bfd5-be831bb05308.png)

 ![image](https://user-images.githubusercontent.com/36288975/170172766-b8aeb788-7fd7-4de7-b340-f04656707ebd.png)

 

### PROCEDURE:
1.open the roboanalyzer software.
2.select the robot and its degrees of freedom. 
3.change the values with the link lenght wherever necessary. 
4.simulate the model for forward kinematics.
5.plot the graph between the link and the joints. 
6.update the DH parameters of the link configuration and end effector configuration.




### SIMULATION:

## 6 DOF:
 ![237883852-f2f7149c-c3cd-4abb-8c30-7fa854e44052](https://github.com/SivaMohan-cloud/Forward-kinematics-using-robot-analyzer/assets/121418870/6a74454e-fe7a-4391-a22d-09d1bd6ef40e)

## 4 DOF:
![237883865-d0bcc4f4-1668-4126-aeb8-1d9bfcf83486](https://github.com/SivaMohan-cloud/Forward-kinematics-using-robot-analyzer/assets/121418870/2956270a-1762-45f2-8abd-2c5e7e16c29c)

 

 ### PLOT:
 
 ## 6 DOF:
 ![237883888-7c4a3f3f-6c18-4c37-aa8b-4aea2029f630](https://github.com/SivaMohan-cloud/Forward-kinematics-using-robot-analyzer/assets/121418870/5d0bfc53-a4fc-4424-8b00-273a3f93aa2f)

 
 ## 4 DOF:
 ![237883913-c3e56194-0991-47a8-8990-570f5a0a6182](https://github.com/SivaMohan-cloud/Forward-kinematics-using-robot-analyzer/assets/121418870/71035532-3aad-4217-8426-6859df9692df)
![237883925-65176d26-e7c8-4b19-85b4-905677a70a6c](https://github.com/SivaMohan-cloud/Forward-kinematics-using-robot-analyzer/assets/121418870/2cb3bd95-87ce-4ee9-858e-69fb3d339bdc)

## RESULT:
Thus, the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer is analysed and the graph for link cordinates and joint angles is plotted.

 
 
 
 
 
 
 
 
 
 
 

 
 














### RESULTS :  
