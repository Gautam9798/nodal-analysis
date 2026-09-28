
# ⛽ Nodal Analysis – Petroleum Engineering

A Python-based **Nodal Analysis** project to evaluate well performance by combining **Inflow Performance Relationship (IPR)** and **Tubing Performance Relationship (TPR)** curves.

The objective is to visualize the relationship between production rate and flowing bottom-hole pressure and identify the operating behavior of a well under different tubing conditions.

## 📌 Project Overview

This project demonstrates:

- 📈 **IPR Curve** – Represents reservoir inflow performance.
- 🛢️ **TPR Curves** – Represents tubing/outflow performance for different tubing sizes.
- 🔄 **Nodal Analysis** – Combines IPR and TPR to study well operating conditions.
- 📊 **Python Visualization** – Uses Matplotlib to plot and compare performance curves.

## 🧮 Methodology

The project uses production-rate and flowing bottom-hole pressure data to construct the IPR curve.

TPR curves are evaluated for different tubing sizes:

- **1.90 in**
- **2.375 in**
- **2.875 in**

The IPR and TPR curves are plotted together to visualize their intersection and analyze the well's operating point.

## 🛠️ Tools Used

- Python
- NumPy
- Pandas
- Matplotlib
- Jupyter Notebook

## 📊 Output

The final plot compares:

- IPR
- TPR at 1.90 in tubing
- TPR at 2.375 in tubing
- TPR at 2.875 in tubing

The graph uses:

- **X-axis:** Production Rate (MMscf/d)
- **Y-axis:** Flowing Bottom-Hole Pressure (psi)

## 📁 Project Files

```text
nodal-analysis/
│
├── NodalAnalysis.ipynb
├── Dataset 1.png
├── Dataset 2.png
└── README.md
