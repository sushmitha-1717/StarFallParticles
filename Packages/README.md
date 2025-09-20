# StarfallParticles

## 🌌 Overview
StarfallParticles is an interactive 3D particle system created in Unity that simulates a beautiful starfall effect. Users can toggle particle emission and dynamically change particle colors in real-time. This project demonstrates Unity’s Particle System, scripting, scene setup, and interactive features.  

It is ideal for learning interactive particle effects or integrating into games and simulations.

---

## 🎯 Motivation
The project aims to explore Unity’s particle system capabilities and interactive scripting. It provides hands-on experience with:
- Particle emission control
- Color gradients and particle fading
- Real-time keyboard interactions
- 3D scene lighting, camera setup, and material application

---

## 🌟 Features
- Real-time falling stars effect
- Press **Space** → Start/Stop particle emission
- Press **C** → Randomize particle colors
- Adjustable particle properties: speed, lifetime, size, color gradient
- Night sky environment with directional lighting and ground plane
- Additive shader for glowing particle effects
- Easy to extend and integrate into other Unity projects

---

PROCESS :
Create New Project:

Open Unity Hub → New Project → 3D (Core) template → Name: StarfallParticles → Create.

Save Scene:

File → Save As… → Scenes/Starfall.unity (create Scenes folder).

Add Ground Plane:

Hierarchy → 3D Object → Plane → rename Ground

Position: (0,0,0), Scale: (10,1,10)

Create Material GroundMat (Dark blue/gray) → assign to Plane

Lighting & Skybox:

Directional Light → Rotation: (30,30,0)

Add Skybox (default or free “Night Sky”)

Add Particle System:

Hierarchy → Effects → Particle System → rename Starfall

Main Module: Duration 5, Looping, Start Lifetime 4, Speed 3, Size 0.15, Color White, Simulation Space: World

Configure Shape & Emission:

Shape: Cone → Angle 20, Radius 5, Position (0,6,0)

Emission: Rate over Time 40 (optional bursts)

Velocity, Color & Size over Lifetime:

Velocity Y = -1, Color Gradient: White → Light Blue → Purple, Size: Start 1 → End 0

Particle Renderer:

Render Mode: Billboard, Material: StarMat → Shader: Particles/Standard Unlit → Additive

Add Script (Interactivity):

Create StarController script → attach to Starfall

Controls:

Space → Toggle emission

C → Randomize particle colors

Adjust Camera:

Position: (0,2,-8), Rotation: (10,0,0)

Save & Test:

File → Save → Press Play → check particle emission, color change, and camera view

🎥:Execution 



https://github.com/user-attachments/assets/5c014b7a-71d5-45d7-af6c-0c8a4fdfd8a9





https://github.com/user-attachments/assets/9873c0d4-55df-4f57-b3c5-e033877a01e4


