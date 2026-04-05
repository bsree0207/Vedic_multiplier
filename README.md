# 2x2 Vedic Multiplier using 90nm CMOS

## 📌 Overview
This project implements a **2x2 bit Vedic Multiplier** based on the Urdhva Tiryagbhyam (vertical & crosswise) algorithm.

## ⚙️ Design Details
- Technology: 90nm CMOS
- Tool: Cadence / Synopsys
- Components:
  - 4 AND gates
  - 2 Full Adders

## 🧠 Working Principle
The multiplier follows:
S0 = A0 × B0  
S1 = (A1 × B0) + (A0 × B1)  
S2 = (A1 × B1) + Carry  

## 🚀 Features
- Reduced delay
- Low power consumption
- Efficient parallel computation

## 📊 Results
- Delay: ~47.7 ps  
- Power: ~22.96 µW (with 13T HFA)  
- Full voltage swing output  

## 📷 Outputs
<img width="984" height="594" alt="image" src="https://github.com/user-attachments/assets/b63473bf-d396-4919-ad46-2324222ce793" />


## 📚 Reference
Based on Vedic Mathematics algorithm and CMOS implementation.
