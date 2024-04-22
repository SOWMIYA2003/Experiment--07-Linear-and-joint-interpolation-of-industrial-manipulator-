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
```
Sowmiya N
212221230106
```
DART studio screen shots for linear interpolation 
DART studio screen shots for joint interpolation 
![p1](https://github.com/SOWMIYA2003/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/93427443/771d840a-7e56-455e-9580-f535d978906d)







### Robot movements :
![p2](https://github.com/SOWMIYA2003/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/93427443/5d11bb20-689e-4e38-90cc-188f2dbb78cf)


![p3](https://github.com/SOWMIYA2003/Experiment--07-Linear-and-joint-interpolation-of-industrial-manipulator-/assets/93427443/7a82c43e-2054-4cb3-814f-81f3a95d3944)



### Output :
Thus ,linear and joint interpolation of industrial manipulator and program is executed.











### Results:  
