# TicTacTobot
Automated Tic Tac Toe Robot

## Table of Contents
- [Overview](#overview)
- [Features](#features)
- [Installation](#installation)
- [Usage](#usage)
- [Demo](#demo)
- [Contributing](#contributing)
- [License](#license)

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
<img src="images/IMG_4795.jpeg" width="500" height="500">
<p>Wiring the Stepper Motors</p>

- **Electromagent with Two Channel Relay**
<img src="images/IMG_4798.jpeg" width="500" height="500">
<p>Electromagnet Connected to Gantry System</p>

<img src="images/IMG_4796.jpeg" width="500" height="500">
<p>Two Channel Relay Wiring</p>

- **Hall Effect Sensor Grid**
<img src="images/IMG_4793.jpeg" alt="Description of the image" width="500" height="500">

<img src="images/IMG_4794.jpeg" width="500" height="500">
<p>Wiring of the Hall Effect sensors</p>

- **Magnetic Game Pieces**
- **Gameplay logic coded into the Arduino Uno Microcontroller**

## Usage

The stepper motors are used to control the T-gantry system. The electromagnet is connected on top of the gantry so that it can be moved under the game board. The magnet will be switched on and off using the two channel relay to move the magnetic game pieces. The board itself has strategically placed hall effect sensors to detect where game pieces are placed. This data is sent back to the Arduino Uno which keeps track of the board status and programatically determined the CPU's next move which is carried out by the gantry and electromagnet.

### Image Gallery

1. <img src="images/IMG_4793.jpeg" width="500" height="500">
2. <img src="images/IMG_4794.jpeg" width="500" height="500">
3. <img src="images/IMG_4795.jpeg" width="500" height="500">
4. <img src="images/IMG_4796.jpeg" width="500" height="500">
5. <img src="images/IMG_4797.jpeg" width="500" height="500">
6. <img src="images/IMG_4798.jpeg" width="500" height="500">
7. <img src="images/IMG_4801.jpeg" width="500" height="500">
8. <img src="images/IMG_4803.jpeg" width="500" height="500">
9. <img src="images/IMG_4805.jpeg" width="500" height="500">

### Video Demo

[![Watch the Demo Video](images/thumbnail.jpg)](images/IMG_4790.MOV)

Click the thumbnail to watch the demo video.

## Contributing

If you'd like to contribute, please fork the repository and create a pull request.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
