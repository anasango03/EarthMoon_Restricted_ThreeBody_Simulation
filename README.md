# Earth-Moon Restricted Three-Body Simulation

This computational physics project models the trajectory of a spacecraft traveling from Earth to the Moon. It explores the classical **Restricted Three-Body Problem** by numerically integrating the equations of motion using the **Runge-Kutta (RK)** method.

## Project Overview

The three-body problem (Earth, Moon, and spacecraft) cannot be solved analytically. However, because the mass of the spacecraft is negligible compared to the Earth and the Moon, it can be treated as a *restricted* problem. This means the spacecraft is affected by the gravitational pull of both celestial bodies, but it does not perturb their orbits. 

This repository contains a Python simulation that calculates the orbital mechanics of the system and generates a dynamic animation of the spacecraft's trajectory toward the Moon.

## Repository Structure

* **`01_Apollo_Trajectory_Simulation.py`**: The core simulation and visualization script. It initializes the physical constants (masses, Earth-Moon distance, escape velocity) and uses a time-step integration to calculate the position and momentum of the spacecraft. It also utilizes `matplotlib` to render a real-time animation of the Earth, the moving Moon, and the rocket's path.

## Technologies Used

* **Python 3**
* **NumPy**: For efficient array management and vector calculus.
* **Matplotlib & Imageio**: For real-time plotting and generating the trajectory animation.
