# Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-

### Aim :
      To understand linear and joint interpolation of industrial manipulator and develop a program for the same 
      
### Equipment Required: 
      Instrial manipulator , teach pendant and associated program platform 
      
### Theory 
    The following interpolation schemes are available in most of the robot controllers.
1. Joint interpolation
2. Straight line interpolation
3. Circular interpolation
4. Irregular smooth motions (manual lead through programming).
#### Joint interpolation: 
The controller determines how far each joint must move to get from the first point defined in the programme to the next. It then selects the joint that
requires the longest time. This determines the amount of movement for other axes such that all the axes start and stop at the same time. Joint interpolation is the default procedure for many commercial robots.

#### Straight-line interpolation: 
In this interpolation, the robot controller computes the straight-line path between two points and develops the sequence of addressable point along the path for the robot to pass through.

#### Circular interpolation: 
This requires the programmer to define a circle in the
robot’s workspace. This is done by specifying three points that lie along the circle. The controller constructs the circle by selecting a series of points that lie closer to the circle. These movements are actually small straight lines. If the addressable points are dense then the linear approximation becomes very much like circle.


#### Manual lead through Programming: 
When the manipulator wrist is moved by the programmer to teach, the movements consist of combination of smooth motion segments. These segments are sometimes approximately straight lines or curves or back and forth motions. These movements are referred as irregular smooth motions and an interpolation is involved to achieve them.




![Robot-interpolation-PTP-LIN-CIRC](https://user-images.githubusercontent.com/36288975/201615171-d0886aaa-8220-4b0c-8a1d-3d8a5c69c76a.png)

### Figure -01 difference between P-P , joint and linear interpolation 


### Program : 

DART studio screen shots for linear interpolation 









DART studio screen shots for joint interpolation 



![WhatsApp Image 2024-04-15 at 14 31 08_acca6f6d](https://github.com/sanjaysivaramakrishnan/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/151629616/dfaa2009-dcd1-46bb-90e8-c71819b77f16)





## Robot movements 





![WhatsApp Image 2024-04-15 at 14 31 09_ae2d214f](https://github.com/sanjaysivaramakrishnan/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/151629616/70f63ab4-5ff9-4f38-89ef-62aed1646613)

![WhatsApp Image 2024-04-15 at 14 31 09_ab8d8d80](https://github.com/sanjaysivaramakrishnan/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/151629616/4be1b406-2f45-4f64-a80b-1e0ec1befa48)








### Results:  
The program for linear and joint interpolation of industrial manipulator is developed successfull
