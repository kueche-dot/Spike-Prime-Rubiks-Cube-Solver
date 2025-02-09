# Spike-Prime-Rubiks-Cube-Solver
This document outlines our approach to developing a Rubik's Cube solver using Spike Prime. While the project is not yet where we would like it to be, we want to share our process, thoughts, and results.

## 📌 Table of Contents  
- [📖 What is it?](#what-is-it)  
- [🚀 Getting Started](#getting-started)  
- [📚 Resources](#resources)  
- [💡 Ideas and Development](#ideas-and-development)  
  - [🎨 Design](#design)  
  - [⚙️ Functions](#functions)  
- [🚧 Challenges](#challenges)  
- [🔨 Build Instructions](#build-instructions)  
- [💻 Software](#software)  
- [📸 Demo / Screenshots](#demo--screenshots)  
- [📂 Additional Resources](#additional-resources)  
- [📝 Lessons Learned & Limitations](#lessons-learned--limitations)  
- [🔮 Future Work](#future-work)  
- [🤝 Contributing](#contributing)  
- [🎖 Acknowledgments](#acknowledgments)  
- [📜 License](#license)  


## 📖 What is it?

The **Spike-Prime-Rubiks-Cube-Solver** is a project aimed at developing a Rubik’s Cube solving robot using LEGO Spike Prime. The goal is to automate the solving process by leveraging Spike Prime’s motors, sensors, and programming capabilities.

🔹 **Current Status:** The project is **not yet finished**. While we have made significant progress, there are still challenges to overcome before achieving a fully functional solution.  

🔹 **Why share it?**  
Even though it’s incomplete, we want to document our journey, share our thoughts, and provide insights into our approach. By doing so, we hope to inspire others, receive feedback, and contribute to the community of robotics and puzzle-solving enthusiasts.

## 🚀 Getting Started  

This section will help you **set up and run** the Spike-Prime-Rubiks-Cube-Solver.  

---

### **1️⃣ Prerequisites**  
Before you start, ensure you have the following:  

🔹 **Hardware Requirements:**  
- ✅ **LEGO Spike Prime Kit** (with motors & sensors)  
- ✅ **Rubik's Cube** (5.5 cm on each side)  
- ✅ **A computer with LEGO Spike App installed**  
- ✅ **USB cable or Bluetooth connection**  

🔹 **Cube Specifications:**  
- The robot is designed for a **5.5 cm (55 mm) Rubik’s Cube**  
- The cube uses **colors that the LEGO Spike Prime color sensor can recognize** (typically **white, yellow, red, blue, green, and orange**)  

🔹 **Software Requirements:**  
- ✅ [LEGO Spike Prime Software](https://education.lego.com/en-us/downloads)  

---

### **2️⃣ Installation Instructions**  

#### **Clone the Repository**  
Download the project files using Git:  
```sh
git clone https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver.git
cd Spike-Prime-Rubiks-Cube-Solver
```
---
### **3️⃣ Basic Usage**
Once installed, follow these steps to test the setup:

  1. Place the 5.5 cm Rubik`s Cube  with the daisy pattern on top into the robot
  2. Run the code on the Lego Spike Prime Hub
  3. Check if the color sensor correctly recognizes the cube's colors
  4. Ensure the robot begins scanning and moving as expected
---
## 📚 Resources  

This section provides useful references and materials related to the **Spike-Prime-Rubiks-Cube-Solver** project.

### 🔹 **1. Official Documentation & Tools**  
- 📌 [LEGO Spike Prime Official Documentation](https://education.lego.com/en-us/downloads)  
- 📌 [LEGO Spike Prime API Reference](https://lego.github.io/lego-spike-python/)  
- 📌 [Python for LEGO Spike Prime (Spike API)](https://github.com/lego/lego-spike-python)  

### 🔹 **2. Rubik's Cube Solving Algorithms**  
- 🧩 [Beginner’s Method for Solving a Rubik’s Cube](https://ruwix.com/the-rubiks-cube/how-to-solve-the-rubiks-cube-beginners-method/)  (we started with this)
- 🔢 [CFOP Method (Advanced Solving)](https://www.cubeskills.com/tutorials/advanced-f2l)  
- 🤖 [Kociemba’s Two-Phase Algorithm](https://kociemba.org/cube.htm) (Used in many automated solvers)  


### **Why These Resources?**  
- ✅ **LEGO Spike Prime Documentation** helps in understanding the hardware and API.  
- ✅ **Solving Algorithms** provide the logic needed for programming the solver.  

---



