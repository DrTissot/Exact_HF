# RF Dataset 0.1-67 GHz: S-parameters for Material Characterization
S-parameter database (0.1-67 GHz) for extracting complex permittivity (epsilon) and loss tangent (delta)

This repository contains a database of **S-parameter** measurements covering a frequency range from **0 to 67 GHz**, generated using **Ansys Electronics Desktop**. The primary purpose of this dataset is to provide the data required for extracting dielectric properties of materials.

## 📌 Project Description
This dataset was created to enable the calculation and analysis of:
* **Complex Permittivity ($\epsilon^*$)**: both real part ($\epsilon'$) and imaginary part ($\epsilon''$).
* **Loss Tangent ($\tan \delta$)**.

The data is particularly useful for researchers and engineers working on RF circuit design, antennas, or material science at millimeter-wave frequencies.

## 📊 Technical Characteristics
* **Frequency Range:** 0.1 GHz to 67 GHz.
* **File Format:** Touchstone (.s1p).
* **Source/Software:** HFSS - Ansys Electronics Desktop.
* **Measured Parameters:** S11 (Magnitude / Phase).
* **Methodology:** Simulation/Measurement of reflection coefficients by coplanar probes (GSG) for material characterization.

## 📂 Repository Structure
* `/data`: Contains all raw `.s1p` measurement files.
* `/docs`: Documentation regarding the simulation setup in Ansys Electronics.
* `LICENSE`: This project is licensed under the GNU General Public License v3.0.

## 🛠 Usage
Since the data is provided in **.s1p** format (1-port), permittivity extraction typically relies on reflection-only methods. Users can implement their own conversion scripts (e.g., in Python or MATLAB) to process these Touchstone files.

## ⚖️ License
This project is distributed under the **GNU General Public License v3.0**. You are free to use, modify, and distribute this data, provided that you keep the same license.

---
GitHub: @DrTissot# Dataset-RF-0-67GHz
S-parameter database (0-67 GHz) for extracting complex permittivity (epsilon) and loss tangent (delta)
