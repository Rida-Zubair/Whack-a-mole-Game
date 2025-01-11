# Whack-a-Mole Game in Digital Logic Design  

### 📋 Overview  
The **Whack-a-Mole game** is a digital circuit simulation project designed for the Digital Logic Design Lab. Players interact with the game by pressing buttons corresponding to randomly lit LEDs to score points. The game operates on a timer, displaying the final score at the end.  

---

### 🚀 Features  
1. **Random LED generation** using the 555 Timer IC and 4017 Decade Counter.  
2. **Score tracking** via button presses using AND gates and the 4026 Decade Counter/7-Segment Driver.  
3. **Game timer** implemented with a second 555 Timer IC in monostable mode, ending with a buzzer sound after 30 seconds.  

---

### 🛠️ Components  
- 555 Timer IC (2 units)  
- 4017 Decade Counter  
- 4026 Decade Counter/7 Segment Driver  
- Logic Gates: AND, OR, NOT  
- Capacitors and Resistors  
- LEDs (Yellow)  
- 7-Segment Displays  
- Push Buttons  
- Buzzer  
- Voltage Source  

---

### 💻 How It Works  
1. **Random LED Lighting:**  
   The 555 Timer IC generates clock pulses fed into the 4017 Decade Counter, lighting up LEDs in a sequential, random manner.  

2. **Button Press and Scoring:**  
   Players press buttons corresponding to lit LEDs. The circuit validates correct presses using AND gates, updating the score on the 7-segment display via the 4026 Counter.  

3. **Game Timer:**  
   A second 555 Timer IC triggers a 30-second countdown, activating the buzzer at the end.  

---

### 🧩 Circuit Design  
The design was created and simulated in **Proteus**, followed by practical implementation on a breadboard. The schematic includes connections for the timer, counters, logic gates, and power supply.  

---

### 📷 Images  
![circuit](https://github.com/user-attachments/assets/5b70ed42-78c9-40a1-b018-34c27f271189)




---

### 🤝 Team 
- **Rida Zubair** (23I-2590)
- **Noor ul Huda** (23I-2099)  
- **Malaika Zaniab** (23I-2605)  
  

Guided by: **Miss Nabeela Maryam**  

---

### 🔗 Repository Contents  
- `WhackAMole_ProteusFiles/` - Proteus design files  
- `Breadboard_Images/` - Practical implementation images  
- `Documentation/` - Detailed report and circuit diagrams  

---

### 📖 Learnings  
This project strengthened our knowledge of:  
- Digital logic and timing circuits  
- Counter-based scoring mechanisms  
- Practical circuit troubleshooting  

---

### ⚡ How to Run  
1. Open the Proteus simulation file.  
2. Run the simulation to test the LED sequence, button presses, and timer.  
3. Refer to the documentation for detailed implementation steps.  

---

Feel free to contribute or explore this repository!  

---
