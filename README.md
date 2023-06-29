# 3D Map Maker

This repository contains code for a 3D map maker that uses two ultrasonic sensors to scan the surrounding objects and pinpoints the data received on a 3D map.

## Getting Started

To get started, clone this repository and navigate to the project directory. The project uses Gradle as its build tool, and you can use the provided Gradle wrapper to build the project.

On Unix systems, run `./gradlew` to build the project. On Windows systems, run `gradlew.bat`.

## Project Structure

The project consists of several important files:

- `3Dmapmaker.pde`: Contains a Processing script to pinpoint data received from the two ultrasonic sensors on a 3D map.
- `control.c`: Contains Arduino code to control the physical scanning of surrounding objects using two ultrasonic sensors that revolve around themselves to do a 180º horizontal scan and another 180º vertical scan.

## License

This project is licensed under the BSD 3-Clause License. See the LICENSE file for more information.
