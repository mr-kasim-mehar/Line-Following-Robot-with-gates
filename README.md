# *********************Line Following Robot With Logic Gates*********************

## Group Members

1. Usman Qadeer: 221370030
2. Qasim Riaz: 221370003
3. Waqas Rafique: 221370221
4. Rana Junaid: 221370126


## Abstract
*The Line Following robot is beginner-friendly and interesting to understand and build. Its working consists of basic logic gates and circuits; the robot follows a line and solves the maze of lines. The robot consists of three IR Sensors to detect the line and two motors to control the movement and direction.

## Introduction
A Line following robot is a machine capable of following a line autonomously. It is a mobile robot that follows a provided path or trajectory through a feedback mechanism and performs its own intelligent actions according to the path or obstacles present in front of it.

This robot consists of two DC motors and two wheels for movement, three IR sensors to detect the line, two AND gates, two OR gates, four NOT gates, one motor driver, a breadboard for circuitry, a car chassis for structural support, and two rechargeable cells for power.

The line-following robot has the capability to follow a black or dark path depending upon the contrast. Line following robots have a wide range of applications ranging from normal domestic use to sophisticated industrial use, such as systems that carry packages from one place to another in an industry, following a predefined path.

## Hardware Components
- IR Sensors (3)
- 74LS08 IC (4 AND gate)
- 74LS04 IC (2 NOT gate)
- 74LS32 IC (2 OR gate)
- L293N Motor Driver (1)
- DC Motors (2)
- Wheels (2)
- Breadboard (1)
- Jumper Wires
- Chassis (1)
- Caster wheel (1)
- Rechargeable cells (2)

## Working
DC motors and wheels are used for movement. IR sensors are used to detect the line. Motor driver is used to control the motors. Breadboard is used for circuitry. Car chassis is used for structural support, and rechargeable cells are used to power the circuit.

## Truth Table

| L(s) | C(s) | R(s) | M(L) | M(R) |
|------|------|------|------|------|
| 0    | 0    | 0    | 0    | 0    |
| 0    | 0    | 1    | 0    | 1    |
| 0    | 1    | 0    | 1    | 1    |
| 0    | 1    | 1    | 0    | 1    |
| 1    | 0    | 0    | 1    | 0    |
| 1    | 0    | 1    | 0    | 0    |
| 1    | 1    | 0    | 1    | 0    |
| 1    | 1    | 1    | 0    | 0    |

## Boolean Expressions
- M(L) = BC' + AC'
- M(R) = A'C + A'B
