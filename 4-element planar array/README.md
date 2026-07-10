# Four-Element Planar Microstrip Patch Antenna Array Design

## Introduction

This project presents the design and simulation of a **four-element planar microstrip patch antenna array** using **Ansys HFSS**. By increasing the number of radiating elements, the antenna achieves higher gain, improved directivity, and better radiation performance.

The antenna was analyzed using full-wave electromagnetic simulation to evaluate its performance over multiple resonant frequencies.

---

# Antenna Structure

The antenna consists of:

- Ground Plane
- Dielectric Substrate
- Four Rectangular Patch Elements
- Corporate Feed Network
- Lumped Port Excitation
- Radiation Boundary (Air Box)

---

# Ground Plane

Provides the reference conductor and improves antenna efficiency by minimizing back radiation.

---

# Dielectric Substrate

Supports the patch elements while influencing antenna bandwidth, resonant frequency, and radiation characteristics.

---

# Patch Elements

Four identical rectangular microstrip patches are arranged in a planar configuration.

The array configuration improves:

- Gain
- Directivity
- Radiation efficiency

---

# Corporate Feed Network

The feed network equally distributes RF power to all four patch elements.

Advantages include:

- Uniform excitation
- Better impedance matching
- Improved radiation performance

---

# Excitation

A Lumped Port is assigned to excite the feed network during simulation.

---

# Radiation Boundary

A radiation boundary enclosing the antenna simulates free-space propagation by absorbing outgoing electromagnetic waves.

---

# HFSS Simulation Procedure

1. Design the ground plane.
2. Create dielectric substrate.
3. Design four rectangular patch elements.
4. Construct corporate feed network.
5. Assign materials.
6. Create air box.
7. Apply Radiation Boundary.
8. Assign Lumped Port.
9. Configure Solution Setup.
10. Perform Frequency Sweep.
11. Simulate the antenna.
12. Analyze simulation results.

---

# Performance Evaluation

## Terminal S-Parameter (S11)

The antenna exhibited multiple resonant frequencies.

The best resonance occurred near **6.62 GHz**, achieving approximately **−39 dB** return loss.

---

## Gain

The four-element array achieved approximately **6 dBi gain**, demonstrating improved radiation performance compared to the two-element array.

---

## Radiation Pattern

The radiation pattern confirms increased directivity resulting from the additional antenna elements.

---

# Simulation Results

The repository contains:

- Antenna Design
- Terminal S-Parameter (S11)
- Gain Plot
- Radiation Pattern

---

# Conclusion

The four-element planar microstrip patch antenna array provides higher gain and improved directivity compared to the two-element configuration, demonstrating the advantages of planar antenna arrays for microwave wireless communication systems.
