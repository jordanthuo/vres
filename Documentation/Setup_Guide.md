# Setup Guide
This guide outlines the steps to set up the Bimanual Robot Arm Teleop System.

## Instructions Overview
- **Bill of Materials:** Gather all necessary components based on your chosen robotic arms.
- **3D Printed Parts:** Print the required components for assembly.
- **Assembly:** Assemble the 3D printed parts and hardware components.
- **Software Setup:** Configure the software for operation and simulation.

## Bill of Materials
Ensure you have the necessary parts for your specific robotic arm setup. Below is a sample bill of materials for commonly used robotic arms:

### Franka Emika Panda
| Vendor | Description | Cost (USD) | Quantity | Total (USD) | Link |
|--------|-------------|------------|----------|-------------|------|
| Amazon | Power Supply | 16.49 | 1 | 16.49 | [Link](#) |
| Robotis | DYNAMIXEL XL330-M288-T | 23.90 | 7 | 167.30 | [Link](#) |
| Robotis | U2D2 Power Hub Board Set | 19.00 | 1 | 19.00 | [Link](#) |
| McMaster | Springs (Robot) | 7.21 | 1 | 7.21 | [Link](#) |

## 3D Printed Parts
### Required Parts
- **Robot Arm Components:** Print the modular parts corresponding to your chosen robotic arm (e.g., Franka, WidowX).
- **Shared Components:**
  - Handle
  - Base
  - Shaft
  - Splint Support

### Suggested Printing Orientation
- Ensure the parts are oriented correctly for strength.
- Use supports for overhanging areas.

## Assembly Instructions
### Step 1: Assemble the Arm
- Attach the 3D printed parts to the motors using screws provided.
- Ensure the screws fit tightly but avoid over-tightening.

### Step 2: Attach the Gripper
- Mount the gripper to the end of the robotic arm.
- Add springs or rubber bands for tension where needed.

### Step 3: Connect the Wires
- Route the wires through the arm, ensuring a clean layout.
- Secure wires with clips or cable ties to avoid interference.

### Step 4: Attach the Controller
- Mount the motor controller to the base of the robot.
- Connect the motors to the controller.

## Software Setup
Clone Repository:
```bash
git clone https://github.com/jordanthuo/vres
cd vres
```

## Example Build
Below is a fully assembled example of the robot arm. Refer to the images for visual guidance during assembly. For videos or additional resources, visit the project website.