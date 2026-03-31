# 🔬 Delamination and Popcorn Effect Analysis in IC Packaging

This project presents a case study on reliability failures observed during **thermal exposure simulating reflow conditions** in semiconductor packaging.

The objective is to identify the failure mechanism, determine the root cause, and propose corrective actions to improve package reliability.

---

## 🎯 Problem Summary

- Failures observed during reliability testing after thermal exposure  
- Failure types: package cracking and delamination  
- Indicates a thermally triggered reliability issue  

---

## 📊 Approach

- Analyzed a **simulated production-like dataset** to study failure trends  
- Correlated failure rate with moisture exposure conditions  
- Identified strong dependency between **moisture level and failure rate**

---

## 📈 Failure Trend

![Failure Trend](assets/failure_trend.png)

*Figure: Failure rate increases significantly with higher moisture exposure, indicating strong correlation.*

---

## 🔍 Key Findings

- Failure occurs only after thermal exposure (reflow-like conditions)  
- Failure is mechanical in nature (delamination and cracking)  
- Moisture inside the package plays a critical role  

---

## 💧 Moisture Absorption

![Moisture Absorption](assets/moisture-capture.png)

*Figure->moisture-capture.png: Semiconductor packages can absorb moisture from the environment, which becomes critical during high-temperature processes.*

---

## 🔥 Physical Failure Mechanism

![Popcorn Effect](assets/popcorn-effect.png)

*Figure->popcorn-effect.png: Moisture inside the package vaporizes during thermal exposure, creating internal pressure that leads to delamination and package cracking (popcorn effect).*

---

## 🔬 Validation

![CSAM](assets/delamination-detection.png)

*Figure->delamination-detection.png: CSAM (C-Mode Scanning Acoustic Microscopy) is used to detect internal delamination and interface separation in IC packages.*

## 🛠️ Corrective Actions

- Implement proper **MSL (Moisture Sensitivity Level) control**  
- Introduce **pre-bake process before reflow**  
- Maintain controlled storage conditions  

---

## 📈 Result

- Failure reduced significantly after corrective actions  
- Improved package reliability under thermal conditions  

---

## 📄 Detailed Analysis

👉 Refer to the full document: **analysis.pdf**

---

## 📚 References

- Fundamentals of Microsystems Packaging — Rao R. Tummala  
  (For semiconductor packaging fundamentals, molding process, and reliability concepts)

- NPTEL Electronics Systems Packaging — Prof. K. N. Bhat  
  (For backend assembly flow and packaging processes)

- Microelectronics Packaging Handbook — Rao R. Tummala  
  (For wire bonding, molding behavior, and packaging technologies)

- General semiconductor packaging literature on moisture-induced delamination and popcorn effect  

---

## 📌 Note

This is a simulated case study created to replicate real-world semiconductor manufacturing scenarios and demonstrate structured problem-solving skills.