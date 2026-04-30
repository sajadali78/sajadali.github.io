---
title: "Design Of Brushless Hybrid Rotor Machine With Synchronous and Vernier Motor Operation"
collection: thesis
type: "Thesis"
permalink: /thesis/2026-04-30-design-brushless-hybrid-rotor
venue: "Sukkur IBA University"
date: 2026-04-30
location: "Sukkur, Pakistan"
excerpt: "Master's thesis on the design and optimization of a dual-stator brushless synchronous machine for variable-speed applications."
---

## 1. Introduction

Induction motors suffer from low efficiency due to energy losses during conversion, primarily high rotor copper losses proportional to slip. While Wound Rotor Synchronous Machines (WRSM) are a viable alternative, they require brushes and slip rings, which introduce significant maintenance and sparking issues. 

Permanent Magnet Vernier Machines (PMVM) offer high torque density and eliminate the need for mechanical gears, but they are costly due to the heavy reliance on permanent magnets and are generally not suitable for high-speed applications.

To resolve these challenges, **Brushless Excitation Topologies** have been developed.

## 2. Problem Statement & Objectives

There is limited literature on dual-mode operations for the same topology that can efficiently handle both low-speed (Vernier) and high-speed (Synchronous) applications without the maintenance drawbacks of brushes. 

**Key Objectives:**
* **Implementation:** Design a Dual Stator, Dual Mode Brushless machine for variable speeds.
* **Performance:** Achieve higher average torque and significantly reduced torque ripple.
* **Optimization:** Reduce the magnet size for cost efficiency using Genetic Algorithms (GA).

## 3. Proposed Models

We proposed and simulated two brushless models to achieve these objectives:
1. **DMDS-WRSVM:** Brushless Dual Mode Dual Stator non-salient Wound Rotor Synchronous and Vernier Machine.
2. **DMDS-HRSVM:** Brushless Dual Mode Dual Stator Hybrid Rotor Synchronous and Vernier Machine.

### Machine Model Dimensions
* **Stack length:** 100 mm
* **Airgap length I/O:** 0.5 mm
* **Number of stator slots:** 24
* **Stator winding poles:** 02/04

## 4. Key Results

The machine operations were successfully tested for both **High Speed** (Synchronous) and **Low Speed** (Vernier) operations.

### Skew Analysis and Torque Ripple Minimization
Initial models showed a significant harmonic content (73% ripple) due to the 18 slot / 4 pole configuration. By introducing an optimized **4° skewing angle** to the stator and PMS, the harmonic content was dramatically reduced. 

* **Before Skewing:** 73% Ripple
* **After Skewing:** Reduced to ~7% Ripple

### Magnetic Flux Density
The maximum flux density ($B_{max}$) remained within strict design limits (< 2.0T) for both operating modes.

## 5. Optimization 

We utilized a **Genetic Algorithm (GA)** to optimize the design due to its integrated workflow (direct access to Ansys solvers), reduced complexity, and rapid deployment. 

**Optimization Parameters:**
* **Objective:** Minimize the Permanent Magnet (PM) area.
* **Constraints:** 
  * Average Torque $\geq$ 5.5 Nm
  * Torque Ripple $\leq$ 30%

**Optimization Results:**
The magnet size was successfully reduced by nearly 50% without sacrificing performance:
* **Before Optimization:** 227.8 sq mm
* **After Optimization:** 115.8 sq mm

## 6. Conclusion

* Successfully designed the DMDS-HRSVM and DMDS-WRSVM models.
* Completed rigorous simulations for both high-speed and low-speed operations.
* Parametrized design variables for PMs to seamlessly run optimizations.
* Optimized and significantly reduced magnet size, cutting costs while maintaining performance.

---

*Note: All diagrams, parametric results, and waveforms (including Back-EMF, output torque, and harmonic spectrums) were extracted and verified using Ansys Maxwell simulations.*
