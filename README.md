# ⚙️ Computer Architecture Project – 8-bit Counter using Verilog

📌 **Project Title:** Design and Simulation of an 8-bit Counter  
📚 **Course:** Computer Architecture  
🎓 **Semester:** 5th Semester  
👩‍💻 **Developed by:** Mahnoor  

---

## 🧠 Project Objective

The objective of this project is to design an **8-bit synchronous up counter** that operates using a clock signal and uses a reset signal to bring the counter back to zero.  
The counter was simulated using **ModelSim software**, and its working was verified through **waveform analysis**.

---

## 🛠️ Tools & Technologies Used

- **Language:** Verilog HDL  
- **Simulation Tool:** ModelSim  
- **Concepts:** Counters, Clock, Reset, Waveform Analysis  

---

## 📂 Project Modules

| Module | Description |
|--------|-------------|
| **Counter Module** | Performs the actual counting operation using `clk`, `reset`, and `count` signals |
| **Testbench Module** | Generates clock, controls reset, and runs simulation for verification |

---

## 🎨 Waveform Analysis

- `clk` toggles continuously between HIGH and LOW  
- Initially, `reset = HIGH` keeps the counter at zero  
- When `reset = LOW`, the counter starts incrementing  
- Counter value increases on every positive edge of the clock  
- Successfully counts from **0 to 255**  

---

## 🎯 Results

- Counter resets to zero when reset is HIGH  
- Counter increments correctly on every positive edge of the clock  
- 8-bit counter verified through waveform simulation  

---

## ✅ Conclusion

This project successfully demonstrates the design and simulation of an **8-bit synchronous counter** using Verilog HDL.  
The correct operation was verified through **ModelSim waveform analysis**, helping in the practical understanding of **counters and clocking concepts** in Computer Architecture.

---

## 🔗 Related Links

- 🌐 [GitHub Portfolio Repository](https://github.com/mahnoor-cs6767)  
- 💼 [Mahnoor’s GitHub Profile](https://github.com/mahnoor-cs6767?tab=repositories)
