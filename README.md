# 🧬 Evolution Simulation (Unity + C#)

A Unity-based simulation that demonstrates evolutionary behavior in artificial organisms. Agents evolve over generations using a combination of simple **neural networks** and **genetic algorithms**, guided by survival performance.

---

## 🎮 Overview

The simulation shows:
- Evolving organisms using fitness-based selection.
- Decision-making using neural networks.
- Mutation and reproduction logic across generations.
- Real-time visualization using Unity's physics engine.

---

## ✨ Features

- 🤖 Sensor-driven agents that navigate the environment.
- 🧬 Genome-based mutation and crossover system.
- 🧠 Neural networks control agent decisions.
- 🔁 Automated generation transition.
- 📊 Visual feedback on agent behavior and learning.

---

## 🛠 Tech Stack

- **Engine:** Unity (2021+)
- **Language:** C#
- **Concepts:** Genetic Algorithm, Neural Networks, Artificial Life

---


---

## 🚀 Getting Started

### Prerequisites

- Unity Hub
- Unity Editor (2021.3 or later recommended)

### Running the Simulation

1. Clone or download this repository.
2. Open the project in **Unity Hub**.
3. Navigate to `Assets > Scenes > SampleScene.unity`.
4. Press ▶️ **Play** in the Unity Editor.

---

## 🧠 AI Concepts Used

- **Genetic Algorithms**  
  Used for selection, mutation, and generation of new agents.
- **Neural Networks**  
  Agents use a small neural network for behavior control.
- **Fitness-Based Evolution**  
  Agents with higher survival rates have better reproduction chances.

---

## 🔧 Customization

Modify the following files to tune behaviors:
- `Globals.cs`: Adjust global variables.
- `NeuralNet.cs`: Change neural network architecture.
- `NextGen.cs`: Tweak mutation rates and selection logic.
- `Input_sensors.cs` / `Output_sensors.cs`: Define sensing and actions.

---

## 📊 PROJECT OUTPUT

### 1. The Top Half

For the top half, as the survival criteria, the following data was obtained.

---

#### 🔹 Generation 0

Start of the simulation:

![Gen 0](https://github.com/user-attachments/assets/979fd483-b5dc-4d96-a85a-b6cd23036102)

---

#### 🔹 Generation 100

Distribution after 100 generations:

![Gen 100](https://github.com/user-attachments/assets/6c534ea9-6bae-43e9-9e7a-cb80a7632380)

---

#### 🔹 Generation 300

More homogenized distribution at generation 300:

![Gen 300](https://github.com/user-attachments/assets/a72ea656-b0f1-4114-8cec-069641f53aae)

---

### 🧬 Prominent Genomes (20 genes of length 6)

After 300 generations, the two most prominent genomes were:
18F9F1DC0D6A280E291F48D00AF89A2A842D1FBA94D8ED66E4E10F746A40C0E167D90F8E922B60DE04507C548921678317E2C81A6B49969091B36955
6FA7DACB34B31D5D70D0A6ED8F41AEF3F57DB828E3D78B0C8DABEA5BC8A915C0140714DA91D35208A358FFF0B7CE9424282F6460BCC98D153DA9CFCD


As can be seen, the organisms comprised mostly of two types of genomes. Since the genome length was long, fewer dominant patterns emerged.

---

### 🧬 Small Genome Case (6 genes)

#### 🔹 Generation 0

Initial population with only 6-gene genomes:

![Gen 0 (6 genes)](https://github.com/user-attachments/assets/2ab62e7f-0efa-4b7f-8303-c56a17264575)

---

#### 🔹 Generation 70

Genome homogeneity achieved at generation 70. Only a single type of organism prevailed due to simpler neural architecture:

![Gen 70 (6 genes)](https://github.com/user-attachments/assets/5f00ce41-f861-4afb-bad3-fbe9468e8aae)

The final dominant genome:
DB5BFEEBAE209C0D811FDE2225BC4BD5A92E





## 🙋 Author

**Kashish Gupta**  
📧 Email: [kashish.kg11@gmail.com](mailto:kashish.kg11@gmail.com)  
🔗 [LinkedIn](https://linkedin.com/in/kashish-kg11)  
💻 [GitHub](https://github.com/kashishgupta29)

---

