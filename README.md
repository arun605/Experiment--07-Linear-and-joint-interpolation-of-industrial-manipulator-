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

![WhatsApp Image 2022-11-21 at 18 33 44](https://user-images.githubusercontent.com/118738931/203062710-e7c15b2d-1ae0-48fc-b20f-830bd29ffd87.jpg)

### Robot movements 

![image](https://user-images.githubusercontent.com/118738931/203062829-b13c8d00-a53c-480e-b828-880d5e02d28f.png)

![image](https://user-images.githubusercontent.com/118738931/203062873-fd6882bd-6e97-4bba-846c-726bbd893c6d.png)

![image](https://user-images.githubusercontent.com/118738931/203062922-a7af67cf-0fbe-4474-ba72-63e030f22b4b.png)

![image](https://user-images.githubusercontent.com/118738931/203062966-dfe2c286-f3f9-4de9-ac89-36067ab6d99a.png)

### Results: 
Thus ,linear and joint interpolation of industrial manipulator and program is executed.
 
