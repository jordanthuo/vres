# Bimanual Robot Arm Teleop System

## Project Overview

This repository provides a modular and scalable framework for bimanual robotic arm teleoperation. While currently demonstrated with the WidowX 250 S by Trossen Robotics and the Franka Emika Panda arm, the system is designed to support a wide range of robotic platforms. Its architecture enables advanced collaborative manipulation tasks, offering flexibility for customization and integration across various hardware and software setups.

### Features

- **Modular and Scalable Framework**: Designed to be easily adaptible to accommodate future expansions, including additional arms or end-effectors.
- **Collaborative Manipulation**: Enables bimanual teleoperation for tasks requiring precise coordination between two arms.
- **Customizable Hardware**: Includes customizable CAD components that can be tailored for specific robotic platforms or applications.

## Repository Structure

```plaintext
├── CAD_Files/
│   ├── Assembly/
│   │   ├── WidowX_Controller/
│   │   ├── FrankaPanda_Controller/
│   ├── Base/
│   ├── Connector/
│   ├── Corner_Adaptor/
│   ├── Handle/
│   ├── Hex_Adapter/
│   ├── Joint_House/
│   ├── Joints/
│   ├── Shaft/
│   ├── Splint_Support/
│   ├── U_Pin/
├── Software/
├── Documentation/
│   ├── Setup_Guide.md
├── README.md
```

#### CAD_Files/

Contains the CAD components for the custom controllers:

- **WidowX_Controller/**: CAD files for the WidowX robotic arm controller.
- **FrankaPanda_Controller/**: CAD files for the Franka Panda robotic arm controller.

#### Software/

Holds the software scripts and tools:

#### Documentation/

Comprehensive guides and references:

- **Setup_Guide.md**: Step-by-step instructions, assembly guidance, and parts list for setting up the system.

## Getting Started

### Installation

#### Clone the repository:

```bash
git clone https://github.com/jordanthuo/vres
```

## Usage

1. Follow the setup guide **Documentation/Setup_Guide.md** to configure hardware and software.
2. Load the CAD files within **CAD_Files/Assembly/.../** into your preferred CAD software for customization or review. Alternatively, import the files into your preferred slicer for 3D printing.
## Acknowledgments

This project was made possible with the support of the QUT Centre of Robotics. Special thanks to my supervisor DR Krishan Rana for providing guidance and mentorship throughout this project.

## Contact

For questions or support, please reach out to jthuo1@outlook.com
