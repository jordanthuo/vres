# Bimanual Robot Arm Teleop System

## Project Overview

This repository contains the mechanical and software components for a bimanual robotic arm system, integrating the WidowX arm and the Franka Emika Panda arm. The project aims to explore and implement advanced control mechanisms for collaborative manipulation tasks using these two robotic platforms. The modular design allows for flexibility and customization in hardware and software integration.

## Repository Structure

```plaintext
├── CAD_Files/
│   ├── WidowX_Controller/
│   ├── FrankaPanda_Controller/
├── Software/
│   ├── Control_Scripts/
│   ├── Simulation_Tools/
├── Documentation/
│   ├── Setup_Guide.md
│   ├── API_Reference.md
├── LICENSE
├── README.md


1. CAD_Files/

Contains the CAD designs for the custom controllers:

WidowX_Controller/: CAD files for the WidowX robotic arm controller.

FrankaPanda_Controller/: CAD files for the Franka Panda robotic arm controller.

2. Software/

Holds the software scripts and tools:

Control_Scripts/: Python scripts for controlling the bimanual arms.

Simulation_Tools/: Resources for simulating arm movements and testing scenarios.

3. Documentation/

Comprehensive guides and references:

Setup_Guide.md: Step-by-step instructions to set up and run the system.

API_Reference.md: Detailed documentation of the software API.

## Getting Started

### Prerequisites

CAD software (e.g., Fusion 360, SolidWorks) to view and modify the designs.

Python 3.8 or higher.

ROS (Robot Operating System) for arm control.

Simulation tools (e.g., Gazebo, RViz).

## Installation

### Clone the repository:

git clone https://github.com/your-repo-url
cd bimanual-robot-arm

Set up ROS workspace and dependencies as outlined in Documentation/Setup_Guide.md.

Load the CAD files into your preferred CAD software for customization or review.

## Usage

Follow the setup guide to configure hardware and software.

Use scripts in Control_Scripts/ to test and control the bimanual system.

Simulate tasks using tools in Simulation_Tools/ before deploying them on physical hardware.

## Contribution

We welcome contributions to improve the project! Feel free to fork the repository, make changes, and submit a pull request. For major changes, please open an issue first to discuss the proposal.
