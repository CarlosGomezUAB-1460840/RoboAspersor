
# Read Me Template
Autonomous robot that waters the plants of a garden. It is able to recognize differnt types of flowers to adjust the amount of watering.

![RoboAspersor](https://github.com/CarlosGomezUAB-1460840/RoboAspersor/blob/main/Images/Robot.PNG)

---

### Table of Contents
You're sections headers will be used to reference location of destination.

- [What it is?](#what-it-is)
- [Description](#description)
- [Requeriments](#requeriments)
- [How to Use](#how-to-use)
- [Simulation](#simulation)
- [Author Info](#author-info)

---

## What it is?

The development team is made up of 3rd year information engineering students. This project has been developed for the subject of Robotics Language and Planning.

Currently on the market there are many robot vacuum cleaners such as the rumba among others, but there is none that is capable of autonomously watering a garden. We have designed a robot, with a budget of 100, capable of watering the garden and taking care of the watering of the different types of plants.

This is our solution

---

## Description

RoboAspersor is an autonomous robot that waters the plants of a garden. It is able to recognize differnt types of flowers to adjust the amount of watering.

The robot body has been created using the tinkercad tool. It is made up of different parts:

- A watertight area to encapsulate electronic elements such as the Raspberry Pi,
- the water tank that stores water for irrigation,
- the lower part where the servomotors and the caterpillar go,
- and the Sprinkler.

Click on the image to see the 3D model.

[![3D model](https://github.com/CarlosGomezUAB-1460840/RoboAspersor/blob/main/Images/piezasRobot.PNG)](https://www.tinkercad.com/things/h1H5N6yzh8O)

To do the simulation we have used CoppeliaSim Edu.

Now let's see the software part of ther project.

![Software diagram](https://github.com/CarlosGomezUAB-1460840/RoboAspersor/blob/main/Images/estructuraSW.png)

---

## Requeriments
For runniung each sample code:
We use a development environment created in anaconda navigator to be able to run the robot

- Python 3.9.x
- CoppeliaSim Edu
- Miniconda 
- Anaconda Navigator
- Jupyter notebook
- Numpy
- TensorFlow

For developement:

- TensorFlow (for IA)
- Sim (for connect to Coppelia)
- And other libraries like (Time, sys, random, skimage.io)+
- TinkerCad (for 3D model)

---
## How to Use

1. Clone this repo.
> git clone [https://github.com/CarlosGomezUAB-1460840/RoboAspersor.git](https://github.com/CarlosGomezUAB-1460840/RoboAspersor.git)
2. Install the required libraries
using conda:
> conda env creaate -f enviroment.yml
3. Execute python script in each directory
4. Download files my_model.h5 and Robot.ttt from drive

---
## Simulation
In the simulation, the robot can be seen watering the different flowers. If a flower has already been watered, it is not watered again.

Click on the image to see the simulation video.

[![Simulation](https://github.com/CarlosGomezUAB-1460840/RoboAspersor/blob/main/Images/linkVideo.png)](https://www.youtube.com/watch?v=n0WhtZnf5Do)

---

## Author Info

- Sergi Díaz 1489852
- Carlos Gómez 1460840
- Pol Fernandez 1531031
- Marc Dávila 1481086

---
