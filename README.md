# LEGO SPIKE Prime Cuber

## What is this?

This is my LEGO SPIKE Prime Rubik's Cube Solver. It is a robot that uses LEGO SPIKE Prime motors and a color sensor to solve a Rubik's Cube.

I made this project because I thought it would be cool to build a robot that could solve a Rubik's Cube by itself. I wanted to combine LEGO building, programming, and problem solving into one project.

## How It Works

The robot uses motors to move the Rubik's Cube and a color sensor to read the colors.

The basic process is:

1. Put a scrambled Rubik's Cube into the robot.
2. The color sensor reads the colors.
3. The program figures out what the cube looks like.
4. The program calculates the moves needed to solve it.
5. The motors move the cube.
6. The robot continues until the cube is solved.

The motors have to be very accurate. If one motor moves too far or not far enough, the cube can get out of position and the solution will not work correctly.

## Hardware

I built the robot using parts from a LEGO SPIKE Prime kit.

* 1 LEGO SPIKE Prime Hub
* 1 LEGO SPIKE Prime Large Motor
* 2 LEGO SPIKE Prime Small Motors
* 1 LEGO SPIKE Prime Color Sensor
* LEGO Technic beams, gears, axles, and connectors
* 1 Rubik's Cube

## Bill of Materials

| Part                          |  Amount |
| ----------------------------- | ------: |
| LEGO SPIKE Prime Hub          |       1 |
| LEGO SPIKE Prime Large Motor  |       1 |
| LEGO SPIKE Prime Small Motor  |       2 |
| LEGO SPIKE Prime Color Sensor |       1 |
| LEGO Technic parts            | Various |
| Rubik's Cube                  |       1 |

## Building It

First, I built the main LEGO frame that holds the Rubik's Cube.

Then I added the motors and gears that move the cube. I also added the color sensor so the robot can read the colors.

After building everything, I connected the motors and sensor to the SPIKE Prime Hub and tested each part separately.

A big part of building this was making sure the cube stays in the right position while the motors are moving it.

## Programming

I programmed the Cuber using the LEGO SPIKE Prime programming system.

The program controls the motors, reads the color sensor, and tells the robot what movements to make.

I had to test the motor movements many times because the robot needs to turn the cube very accurately.

## Calibration

Getting the motor movements right was one of the hardest parts.

I tested how far the cube moved with different motor settings and changed the values until the movements were accurate.

Even a small difference in a motor movement can cause the cube to be in the wrong position later.

## Problems I Had

One problem I had was getting the motors to move exactly the right amount.

Another problem was keeping the cube lined up correctly. If the cube moves around while the robot is running, the motors might not turn it correctly.

I fixed these problems by testing the robot, changing the code or LEGO pieces, and trying again.

## What I Learned

I learned a lot about programming motors and sensors with LEGO SPIKE Prime.

I also learned that the physical robot and the code have to work together. A small problem with the LEGO mechanism can cause a problem in the program, and a small programming mistake can make the robot move incorrectly.

This project also taught me a lot about testing and debugging because I had to keep trying different things until they worked.

## How to Run It

1. Turn on the SPIKE Prime Hub.
2. Connect the Hub to the SPIKE Prime app.
3. Open the Cuber program.
4. Make sure the motors and color sensor are connected to the correct ports.
5. Put the scrambled Rubik's Cube into the robot.
6. Start the program.
7. Let the robot scan the cube and run the solving program.

## Photos

Photos of the finished robot, the mechanism, and the build are included in this repository.

## Future Improvements

I would like to make the robot faster and make the color sensor more accurate.

I would also like to improve the mechanism so the cube stays in place better and make the solving process more reliable.

## Why I Made It

I made this project because I like LEGO, robotics, and programming. I wanted to challenge myself by making something that could solve a real Rubik's Cube instead of just making a robot that moves around.

It took a lot of testing and fixing, but it was really cool seeing the robot actually solve the cube.

## Project Photo

![Finished LEGO Rubik's Cube Solver](rubiks-cube-solver.png)
