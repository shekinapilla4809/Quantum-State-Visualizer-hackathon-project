# ⚛️ Quantum Circuit → Bloch Visualizer

### 🏆 AQVH912 – Quantum Computing Hackathon Project

A web-based **Quantum State Visualizer** designed to make quantum computing concepts easier to understand through interactive **Bloch Sphere visualizations**.

The application allows users to create and analyze quantum circuits, apply quantum gates, simulate quantum states, and visualize individual qubit states.

---

## 🚀 Project Overview

Quantum computing concepts can be difficult to understand because quantum states are represented using mathematical notation and are not directly visible.

**Quantum Circuit → Bloch Visualizer** provides an interactive visual approach to understanding how quantum gates affect quantum states.

### 🔄 Project Workflow

```text
Quantum Circuit
       ↓
Quantum Gates
       ↓
Qiskit Simulation
       ↓
Quantum State
       ↓
Qubit State Analysis
       ↓
Bloch Sphere Visualization
```

The goal of this project is to bridge the gap between **quantum computing theory and visual understanding**.

---

## ✨ Features

* ⚛️ Quantum circuit simulation
* 🌐 Interactive Bloch Sphere visualization
* 🧮 Quantum state calculation
* 🔢 Multi-qubit quantum state analysis
* 🔄 Individual qubit state visualization
* 📂 OpenQASM file upload support
* 🧩 Multiple quantum gates
* 📜 Quantum state/history tracking
* 🎨 Modern dark-themed interface
* 📊 Visual representation of quantum states
* 🔐 Authentication support

---

## 🧩 Supported Quantum Gates

| Gate     | Description              |
| -------- | ------------------------ |
| **H**    | Hadamard Gate            |
| **X**    | Pauli-X Gate             |
| **Y**    | Pauli-Y Gate             |
| **Z**    | Pauli-Z Gate             |
| **S**    | S Phase Gate             |
| **T**    | T Phase Gate             |
| **RX**   | Rotation around X-axis   |
| **RY**   | Rotation around Y-axis   |
| **RZ**   | Rotation around Z-axis   |
| **SWAP** | Swaps two qubit states   |
| **CX**   | Controlled-X / CNOT Gate |
| **CY**   | Controlled-Y Gate        |
| **CZ**   | Controlled-Z Gate        |

---

## 🧠 How It Works

### 1️⃣ Create a Quantum Circuit

Users create a quantum circuit using the supported quantum gates.

### 2️⃣ Apply Quantum Gates

Different gates such as H, X, Y, Z, RX, RY, RZ, SWAP, CX, CY, and CZ can be applied to the circuit.

### 3️⃣ Simulate the Circuit

The circuit is simulated using **Qiskit** to calculate the resulting quantum state.

### 4️⃣ Analyze the Quantum State

For multi-qubit circuits, the application analyzes the state of individual qubits.

### 5️⃣ Visualize Using Bloch Spheres

The resulting single-qubit states are represented using Bloch Spheres.

This provides an intuitive way to observe how quantum gates transform quantum states.

---

## 🛠️ Technologies Used

### Programming Language

* 🐍 Python

### Framework

* Streamlit

### Quantum Computing

* Qiskit
* Qiskit Aer

### Data Processing

* NumPy
* Pandas

### Visualization

* Matplotlib
* Plotly
* Streamlit

### Authentication

* Google Authentication

---

## 📁 Project Structure

```text
Quantum-State-Visualizer-hackathon-project/
│
├── main.py
├── ibm_app.py
├── login_page.py
├── google_auth.py
│
├── requirements.txt
├── runtime.txt
├── Procfile
│
├── logo.png
├── logo.ico
│
└── README.md
```

---

## 💻 Installation & Setup

### 1️⃣ Clone the Repository

```bash
git clone https://github.com/shekinapilla4809/Quantum-State-Visualizer-hackathon-project.git
```

### 2️⃣ Open the Project Folder

```bash
cd Quantum-State-Visualizer-hackathon-project
```

### 3️⃣ Create a Virtual Environment

```bash
python -m venv venv
```

### 4️⃣ Activate the Virtual Environment

#### Windows

```bash
venv\Scripts\activate
```

#### Linux / macOS

```bash
source venv/bin/activate
```

### 5️⃣ Install Dependencies

```bash
pip install -r requirements.txt
```

### 6️⃣ Run the Application

```bash
streamlit run main.py
```

The application will open in your web browser.

---

## 📂 OpenQASM Support

The application supports uploading quantum circuits using **OpenQASM** files.

### Workflow

```text
OpenQASM File
      ↓
Quantum Circuit
      ↓
Qiskit
      ↓
Quantum State
      ↓
Bloch Sphere
```

This allows users to visualize quantum circuits created outside the application as well.

---

## 📊 Example

A single qubit initially starts in the state:

```text
|0⟩
```

When a Hadamard gate is applied:

```text
H|0⟩
```

the qubit enters a superposition state:

```text
(|0⟩ + |1⟩) / √2
```

The application represents this quantum state visually using a Bloch Sphere.

---

## 🎯 Problem Statement

Quantum computing is an emerging field, but many students and beginners find it difficult to understand quantum states and quantum gates because they are primarily represented through mathematical concepts.

There is a need for an interactive and visual learning tool that can demonstrate how quantum gates transform quantum states.

---

## 💡 Proposed Solution

The **Quantum Circuit → Bloch Visualizer** provides an interactive environment where users can build quantum circuits and observe the resulting quantum states through Bloch Sphere visualization.

The project helps users:

* Understand quantum gates
* Visualize quantum states
* Explore superposition
* Observe state transformations
* Experiment with multi-qubit circuits
* Learn quantum computing interactively

---

## 🏆 Hackathon Information

| Details          | Information                        |
| ---------------- | ---------------------------------- |
| **Project ID**   | AQVH912                            |
| **Project Name** | Quantum Circuit → Bloch Visualizer |
| **Domain**       | Quantum Computing                  |
| **Event**        | Quantum Valley Hackathon           |
| **Organization** | APSCHE                             |

This project was developed as a hackathon solution focused on making quantum computing concepts more accessible through interactive visualization.

---

## 🔮 Future Enhancements

Future versions may include:

* 🎥 Quantum circuit animations
* 🧠 AI-powered quantum circuit explanations
* 📈 Advanced quantum state analytics
* 🔗 IBM Quantum backend integration
* 📱 Improved mobile responsiveness
* 🌐 Real-time collaborative quantum circuits
* 📚 Interactive quantum computing tutorials
* 🧪 Support for additional quantum gates and algorithms
* 📊 Measurement probability visualization
* 🔬 Density matrix visualization
* 📉 Quantum circuit performance analysis

---

## 👩‍💻 Developer

### Shekina Pilla

**B.Tech – Computer Science & Engineering (Data Science)**

### Areas of Interest

* ⚛️ Quantum Computing
* 🤖 Artificial Intelligence
* 📊 Data Science
* 💻 Software Development
* 🎨 3D Animation & Visualization

---

## 🙏 Acknowledgements

This project uses and is inspired by technologies and resources from:

* [Qiskit](https://qiskit.org/)
* [IBM Quantum](https://quantum.ibm.com/)
* [Streamlit](https://streamlit.io/)
* Python
* APSCHE
* Quantum Valley Hackathon

---

## 📜 License

This project is developed for **educational, research, and hackathon purposes**.

---

## ⭐ Support

If you find this project useful or interesting, please consider giving the repository a ⭐ **Star**.

Thank you for checking out the **Quantum Circuit → Bloch Visualizer**! ⚛️
