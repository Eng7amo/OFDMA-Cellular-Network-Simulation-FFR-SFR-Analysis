# OFDMA Cellular Network Simulation: FFR & SFR Analysis  

This repository contains simulations and analysis of **Frequency Reuse Strategies** in **OFDMA-based cellular networks**, focusing on **Strict Fractional Frequency Reuse (FFR) and Soft Frequency Reuse (SFR)**. The project evaluates the impact of different frequency reuse schemes on **sub-band allocation, spectral efficiency, and SINR performance**.

## 🚀 Features  
- **Mathematical modeling of Strict FFR & SFR**.  
- **Simulation of resource allocation** based on interior radius.  
- **Visualization of sub-band distribution** across different frequency reuse schemes.  
- **Comparative analysis of frequency reuse techniques in OFDMA networks**.  

## 📂 Project Structure  
📁 OFDMA_FFR_SFR_Simulation │── 📜 Mobile_Comm_Final_Presentation.ipynb # Main Jupyter Notebook │── 📜 requirements.txt # Dependencies list │── 📜 README.md # Project documentation │── 📁 data/ # Datasets or parameters used │── 📁 figures/ # Generated plots and visualizations

## 📌 Installation  
### 1️⃣ Clone the repository  
git clone https://github.com/yourusername/OFDMA_FFR_SFR_Simulation.git
cd OFDMA_FFR_SFR_Simulation

### 2️⃣ Create a virtual environment (optional but recommended)
python -m venv ofdma_env
source ofdma_env/bin/activate  # On Windows: ofdma_env\Scripts\activate

### 3️⃣ Install dependencies
pip install -r requirements.txt

### 🛠 Usage
Run the Jupyter Notebook
jupyter notebook
Open Mobile_Comm_Final_Presentation.ipynb and execute the cells to visualize sub-band allocation and frequency reuse performance.

### 🔍 How It Works
Strict FFR Calculation:

Computes the number of sub-bands allocated for interior and exterior zones.

Uses a strict allocation policy to optimize interference.

SFR Calculation:

Dynamically allocates sub-bands based on interior radius.

Uses a flexible power control factor (β) to enhance cell-edge performance.

Visualization:

Plots the percentage of total sub-bands allocated for different reuse schemes.

Compares Strict FFR, SFR, and Universal Reuse (N=1).

### 📊 Analysis
Evaluates how cell radius and power allocation impact network efficiency.

Analyzes spectral efficiency under different reuse schemes.

Compares strict and flexible reuse strategies for OFDMA-based networks.

### 🤝 Contribution
Feel free to contribute by creating pull requests or reporting issues in the Issues section.
.

### 📜 License
This project is licensed under the MIT License.
