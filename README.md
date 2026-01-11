# Unmanned drone simulation in Paris

## Project description
This project is a Unity simulation of an unmanned drone flying over Paris.  
The environment is generated using **Cesium for Unity**, providing real-world 3D geographic data.

The project aims to simulate drone navigation in a realistic urban environment and after to be implemented in a VR mode.

---

## Project goal
- Simulate the flight of an unmanned drone
- Explore Paris using real-world 3D data
- Control a drone inside a realistic city environment

---

## Drone controls (Non-VR Mode)

The drone can be controlled using the keyboard:

- **z** → Move forward  
- **S** → Move backward  
- **J** → Move left  
- **L** → Move right  

Drone movement is handled using C# scripts and Unity physics.


## VR Implementation (Work in Progress)

A VR version of the project was planned using the **XR Interaction Toolkit**.

### Current status
- XR Interaction Toolkit installed
- XR Origin (XR Rig) created
- Input System configured
- Locomotion System and movement providers added
- Initial VR movement scripts created

### Limitations
- The VR implementation could not be fully tested
- VR movement is incomplete and not fully functional
- The project currently works mainly in non-VR mode

---

## Unity version and compatibility (Important)

This project was developed using: Unity 2022.3.62f1 (LTS)

The **Unity 6 version was not used**, as significant compatibility issues were encountered when installing **Cesium for Unity**.  
For this reason, the project was intentionally created with **Unity 2022.3 LTS** which is fully supported by Cesium.

⚠️ **Important notice**:
- Opening this project with **Unity 6 may cause errors**
- Opening a Unity 2022 project in Unity 6 can **override or break project settings**
- This issue was encountered during development and caused project instability

👉 **It is strongly recommended to open this project using Unity 2022.3.62f1** via Unity Hub.

---

## Main scene

The main Unity scene of the project is Projet1unmanned.unity. 


This scene contains:
- The drone GameObject
- Cesium georeferencing configuration
- Paris 3D environment
- Camera and control setup

---

## Technologies used
- Unity 2022.3.62f1 (LTS)
- C#
- Cesium for Unity
- XR Interaction Toolkit (partially configured)






