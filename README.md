# 🎯 AR Math Visualizer & VR Shooting Game (Unity Projects)
This repository contains two complete Unity-based immersive applications:

1. **AR Math Visualizer** – An Augmented Reality application that detects surfaces and places 3D mathematical shapes (Cube, Cylinder, Arch) and displays formulas for each.  
2. **VR Shooting Game** – A simple first-person VR shooter built using Unity XR, with weapon mechanics, enemy targets, and interactive gameplay.

Both projects are beginner–friendly, well-structured, and suitable for academic submissions, internship tasks, demo portfolios, and Unity learning paths.

---

## 📌 Table of Contents
- [Project 1: AR Math Visualizer](#-project-1-ar-math-visualizer)
  - Features
  - Requirements
  - How It Works
  - Installation & Setup
  - Controls
  - Project Structure
  - Testing Instructions
- [Project 2: VR Shooting Game](#-project-2-vr-shooting-game)
  - Features
  - Requirements
  - Installation & Setup
  - Controls
  - Project Structure
  - Testing Instructions
- [Screenshots (Placeholders)](#-screenshots)
- [Future Scope](#-future-scope)
- [How to Run/Build APK](#-how-to-runbuild-apk)
- [Author](#-author)

---

# 🚀 **Project 1: AR Math Visualizer**

## 📌 Overview
AR Math Visualizer is a Unity AR Foundation application that:
- Detects real-world surfaces  
- Places 3D objects (Cube, Cylinder, Arch)  
- Displays formulas for Volume/Area  
- Allows moving, rotating, scaling and deleting objects  

This project is designed to help students visualize mathematical 3D shapes in real space.

---

## ⭐ **Features**
- ✔ Surface detection (AR Plane Detection)  
- ✔ Tap to place 3D objects  
- ✔ UI buttons for Cube / Cylinder / Arch  
- ✔ Display mathematical formulas  
- ✔ Move, Rotate, Scale (Gesture support)  
- ✔ Delete object  
- ✔ Lightweight and beginner-friendly  

---

## 🛠️ **Tech Stack**
- Unity 2021/2022/2023  
- C# Scripts  
- AR Foundation  
- ARCore XR Plugin / ARKit XR Plugin  

---

## 📁 **Project Structure**
AR-Math-Visualizer/
├── Assets/
│ ├── Scripts/
│ │ ├── ARPlacementManager.cs
│ │ ├── ObjectManipulator.cs
│ │ ├── UIManager.cs
│ ├── Prefabs/
│ │ ├── Cube.prefab
│ │ ├── Cylinder.prefab
│ │ ├── Arch.prefab
│ ├── UI/
│ ├── Buttons, Panels, Formula Texts
├── Scenes/
│ ├── ARScene.unity
├── README.md

---

## 🔧 **Installation & Setup**
1. Install **Unity Hub**  
2. Use Template: **3D (URP optional)**  
3. Install:
   - AR Foundation  
   - ARCore XR Plugin (Android)  
   - ARKit XR Plugin (iOS)  
4. Switch Build Platform to **Android**  
5. Enable ARCore in Project Settings → XR  

---

## 🎮 **Controls**
| Action | Gesture / Button |
|--------|------------------|
| Place Object | Tap on screen |
| Move | Drag |
| Rotate | Two-finger twist |
| Scale | Pinch gesture |
| Delete | Delete button |

---

## 🧪 **Testing Instructions**
- Use a physical Android device  
- Ensure ARCore is supported  
- Build & Run from Unity  
- Allow camera permissions  
- Point camera at a surface until yellow/white AR plane appears  
- Tap to place object  
- Use gestures for manipulation  

---

---

# 🔫 **Project 2: VR Shooting Game (Unity XR)**

## 📌 Overview
This is a VR First-Person Shooting game built using Unity XR.  
The player shoots targets using a VR controller with simple gameplay mechanics.

---

## ⭐ **Features**
- ✔ First-person shooting system  
- ✔ Gun firing mechanics  
- ✔ Enemy/target objects  
- ✔ Damage system  
- ✔ Functional main menu (Play button)  
- ✔ Custom background  
- ✔ Removed minimap, ammo bar, reload bar (as required)  
- ✔ WebGL or APK build  

---

## 🛠️ **Tech Stack**
- Unity 2021+  
- XR Interaction Toolkit  
- Oculus / OpenXR  
- C# Scripts  
- Unity Input System  

---

## 📁 **Project Structure**
VR-Shooting-Game/
├── Assets/
│ ├── Scripts/
│ │ ├── GunController.cs
│ │ ├── Target.cs
│ │ ├── GameManager.cs
│ ├── Prefabs/
│ ├── Scenes/
│ ├── IntroMenu.unity
│ ├── MainLevel.unity
├── README.md

---

## 🔧 **Installation & Setup**
1. Install Unity Hub  
2. Create **3D Core** project  
3. Add XR packages:
   - XR Interaction Toolkit  
   - OpenXR Plugin  
4. Project Settings → XR Plug-in Management → Enable OpenXR  
5. Connect VR Device (Oculus/Meta/XR Headset)  

---

## 🎮 **Controls**
| Action | Control |
|--------|---------|
| Shoot | Trigger button |
| Move | Joystick (if enabled) |
| Reload | Auto / disabled depending on version |
| Select Menu | Ray Interactor |

---

## 🧪 **Testing Instructions**
### For Windows + Oculus
- Connect VR headset  
- Press Play in Unity (VR Mode)  
- Stand in play area, aim gun, shoot targets  

### For WebGL
- Build → WebGL  
- Host on local server or GitHub Pages  

---

# 🚀 **Future Scope**
### AR Project
- Add more shapes (Sphere, Cone, Prism)  
- Voice input for shape placement  
- Step-by-step math tutorials  

### VR Shooting Game
- Add enemy AI  
- Add levels, scoring system, power-ups  
- Multiplayer support  

---

# 📦 How to Build / Run APK
### For Android (AR or VR)
1. File → Build Settings  
2. Select **Android**  
3. Switch Platform  
4. Player Settings:
   - Minimum API Level 24+  
   - ARM64  
5. Press **Build**  
6. Transfer APK to device  
7. Install manually  

---
