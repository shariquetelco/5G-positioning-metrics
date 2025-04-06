<p align="center">
  <img src="IABG_Logo.png" alt="IABG Logo" width="250"/>
</p>

<h1 align="center">5G Positioning Raw Measurement Dataset</h1>

<p align="center">
  <a href="https://github.com/your-repo-link"><img alt="License" src="https://img.shields.io/badge/license-MIT-blue.svg"></a>
  <a href="#"><img alt="MATLAB" src="https://img.shields.io/badge/MATLAB-2023b-orange"></a>
  <a href="#"><img alt="Dataset" src="https://img.shields.io/badge/data-available-brightgreen"></a>
  <a href="#"><img alt="Conference" src="https://img.shields.io/badge/MedComNet-2024-blueviolet"></a>
</p>

# 5G Positioning Raw Measurement Dataset
This repository provides raw datasets of 5G positioning measurements generated using a realistic simulation environment with a MATLAB-based ray tracing tool. The data has been analyzed as part of a research paper submitted to MedComNet 2024, taking place in June 2024 in Nice, France.


Each row of the datasets is composed of the following:
- Base Station (BS) coordinates (x, y, z)
- User Equipment (UE) coordinates (x, y, z)
- Raw measurements (TDOA/AOA/TOA)
- Timestamp of measurement acquisition (1-100)

For each UE position, 100 Monte-Carlo simulations are performed. The timestamp indicates in which Monte-Carlo simulation the measurement is acquired.
The first BS for each timestamp is the reference BS used to compute the TDOA; therefore, no TDOA measurement is shown for that BS.
<p align="center">
  <img src="https://github.com/Ita97/ICASSP2024_5G_pos_meas/assets/28793450/95bd75bd-5e05-445e-b456-8e47111b804e"  width="500"  /></center>
</p>

---

## 📡 Overview

This repository provides a dataset of **5G positioning raw measurements**, simulated in a realistic radio environment using a MATLAB-based ray tracing tool. The data supports high-precision localization studies and reflects practical propagation behavior in 5G networks.

These measurements were analyzed in a paper submitted to **MedComNet 2024**, taking place in **June 2024 in Nice, France**.

---

## 📦 Dataset Contents

- Raw ray-traced measurement data  
- Multiple urban/suburban scenarios  
- Ground-truth position labels  
- MATLAB scripts for parsing and visualization  

---

## 🛠 Requirements

- MATLAB R2023b or newer  
- Signal Processing Toolbox  
- Phased Array System Toolbox  

---

## 📂 Repository Structure


