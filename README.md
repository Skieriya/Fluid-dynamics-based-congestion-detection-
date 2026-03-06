
# 🚦 Fluid Dynamics Traffic Simulation

A physics-inspired traffic simulation that models traffic as a continuous fluid system using simplified Navier–Stokes equations.

Instead of modeling individual vehicles, the system treats traffic as a density and velocity field, allowing the simulation of:

- congestion waves
- adaptive traffic lights
- emergency vehicle path clearing
- flyovers and topography effects
- turbulence-like traffic behavior

This approach bridges fluid mechanics, physics simulation, and intelligent traffic control.

---

# 🧠 Core Idea

Traffic flow behaves similarly to compressible fluid flow.

The simulation models:

- Density (ρ) → vehicles per unit area
- Velocity field (v) → traffic speed and direction
- Pressure (P) → congestion pressure

Using simplified forms of the continuity equation and Navier-Stokes equations.

## Continuity Equation

∂ρ/∂t + ∇·(ρv) = 0

Ensures conservation of vehicles in the system.

## Momentum Equation

∂v/∂t + (v · ∇)v = -∇P/ρ + ν∇²v

Where:

- ρ = traffic density
- v = velocity field
- P = traffic pressure
- ν = viscosity (driver behavior / friction)

---

# 🧪 Simulation Results

Test configuration:

Grid Size: 100 × 100  
Time Step: 0.1  
Road Layout: Four-way intersection  
Simulation Length: 500 steps

<img width="1453" height="599" alt="image" src="https://github.com/user-attachments/assets/536ad5b3-0cd6-4fcf-994c-b62a8b0ec333" />
<img width="1465" height="588" alt="image" src="https://github.com/user-attachments/assets/8c11bac0-4154-4239-b66e-ccf1f427f024" />
<img width="1467" height="597" alt="image" src="https://github.com/user-attachments/assets/80b06f29-3c8b-4585-8e11-f158fe102922" />
<img width="1441" height="600" alt="image" src="https://github.com/user-attachments/assets/3801f76b-2d26-4c2d-af6d-3966bbc4197c" />
<img width="1450" height="598" alt="image" src="https://github.com/user-attachments/assets/ff24bed5-923e-4b59-a9b8-800109f31701" />


