# Two-Element Planar Microstrip Patch Antenna Array Design

## Introduction

This project presents the design and simulation of a **two-element planar microstrip patch antenna array** using **Ansys HFSS**. The objective was to investigate the effect of combining two patch antenna elements to improve antenna gain and directivity while maintaining a compact structure suitable for wireless communication applications.

Microstrip patch antennas are widely used because of their low profile, lightweight construction, ease of fabrication, and compatibility with printed circuit board (PCB) technology.

---

# Antenna Structure

The antenna consists of the following components:

## Ground Plane

The ground plane is placed beneath the substrate and acts as the reference conductor.

Functions:

- Provides return current path
- Reflects electromagnetic waves toward the radiating patch
- Reduces back radiation
- Improves radiation efficiency

---

## Dielectric Substrate

The substrate separates the radiating patch from the ground plane.

Its dielectric constant influences:

- Resonant frequency
- Antenna bandwidth
- Radiation efficiency
- Patch dimensions

---

## Patch Elements

The antenna consists of **two rectangular microstrip patches** connected through a corporate feed network.

The dimensions of the patch determine the operating frequency.

---

## Feed Network

A microstrip corporate feed network is used to equally distribute power to both antenna elements.

Benefits:

- Uniform power distribution
- Better impedance matching
- Improved radiation characteristics

---

## Excitation

A Lumped Port is assigned at the feed line to excite the antenna during simulation.

---

## Radiation Boundary

An air box surrounding the antenna is created and assigned a Radiation Boundary.

Purpose:

- Simulates free-space conditions
- Prevents wave reflections from simulation boundaries

---

# HFSS Simulation Procedure

The simulation was performed using the following workflow:

1. Create the ground plane.
2. Design the dielectric substrate.
3. Draw two rectangular patch elements.
4. Design the corporate feed network.
5. Assign material properties.
6. Create surrounding air box.
7. Assign Radiation Boundary.
8. Assign Lumped Port excitation.
9. Configure Solution Setup.
10. Define Frequency Sweep.
11. Run electromagnetic simulation.
12. Evaluate antenna performance.

---

# Performance Evaluation

The antenna performance was evaluated using:

## Terminal S-Parameter (S11)

Measures the amount of reflected power.

Lower S11 values indicate better impedance matching.

---

## Gain

Represents the antenna's ability to radiate energy in a desired direction.

The simulated antenna achieved approximately **3 dBi gain**.

---

## Radiation Pattern

The radiation pattern illustrates the directional characteristics of the antenna and helps evaluate beam direction and directivity.

---

# Simulation Results

The repository contains:

- Antenna Design
- Terminal S-Parameter (S11)
- Gain Plot
- Radiation Pattern

---

# Conclusion

The two-element planar array demonstrated improved gain and directivity compared to a single patch antenna, making it suitable for microwave wireless communication applications.
