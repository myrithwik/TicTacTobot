# TicTacTobot
Automated Tic Tac Toe Robot

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Usage](#usage)
- [Video Demo](#videodemo)

## Overview

In this project I showcase my skills in embedded systems engineering by building an automated tic tac toe robot. Topics in this project include mechanical construction, hardware design, and software design. The process of building this project from the ground up was an incredible learning experience. My main takeway from this project is understanding the challenges of integrating hardware with software to create a robust product. 

## Features

Main features in this project include:
- **Cartesian XY T-Gantry system**
<img src="images/IMG_4797.jpeg" width="500" height="500">
<img src="images/IMG_4801.jpeg" width="500" height="500">
<img src="images/IMG_4803.jpeg" width="500" height="500">
<img src="images/IMG_4805.jpeg" width="500" height="500">

- **Stepper Motors to power the gantry**
<p>Stepper Motors Wiring:</p>
<img src="images/IMG_4795.jpeg" width="500" height="500">

- **Electromagent with Two Channel Relay**
<p>Electromagnet Connected to Gantry System:</p>
<img src="images/IMG_4798.jpeg" width="500" height="500">

<p>Two Channel Relay Wiring:</p>
<img src="images/IMG_4796.jpeg" width="500" height="500">

- **Hall Effect Sensor Grid**
<img src="images/IMG_4793.jpeg" alt="Description of the image" width="500" height="500">

<p>Wiring of the Hall Effect sensors:</p>
<img src="images/IMG_4794.jpeg" width="500" height="500">

- **Magnetic Game Pieces**
- **Gameplay logic coded into the Arduino Uno Microcontroller**

## Usage

The stepper motors are used to control the T-gantry system. The electromagnet is connected on top of the gantry so that it can be moved under the game board. The magnet will be switched on and off using the two channel relay to move the magnetic game pieces. The board itself has strategically placed hall effect sensors to detect where game pieces are placed. This data is sent back to the Arduino Uno which keeps track of the board status and programatically determined the CPU's next move which is carried out by the gantry and electromagnet.

### Video Demo

[![Watch the Demo Video](images/thumbnail.jpg)](images/IMG_4790.MOV)

Click the thumbnail to watch the demo video.
