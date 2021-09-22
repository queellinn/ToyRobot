# Toy Robot
This is an application allowing a toy robot to move around on a grid measuring 5 x 5 units. 
## Commands
Command|Action
--------------|--------------
`PLACE X,Y,FACING`|Places the robot on the table in position `X`, `Y` and facing `NORTH`, `SOUTH`, `EAST` or `WEST`.
`MOVE`|Moves the robot one unit forward in the direction it is currently facing.
`LEFT`|Rotates the robot 90° anti-clockwise without changing the position of the robot.
`RIGHT`|Rotates the robot 90° clockwise without changing the position of the robot.
`REPORT`|Outputs the X, Y and F (facing/direction) of the robot.
`HELP`|Displays this table.
`QUIT`|Terminates the application.

The application will discard all commands until a valid `PLACE` command has been executed.
## Example Input
````
PLACE 0,0,NORTH
````
````
MOVE,LEFT
````
````
REPORT
````
````
RIGHT,MOVE,MOVE,LEFT,REPORT
````
````
LEFT,LEFT,MOVE
````
````
RIGHT,LEFT,RIGHT
````
## Example Output
Output|Action
--------------|--------------
`0,0,WEST`|`REPORT` command returns current `X`, `Y` and `DIRECTION` of the robot.
`OK`|Command accepted and executed.
`ERROR`|Command is invalid or will destroy the robot.
## Badges
[![Quality Gate Status](https://sonarcloud.io/api/project_badges/measure?project=queellinn_ToyRobot&metric=alert_status)](https://sonarcloud.io/dashboard?id=queellinn_ToyRobot)
[![Reliability Rating](https://sonarcloud.io/api/project_badges/measure?project=queellinn_ToyRobot&metric=reliability_rating)](https://sonarcloud.io/dashboard?id=queellinn_ToyRobot)
[![Security Rating](https://sonarcloud.io/api/project_badges/measure?project=queellinn_ToyRobot&metric=security_rating)](https://sonarcloud.io/dashboard?id=queellinn_ToyRobot)
[![Lines of Code](https://sonarcloud.io/api/project_badges/measure?project=queellinn_ToyRobot&metric=ncloc)](https://sonarcloud.io/dashboard?id=queellinn_ToyRobot)
[![Duplicated Lines (%)](https://sonarcloud.io/api/project_badges/measure?project=queellinn_ToyRobot&metric=duplicated_lines_density)](https://sonarcloud.io/dashboard?id=queellinn_ToyRobot)
