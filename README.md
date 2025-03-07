# Forward-kinematics-using-robo-analyzer

## AIM: 
To analyze the forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer and polt the graph for link cordinates and joint angles
### COMPONENTS REQUIRED:
1.Robo analyzer software  


### THEORY :
  
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

STEP 1:Open the roboanalyzer software.

STEP 2:Select the robot and its degrees of freedom.

STEP 3:Change the values with the link lenght wherever necessary.

STEP 4:Simulate the model for forward kinematics.

STEP 5:Plot the graph between the link and the joints.

STEP 6:Update the DH parameters of the link configuration and end effector configuration.



### SIMULATION 
 
## DH PARAMETERS
## 6 DOF

![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/ae1fd899-15e5-4908-a629-ce5535dfe081)

## 4 DOF

![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/42c65604-a4af-4237-9546-63291407440e)

 ### PLOT 
 
 ## 6 DOF
 
 ![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/e115978a-b8ac-4d3d-aa67-36be6b3bd2eb)

## 4 DOF:
 
 ![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/a8c4fb8e-fbae-4ade-95d2-0f86d726d016)

## PLOT :
## 6 DOF:

 ![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/9cc64e1c-12af-4342-8223-74bbdc64350c)

## 4 DOF:

![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/515a9a49-4eba-4b75-9efd-1305356d8bdd)

 
## EE CONFIGURATION:
## 6 DOF:
 
 
 ![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/742bc762-1932-401a-adeb-2acfa1e1076f)

## 4 DOF:

![image](https://github.com/Janani-2003/Forward-kinematics-using-robot-analyzer/assets/94288340/7dbd2d5c-e607-4490-83c2-fcc5c6ccff98)



### RESULTS :  

The forward kinematics using DH paramerters for a 4 and 6 dof robot using roboanalyzer has been analyzed and the graph for link cordinates and joint angles has been ploted.
