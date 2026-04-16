# Ansys HFSS Simulation Setup (Coplanar Lines)

This document details the specific configuration used to generate the S-parameter dataset.

## 🛠 Simulation Environment
* **Software:** Ansys HFSS
* **Geometry:** Coplanar Lines (CPW - Coplanar Waveguide and CPWG - Coplanar Waveguide with Ground).
* **Excitation:** Waveport (calibrated for coplanar topology).
* **Reference Impedance ($Z_0$):** 50 $\Omega$.

## 📐 Model Details
* **Dimensions:** Elements on the order of **200 µm** (center trace width and gaps).
* **Material Under Test (MUT):** Placed in interaction with the line's evanescent field. For CPWG structures, the bottom ground plane ensures better field confinement at high frequencies.
* **Frequency Range:** Sweep from 0.1 GHz to 67 GHz.

## 🔬 Characterization Method
CPW and CPWG topologies are preferred as they allow for broadband characterization with direct contact, while minimizing radiation losses at 67 GHz. The $S_{11}$ signal captured at the Waveport depends on the effective dielectric constant of the line, which is modified by the presence of the tested material. The extraction consists of isolating the material's contribution based on the phase shift and amplitude variation of the reflected signal.
