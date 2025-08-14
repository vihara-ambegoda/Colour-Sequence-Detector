#🔴🟠🟢🔵🟡 Colour-Sequence-Detector
Design of A Colour Sequence Detector for a 5-core Harness Cable

# Colour Sequence Detector

Low-cost tester for verifying the **colour sequence** and **continuity** of 5-core harness cables at both ends of a coil.  
Designed **without microcontrollers** to keep the design simple and cost-effective, powered by a 9 V battery.

---

## 📜 Overview
This device checks if both ends of a cable have the **same wire colour sequence** and ensures **continuity**.  
It was developed for the Harness Department as a more efficient alternative to the manual continuity tester.

---

## ⚙️ How It Works
1. A **555 Timer** generates clock pulses.  
2. Two **CD4017 Decade Counters** are clocked together:  
   - One drives the positive side of LEDs.  
   - The other (through a **NOT gate**) drives the negative side.  
3. When the wire order matches at both ends, the corresponding LED lights up.

---

## 💡 Features
- Tests **5 cores** (expandable to 10).  
- Detects **sequence** and **continuity**.  
- **No microcontroller** → reduced cost.  
- Tested via **Proteus 8 Professional** simulation and breadboard prototype.

---

## 🛠 Components
- 1 × 555 Timer IC  
- 2 × CD4017 Decade Counter IC  
- 1 × NOT Gate IC  
- LEDs (per core)  
- Resistors, jumper wires, breadboard  
- 9 V Battery

---

## 📷 Project Images
**Simulation (Proteus 8 Professional):**  
![Simulation Screenshot](images/simulation.png)  

**Breadboard Prototype:**  
![Breadboard Build](images/breadboard.png)  

*(Add actual file paths to your images in the `images` folder)*

---

## 📐 Circuit Diagram
![Circuit Diagram](images/circuit_diagram.png)  
*(Add your schematic here)*

---

## 🔮 Future Improvements
- Expand to test **up to 10 cores**.  
- Build into a **durable production-line-ready enclosure**.  

---

## 📄 License
This project is shared for **educational purposes**.  
Remove any sensitive details before sharing publicly.  
