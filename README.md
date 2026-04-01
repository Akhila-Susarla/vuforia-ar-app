<div align="center">

# Vuforia AR App

<img src="https://img.shields.io/badge/Unity-2019.2.9f1-000000?style=for-the-badge&logo=unity&logoColor=white" />
<img src="https://img.shields.io/badge/C%23-Scripts-239120?style=for-the-badge&logo=csharp&logoColor=white" />
<img src="https://img.shields.io/badge/Vuforia-8.3.9-E05A22?style=for-the-badge" />
<img src="https://img.shields.io/badge/Platform-Android%20%7C%20iOS-3DDC84?style=for-the-badge&logo=android&logoColor=white" />
<img src="https://img.shields.io/badge/Type-Marker--Based%20AR-6366f1?style=for-the-badge" />

<br/>

*Image-target AR experience built with Vuforia Engine — point your phone at a physical marker and watch 3D content come to life.*

</div>

---

## Overview

This Unity project uses **Vuforia Engine 8.3.9** to detect physical image targets (printed markers) through a mobile camera and overlay augmented reality content on top of them. Built as part of an undergraduate AR/VR development course.

**How it works:** Vuforia continuously scans the camera feed for a registered image target (`DemoSAR`). When the marker is recognized, a virtual 3D object is anchored to it in world space and tracks with any movement of the physical card.

---

## How to Open

1. Install **Unity 2019.2.9f1** (via Unity Hub)
2. Clone this repo and open the `AR App` folder as a Unity project
3. Import Vuforia Engine from the Unity Package Manager or Asset Store
4. Open `Assets/Scenes/SampleScene.unity`
5. Build and deploy to Android or iOS

---

## Tech Stack

| Tool | Version | Purpose |
|---|---|---|
| Unity | 2019.2.9f1 | Game engine |
| Vuforia Engine | 8.3.9 | Image target detection & AR tracking |
| C# | — | Scripting |

---

<div align="center">

Built by [Akhila Susarla](https://github.com/Akhila-Susarla) · Undergrad AR/VR Course

</div>
