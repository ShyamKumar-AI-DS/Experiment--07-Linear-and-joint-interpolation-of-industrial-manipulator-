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
Name : Shyam Kumar A
Reg No : 212221230098
```

DART studio screen shots for linear interpolation and DART studio screen shots for joint interpolation. 

![1](https://user-images.githubusercontent.com/94226297/203059184-0447ae4b-8eb7-4736-9c1b-6ccf7d680a17.jpeg)

### Robot movements 

![2](https://user-images.githubusercontent.com/94226297/203059280-a1397958-489a-4477-b05c-b75bc0441304.jpeg)

![3](https://user-images.githubusercontent.com/94226297/203059765-f0f9539b-4626-4ad4-bdc4-f47218e93844.jpeg)

![4](https://user-images.githubusercontent.com/94226297/203059794-0ebbf0a7-074c-438a-9e0e-67954bcb87a9.jpeg)

![5](https://user-images.githubusercontent.com/94226297/203059811-5f041aa5-7e4f-49e7-ac90-95bdda7b8730.jpeg)

### Result: 

Thus ,linear and joint interpolation of industrial manipulator and program is executed.
