# Prime Cuber

Prime Cuber is my LEGO SPIKE Prime Rubik's Cube solver. The goal of the project is to make a robot that can take a scrambled Rubik's Cube and solve it using LEGO SPIKE Prime.

I built Prime Cuber using LEGO Technic pieces and the parts that came with the LEGO SPIKE Prime kit. The SPIKE Prime Hub controls the motors and sensors that make the robot move.

## What Prime Cuber Does

Prime Cuber is designed to hold a Rubik's Cube and turn the different parts of the cube. The robot uses motors to move the mechanisms that control the cube.

The idea is that instead of solving the cube by hand, the robot can do the moves for me.

The main things the robot needs to do are:

1. Hold the Rubik's Cube in the right position.
2. Move the cube without dropping it.
3. Turn the different sides of the cube.
4. Use the SPIKE Prime motors to make the movements.
5. Follow the solving sequence until the cube is solved.

## How I Built It

I built the robot out of LEGO Technic pieces from the SPIKE Prime set. I used different beams, pins, axles, gears, and other LEGO pieces to make the mechanisms.

One of the hardest parts of building it was making the mechanisms strong enough to move the Rubik's Cube while still allowing the cube to turn.

I also had to make sure that the motors were attached securely so that the robot did not move around instead of moving the cube.

## Electronics

The electronics for Prime Cuber are LEGO SPIKE Prime parts.

The main controller is the SPIKE Prime Hub. The Hub controls the motors and sensors and runs the program.

The motors are connected directly to the Hub using the cables that came with the SPIKE Prime kit. There is no custom PCB in this project.

## Motors

The motors are used to move the different mechanisms on the robot.

The program controls how far the motors turn and how fast they move. Getting the motors to move the correct amount is important because even a small error can make the Rubik's Cube harder to solve.

I had to test the motor movements to make sure the mechanisms were moving the cube correctly.

## Programming

I programmed Prime Cuber using LEGO SPIKE Prime.

The program tells the Hub what the motors need to do and controls the movements of the robot.

A big part of the programming is making sure the robot does the moves in the correct order. The robot has to make the right turns and movements or the cube will not end up solved.

I also had to test the program multiple times because the physical robot does not always move exactly how I expect it to.

## Solving the Cube

The Rubik's Cube starts scrambled.

The robot needs to perform a series of moves to get the cube back to the solved state. Each move has to be done correctly because one wrong movement can change the rest of the solution.

Prime Cuber uses the programmed sequence of movements to control the cube.

The goal is for the robot to finish with all of the colors on the correct sides.

## Testing

I tested the robot by running different movements and checking how the Rubik's Cube moved.

Some of the testing involved changing how far the motors moved and making sure the cube stayed in the correct position.

I also tested the mechanisms to make sure they did not get stuck and that the LEGO pieces stayed connected while the motors were running.

Testing was important because the robot has a lot of moving parts, and small problems with one mechanism can affect the rest of the robot.

## Problems I Had

One of the challenges with this project was getting the LEGO mechanisms to move the Rubik's Cube correctly.

The motors can move very precisely, but the physical LEGO pieces can still move slightly when the robot is running. This means that the robot has to be built carefully and the motor movements have to be tested.

Another challenge was making the robot strong enough to turn the cube without the frame bending or pieces coming apart.

## What I Learned

While working on Prime Cuber, I learned more about LEGO mechanical systems, gears, motors, sensors, and programming.

I also learned that building something that works in real life is different from just writing code. The code can be correct, but if the mechanism is not built correctly, the robot still won't work.

I had to keep testing the robot and changing things until the mechanical parts and the program worked together.

## Parts

The project uses parts from a LEGO SPIKE Prime kit, including:

- LEGO SPIKE Prime Hub
- LEGO SPIKE Prime motors
- LEGO SPIKE Prime sensors
- LEGO Technic beams
- LEGO Technic axles
- LEGO Technic gears
- LEGO Technic pins
- Other LEGO pieces from the SPIKE Prime set
- SPIKE Prime motor and sensor cables
- Rubik's Cube

The full bill of materials is in [BOM.csv](BOM.csv).

## Wiring

Prime Cuber does not use a custom PCB.

The motors and sensors connect directly to the SPIKE Prime Hub using the LEGO SPIKE Prime cables that came with the kit.

The wiring diagram is included in this repository.

## Project Goal

My goal with Prime Cuber is to build a LEGO robot that can solve a Rubik's Cube.

I wanted to make something that combines LEGO building, mechanical design, programming, motors, and sensors into one project.

## Future Improvements

If I keep working on Prime Cuber, I would like to improve the robot's reliability and make the solving process faster.

I would also like to make the mechanisms work more smoothly and reduce the amount of time it takes for the robot to solve the cube.

## Credits

Prime Cuber was built by me using LEGO SPIKE Prime and LEGO Technic parts.

The project is called **Prime Cuber** because it uses LEGO SPIKE Prime to solve a Rubik's Cube.
