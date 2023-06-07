# Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-cobot
## Aim : To Execute a program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio.

## Components Required:

*Doosan Industrial Collaborative Robot

*DRL (Doosan Robotics Language) Studio Software

### Theory 
INTERPOLATION

Interpolation, which is necessary for any type of programming, consists of generating data points between given coordinate axis positions. Within the Machine Control Unit (MCU), a device called an interpolator causes the drives to move simultaneously from the start to the end of the command. The interpolator is either an electronic hardware device for a NC system, or a software program for a CNC system. An interpolator provides two functions:

It calculates individual axis velocities to drive the tool along the programmed path at the given feed rate.

It generates thousands of intermediate coordinate points along the programmed path between the start point and the end point of the cut.

During positioning, all programmed axes move simultaneously at the specified feed rates until each axis has reached its destination. All drives start together, but without an interpolator individual destinations are reached successively according to the path traveled. However, an interpolator coordinates these axis motions in such a way that the programmed path is constantly maintained from the beginning to the end of the movement.

Linear and circular interpolation are most commonly used in CNC programming applications:

Linear interpolation is used for straight-line machining between two points.

Circular interpolation is used for circles and arcs.

Helical interpolation, used for threads and helical forms, is available on many CNC machines.

Parabolic and cubic interpolation are used by industries that manufacture parts having complex shape such as aerospace parts, and...

## Procedure:

Manipulate the end effector as per the given configuration. Movement Should Initiate in P1 and progress till the end point. Travel path should be in sequence as stated below.


![Screenshot (308)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/83618fe9-e882-4a2f-a3a2-e05b0254f9f2)

![Screenshot (309)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/4023565c-bd61-4208-8145-d7f2ab0d3b6b)

![Screenshot (310)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/942380f1-7713-4052-809f-a231a557eeba)

![Screenshot (311)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/3c499c12-5302-4e6a-8f80-84002cecd6cf)

![Screenshot (312)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/e08c2b9f-a833-4eb1-84e0-4c7a7faed4de)

![Screenshot (313)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/78150932-8d62-474e-9d7e-59c2481dd999)

![Screenshot (314)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/f84cec66-f8d6-4276-bde2-6261393c0686)

### output
linear interpolation:

![Screenshot (315)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/aaf8917a-8bf2-472b-a254-1e563548ea38)

circular interpolation:

![Screenshot (316)](https://github.com/VelasiriSreeja/Lab-Ex.-No---7-Execute-a-program-for-Straight-line-and-Circular-interpolation-in-Doosan-Industrial-C/assets/118344328/806ecf06-79b2-48fe-b5ea-fcf70ea1a553)


### Result
A program for Straight-line and Circular interpolation in Doosan Industrial Cobot using DRL studio has been executed successfully.
 
