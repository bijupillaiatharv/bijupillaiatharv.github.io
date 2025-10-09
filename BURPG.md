---
title: BURPG
filename: BURPG.md
---
Go to [Home](README.md)
## Boston University Rocket Propulsion Group
### Argo
**Specificiations:**
  * Category: Bipropellant Launch Vehicle (IPA/N2O)
  * Goal Altitude: 100,000 ft
  * Thrust: 1750 lbf
  * Size: 8 in OD, 22+ ft long

**Contributions:**
  * Designed pressure vessels to hold fuel and oxidizer
    * Sized radial bolts to ensure tank can withstand internal pressure and external thrust loads
    * Created Python script that models the blowdown of the fuel tank to approximate necessary ullage volume
    * Simulated an bang-bang accumulator system in Python and weighed its fidelity in providing constant ullage pressure in the fuel tank
    * Simulated autogenous pressurization of nitrous oxide in Python to refine performance metrics
    * Ran finite element analysis on tank domes to verify design
  * Intertank Fluids Lead
    * Ensure proper routing, valve selection and sizing of intertank fluids components
    * Responsible for designing fuel/ox dump, vent, and relief systems on vehicle
    * Guide team members through the design, build, test process for this subsystem

| FEA Element | Image | Simulation Element | Image |
| --- | --- | --- | --- |
| Dome Loads and Fixtures 1 | <img src="/images/DomeFixtures1.png" width="50%" height="auto"> | Dome Loads and Fixtures 2 | <img src="/images/DomeFixtures2.png" width="50%" height="auto"> |
| Dome Mesh | <img src="/images/DomeMesh.png" width="50%" height="auto"> | Dome VonMises Plot | <img src="/images/DomeVonMises.png" width="50%" height="auto"> |
| Dome FOS Plot | <img src="/images/DomeFOS.png" width="50%" height="auto"> |

| Python Simulation Element | Image | 
| --- | --- |
| Fuel Blowdown Simulation | <img src="/images/BlowdownSimulation.png" width="50%" height="auto"> |
| Fuel Bang Bang Simulation | <img src="/images/BangBangSimulation.png" width="50%" height="auto"> |
| Oxidizer Autogenous Pressurization Simulation | <img src="/images/AutogenousPressurization.png" width="50%" height="auto"> |

### Icarus
**Specifications:**
  * Altitude: 13,000 ft
  * Thrust: 2200 lbf
  * Type: Bipropellant (IPA/N2O)
  * Size: 8in OD, 17 ft long

**Contributions:**
  * Designed 3D printed wire cover to secure avionics downcomer wire and improve aerodynamics
    * Ensured 3D printed fixtures interfaced with intertank, thrust structure, and avionics bay
  * Supported flight readiness test campaign through test infrastructure setup
  * Designed avionics D-subminiature covers to protect wire harnessing

| Description | Image | Image |
| --- | --- | --- |
| Team Photos | <img src="/images/TeamPhoto2.JPEG" width="50%" height="auto"> | <img src="/images/TeamPhoto1.JPEG" width="50%" height="auto"> |
| Wire Cover | <img src="/images/WireCover.png" width="50%" height="auto"> | <img src="/images/WireCover2.jpg" width="50%" height="auto"> |


### VEGAS
**Specifications:**
  * Category: Bipropellant Test Stand (IPA/N2O)
  * Max Thrust Supported: 600 lbf
  * Use Cases: Rapid deployment and testing of small-scale rocket elements, utilize test data for full size designs

**Contributions**
  * Designed fuel-centered carbon steel pintle injector
  * Sized pintle holes and annular sleeve to ensure proper mass flow rates of fuel and oxidizer
  * Ran fluid simulations to ensure injector stiffness is suffcient
  * Coordinated with other subteams to accomodate interfacing methods

| Version | Design | Version | Design | Version | Design |
| --- | --- | --- | --- | --- | --- |
| Version 1 | <img src="/images/PintleInjectorV1.png" width="50%" height="auto"> | Version 2 | <img src="/images/PintleInjectorV2.png" width="50%" height="auto"> | Version 3 | <img src="/images/PintleInjectorV3.png" width="50%" height="auto"> |
| Version 4 | <img src="/images/PintleInjectorV4.png" width="50%" height="auto"> | Version 5 | <img src="/images/PintleInjectorV5.png" width="50%" height="auto"> | Version 6 | <img src="/images/PintleInjectorV6.png" width="50%" height="auto"> |
| Version 7 | <img src="/images/PintleInjectorV7.png" width="50%" height="auto"> | Version 8 | <img src="/images/PintleInjectorV8.png" width="50%" height="auto"> | Version 9 | <img src="/images/PintleInjectorV9.png" width="50%" height="auto"> |

### Hybrid Intro Project
**Specifications:**
  * Category: Hybrid Rocket Nozzle + Accompanying Flight Computer (Paraffin Wax/GOx)
  * Thrust: 10 lbf
  * Use Cases: allows incoming members of the team to acclimate themselves with the engineering design process and fundamental rocketry concepts

**Contributions**
  * Co-led the an introductory project where I helped guide new members in sizing and printing a hybrid rocket nozzle
  * Held office hours to solidify basic rocketry concepts from Rocket Propulsion Elements (Sutton & Bilbarz)
  * Led three sets of design reviews to provide feedback for their design
    * Corrected mistakes made in nozzle sizing calculations
    * Critique FEA analyses and engineering drawings
    * Provided feedback on design review best practices

| Description | Image |
| --- | --- |
| My group's firing from when I was a freshman. | <img src="/images/HIPFiring.png" width="50%" height="auto"> |
