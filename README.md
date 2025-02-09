# Spike-Prime-Rubiks-Cube-Solver
This document outlines our approach to developing a Rubik's Cube solver using Spike Prime. While the project is not yet where we would like it to be, we want to share our process, thoughts, and results.

![Assembling Animation](https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/Bot_2.gif)
## 📌 Table of Contents  
- [📖 What is it?](#what-is-it)  
- [🚀 Getting Started](#getting-started)  
- [📚 Resources](#resources)  
- [💡 Ideas and Development](#ideas-and-development)  
  - [🎨 Design](#design)  
  - [⚙️ Functions](#functions)  
- [🔨 Build Instructions](#build-instructions)  
- [💻 Software](#software)  
- [📸 Demo / Screenshots](#demo--screenshots)   
- [🤝 Contributing](#contributing)  
- [🎖 Acknowledgments](#acknowledgments)  


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
## 💡 Ideas and Development  

### 🔹 Why did we start this project?  
As part of a **university seminar**, we were given the challenge of using the **LEGO Spike Prime** set to build a **robot capable of solving a task**. After brainstorming different possibilities, we decided to take on the challenge of designing a robot that could solve a **Rubik’s Cube**.  

---

### 🔹 What were the main goals at the beginning?  
The primary goal of this project was to develop a **fully functional Rubik’s Cube-solving robot** **without any prior programming experience**. We aimed to understand and apply fundamental robotics concepts while learning **mechanical design and programming** along the way.  

---

### 🔹 What were our first ideas about how to solve the problem?  
Initially, we focused on designing a **compact robot** that could perform the essential functions required to manipulate and solve a Rubik’s Cube. Our priority was **mechanical design**, ensuring that the robot had the necessary movements to interact with the cube effectively. At this stage, we did not yet consider the **software aspect** in depth, as our primary concern was creating a structure capable of handling the cube efficiently.  

---

### 🔹 How did we design the robot? (Mechanical structure, motor placement, etc.)  
Our approach was based on **analyzing how humans solve a Rubik’s Cube**. We studied **videos** of people solving the cube and carefully observed the movements required to rotate and manipulate the sides. We then broke these motions down into their most fundamental components and designed our robot to **replicate them in the simplest possible way**.  

One of the biggest challenges was ensuring that the **mechanical design** remained **compact and functional** while still allowing for the necessary **cube manipulations**. The placement of the **motors** and **grippers** was carefully adjusted to ensure that the robot could hold and rotate the cube without requiring excessive space.  

---

### 🔹 What were the important design decisions?  
Once the core functions were physically built, we conducted **multiple test runs** to assess the performance of the motors. During these tests, we observed that as the motors aged, their **accuracy began to decline**. To compensate for this issue, we introduced **physical movement limits (stoppers)** to restrict the range of motion and ensure **greater precision**. These stoppers played a crucial role in **maintaining consistency** during cube rotations and significantly improved the overall reliability of our design.  

Another important decision was to **keep the robot’s design as modular as possible**, allowing us to make **adjustments and improvements** as needed without having to rebuild the entire structure.  

---

### 🔹 Did we create prototypes before settling on the final version?  
Since we had a **limited time frame** for the project, we did not create multiple prototypes. Instead, our current version **is the prototype**, as we continuously improved and refined the design throughout the development process. Our focus was on **iterative improvements**, adjusting the design and functionality based on test results rather than building entirely new versions.  

---

### 🔹 What coding approaches or algorithms did we try?  
We made **several attempts** to develop a functional code for our robot. These different coding trials can be found in the **(insert branch name here)** branch of our repository. However, since we entered this project **without any programming experience**, we faced significant challenges in developing a working solution.  

To aid our learning process, we studied existing Rubik’s Cube-solving robots, such as **[MindCuber](https://mindcuber.com)**, and examined the **algorithms listed in the [Resources](#resources) section**. Unfortunately, we were unable to fully implement a solution within our time constraints.  

We experimented with multiple solving **algorithms** but struggled with **adapting them to the Spike Prime system**. While our mechanical structure was fully capable of solving the cube, the **software aspect** remained the biggest challenge.  

---

## 🔄 Challenges & Iterations  

### 🔹 What problems did we face during development?  
Throughout development, we encountered **several key challenges**:  
1. **Motor Accuracy Issues** – Over time, we noticed a **decline in precision**, which affected the cube’s rotation accuracy.  
2. **Lack of Programming Experience** – Since none of us had previous coding experience, learning to write functional and efficient code was a major hurdle.  
3. **Color Recognition Limitations** – The **color sensors of the Spike Prime set** sometimes struggled to accurately differentiate between cube colors, leading to misreadings.  

These challenges required constant problem-solving and adaptation to keep the project moving forward.  

---

### 🔹 How did our initial ideas change over time?  
While our **core concept remained the same**, we had to **adjust our goals** as we progressed. Initially, we had hoped to create a **fully autonomous** cube-solving robot. However, due to **time constraints and programming difficulties**, we had to **scale down our expectations** and focus on **mechanical reliability first**.   

Instead of achieving a **fully functional solver**, we shifted towards **building a stable mechanical foundation** that could serve as a base for future improvements.  

---

### 🔹 Did we remove or simplify any features due to limitations?  
Given our constraints, we had to **simplify the code** and focus on **mechanical precision**. While our robot has all the necessary **physical functions to solve the cube**, the software is still incomplete. The missing piece is a **fully implemented solving algorithm**, which we hope to develop in the future.  

---

## 🚀 Current State & Future Plans  

### 🔹 What works well in the current version?  
Despite the challenges, several aspects of our robot function **very reliably**:  
✅ The **cube-flipping mechanism** operates smoothly.  
✅ The **gripping system** securely holds the cube in place.  
✅ The **rotation adjustments** allow precise positioning of the cube.  
✅ The **tower approach mechanism** ensures proper alignment of the cube for movements.  

These mechanical elements form a **solid foundation for a fully functional solver** in the future.  

---

### 🔹 What still needs improvement?  
While the mechanical design is **highly functional**, certain areas still need **refinement**:  
❌ The **software (code)** needs significant improvement.  
❌ The **rotation of the cube on the extra platform** is not yet fully optimized.  

These aspects are the focus of our **next development phase**.  

---

### 🔹 What features do you plan to add in the future?  
We have exciting plans for the next iteration of our robot, including:  
🔄 **A Scramble Mode** – This mode would allow the robot to **randomly shuffle the cube**, making it more versatile.  
🧠 **A Solving Algorithm** – Implementing a **fully working algorithm** to complete the cube automatically.  

These additions will bring us **closer to a fully autonomous Rubik’s Cube solver**.  

---
## 🔨 Build Instructions  

To assemble the **Spike-Prime-Rubiks-Cube-Solver**, follow the detailed **LEGO-style building instructions** provided in the PDF below.  

📄 **Download the full step-by-step build guide:**  
👉 [Building Instructions (PDF)](https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Building%20Instructions.pdf) 

---
## 💻 Software  

This section provides an overview of the available **code versions** for the Spike-Prime-Rubiks-Cube-Solver. Different versions were created to explore various programming approaches and solving methods.  

---

### 📝 **Available Code Versions**  

Below are the different versions of the software, each with a brief description and a direct link to the corresponding file:  

#### **1️⃣ Basic Functions (Code Blocks)**  
📄 **File:** [Basic Movement Functions (Code Blocks)](https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Code/Basic%20Movement%20%20functions%20code%20blocks.llsp3)  
💡 **Description:** This version contains the **fundamental movement functions**, programmed using **LEGO Spike Prime code blocks**.  

---


#### **2️⃣ Basic Functions (Python)**  
📄 **File:** [Basic Movements (Python)](https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Code/Basic%20Movements%20python%20code.llsp3)  
💡 **Description:** This version also includes the **basic movement functions**, but it is programmed using **Python** instead of code blocks. Additionally, it implements **Rubik’s Cube notation movements (e.g., R, L, U, D, F, B)**.  

---

#### **3️⃣ Attempt at the Beginner’s Method**  
📄 **File:** [Beginner’s Method Attempt](https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Code/try%20of%20the%20beginners%20method.llsp3)  
💡 **Description:** This version is an **initial attempt** at implementing the **Beginner’s Method** for solving a Rubik’s Cube.  

---

#### **4️⃣ White Cross Extension**  
📄 **File:** [Extending the White Cross](https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Code/extended%20white%20cross.llsp3)  
💡 **Description:** This version extends the basic **white cross formation**, a crucial step in solving the Rubik’s Cube.  



## 📸 Demo / Screenshots

During the development of the **Spike-Prime-Rubiks-Cube-Solver**, we explored various designs for the **grabbing mechanism** to securely hold and manipulate the Rubik’s Cube. Below are some images of our initial attempts:  

<p align="center">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0000.jpg" width="300">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0001.jpg" width="300">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0002.jpg" width="300">
</p>

<p align="center">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0003.jpg" width="300">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0004.jpg" width="300">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0005.jpg" width="300">
</p>

<p align="center">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0006.jpg" width="300">
  <img src="https://github.com/kueche-dot/Spike-Prime-Rubiks-Cube-Solver/blob/main/Pictures/IMG-20250209-WA0007.jpg" width="300">
</p>


### 🔹 **Observations from the Design Process**  
- The **gripping mechanism needed precise control** to avoid damaging the cube.  
- We tested **different approaches** to find the right balance between **stability and flexibility**.  
- **Adjustments in motor positioning** were required to ensure accurate grabbing and releasing of the cube.  

## 📹 Robot in Action  

<p align="center">
  <a href="https://youtu.be/Y_E2VXqjoBQ">
    <img src="https://img.youtube.com/vi/Y_E2VXqjoBQ/maxresdefault.jpg" width="70%" alt="Spike-Prime Rubik's Cube Solver in Action">
  </a>
</p>

🎥 **Click the image above to watch the video!**  





---
## 🤝 Contributing  

We **welcome contributions** to improve the **Spike-Prime-Rubiks-Cube-Solver**! Whether it’s fixing a bug, adding a feature, or improving documentation or finishing the code😁  **your help is greatly appreciated!** 🚀  

---

### 🔹 **How to Contribute**  

1️⃣ **Fork the Repository**  
Click the **Fork** button at the top of this repository to create your own copy.  

2️⃣ **Clone Your Forked Repository**  
```sh
git clone https://github.com/your-username/Spike-Prime-Rubiks-Cube-Solver.git
cd Spike-Prime-Rubiks-Cube-Solver
```
3️⃣ **Create a New Branch**
```sh
git checkout -b feature-branch-name
```

4️⃣ **Make Your Changes**
🔹Edit the files and implement your improvements.
🔹Test your changes to make sure everything works.

5️⃣ **Commit Your Changes**
```sh
git add .
git commit -m "Brief description of changes"
```
6️⃣ **Push to GitHub**
```sh
git push origin feature-branch-name
```

7️⃣ **Submit a Pull Request (PR)**
<br>🔹Go to the original repository on GitHub.<br>
🔹Click “Compare & pull request”.<br>
🔹Add a clear title and description of your changes.<br>
🔹Click “Create pull request” and wait for review. 🎉<br>

## 🎖 Acknowledgments  

We would like to express our gratitude to the following individuals and resources that helped make this project possible:  

### 🔹 Team Members  
- **[Peter]**  
- **[Raphael]** 
- **[Marius]** 
### 🔹 Mentors & Advisors  
- **[Dr.-Ing. Giuseppe Sanseverino]** – For guidance and support during the university seminar.  

### 🔹 External Projects & Inspiration  
- **[MindCuber](https://mindcuber.com/)** – For providing insight into existing Rubik’s Cube solvers.  
- **[Kociemba’s Algorithm](https://kociemba.org/cube.htm)** – A key reference for solving strategies.  
- **Various YouTube tutorials** on Rubik’s Cube solving techniques.  

