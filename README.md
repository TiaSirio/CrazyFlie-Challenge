# CrazyFlie Challenge Project 🏆

This repository showcases the first four demos of the Drone Challenge of the 2021 edition, conducted at Uppsala University in Sweden.

## Overview 🚁

The demos explore specific behaviors of Crazyflie drones within a cubic area (5m x 5m x 2m) at Polytechnic of Milan, using the Lighthouse positioning system. The challenges are implemented in Python, leveraging the MotionCommander for drone movement control and logging for various decks.

## Demos 🎮

1. Zig-zag between objects.
2. Overcome an object.
3. Pass on the left: surpass the object on its left.
4. Follow the human: when the drone detects an obstacle too close to the front sensor, it starts following the obstacle, maintaining a certain distance.

## Usage 🛠️

1. Clone or download this repository.
2. Set up the Lighthouse and the Crazyflie drone.
3. Run each demo script using Python.

## Known Issues - Decks 🚧

- The Z-ranger deck v2 exhibits stability issues when passing above an object due to compensation on the Kalman Filter.

## University Course 📖

This is the final project of the exam "Middleware Technologies and Distributed Systems" for the Computer Science and Engineering degree at Polytechnic of Milano.

## Authors 👨‍💻

- [TiaSirio](https://www.github.com/TiaSirio)
- [matteovisotto](https://www.github.com/matteovisotto)
- Daniele Sinigaglia

## Documentation 📄

For detailed information and results, refer to the [Drone_demos.pdf](Drone_demos.pdf) document.