<img width="1434" height="817" alt="image" src="https://github.com/user-attachments/assets/ef979e38-832e-4e31-b66b-f17f00e02e88" />
<img width="1434" height="817" alt="image" src="https://github.com/user-attachments/assets/ef979e38-832e-4e31-b66b-f17f00e02e88" />


# Pulse-Doppler Radar Range & Velocity Estimation

## 🎯 Overview
This project is a MATLAB-based simulation of a Pulse-Doppler Radar system. It demonstrates the fundamental principles of Digital Signal Processing (DSP) used in modern radar systems to detect a target's distance and its speed through noise.

## 📡 Key Features
- **Pulse Generation:** Simulates a pulse-modulated carrier signal.
- **Noise Modeling:** Implements Additive White Gaussian Noise (AWGN) to simulate real-world atmospheric interference.
- **Matched Filtering:** Uses Cross-Correlation to recover the signal from a low SNR environment.
- **Doppler Processing:** Utilizes Fast Fourier Transform (FFT) to calculate the frequency shift and estimate target velocity.

## 🛠️ Concepts Demonstrated
- **Time of Flight (ToF):** $Range = \frac{(c \times \Delta t)}{2}$
- **Doppler Shift:** $f_d = \frac{2 \cdot v \cdot f_c}{c}$
- **Sampling Theory:** Selection of $f_s$ to avoid aliasing.

## 📊 Results
When the simulation is run, it produces two primary outputs:
1. **Time Domain Plot:** Shows the correlation peak which identifies the target's distance.
2. **Frequency Domain Plot:** Shows the Doppler shift peak which identifies the target's speed.



## 🚀 How to Run
1. Clone this repository: `git clone https://github.com/YourUsername/Radar-DSP-Project.git`
2. Open MATLAB.
3. Run `src/radar_doppler.m`.

## 🎓 Author
**Pranathi**
*Avinya Institute*
*Focus: Cybersecurity & Signal Processing*
