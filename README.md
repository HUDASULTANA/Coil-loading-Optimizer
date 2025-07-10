# 🚄 Coil Loading Optimizer Tool

An intelligent and automated tool designed to optimize the loading of Hot Rolled Coils (HRC) into railway wagons at **JSW Steel, Dolvi Works**, aiming to **minimize dead freight** and improve operational efficiency.

---

## 📌 Problem Statement

A significant portion of wagon capacity was going unutilized due to mismatched coil weights, resulting in **dead freight averaging ~20%** and costing **over ₹6 crore per month**. Manual planning lacked precision and efficiency, especially under weight uniformity constraints and coil placement rules.

---

## 🎯 Solution Overview

This tool uses a **greedy approximation algorithm** to:
- **Group coils** into valid triplets or duplets based on weight difference rules.
- **Match coil groups** to wagon capacities efficiently.
- Ensure **100% coil utilization** and **minimum dead weight**.
- Handle mixed wagon types (e.g., BFNV, BRN, BOXN, etc.) with varying capacities.

---

## ⚙️ Features

- 📦 Supports **multiple wagon types** with custom capacities.
- 🧠 Applies **coil grouping rules**:
  - Max 2T weight difference in a wagon.
  - Middle coil must be lighter than both ends.
- 📊 Outputs **Excel sheets** with wagon-wise coil assignments.
- 🧮 Calculates total utilized weight and dead freight.
- 🧪 Easy testing with dummy datasets or real-time data.

---

## 🖥️ How to Use

1. Clone the repo:
   ```bash
   git clone https://github.com/HUDASULTANA/Coil-loading-Optimizer.git
   cd Coil-loading-Optimizer
