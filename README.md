# Networked Painting App (Kivy Simulation)

![Python](https://img.shields.io/badge/Python-3.12-blue.svg)
![Kivy](https://img.shields.io/badge/Kivy-2.x-green.svg)
![Platform](https://img.shields.io/badge/Platform-Linux-orange.svg)

## 🎨 Overview

This project is a **digital painting application** built using **Python** and the **Kivy** framework. It features a real-time drawing interface designed to simulate a networked environment.

Initially conceptualized as an embedded project for a **Raspberry Pi** touch display, the project was adapted into a pure Linux-based simulation due to hardware unavailability in our department. Though thanks to python compatibility features, it works fine on other operating systems as well as MacOS and Windows.

It demonstrates how to handle touch events, graphical rendering, and networked communication (Socket/WebSocket) within a GUI application.

## ✨ Key Features

*   **Interactive Canvas:** Smooth freehand drawing capabilities using Kivy's widget system.
*   **Real-time Simulation:** Simulates the interaction intended for an embedded touch device on a standard Linux desktop.
*   **Networked Architecture:** Utilizes socket programming to handle data transmission (designed to separate the input logic from the display logic).
*   **Custom UI:** Minimalist interface focused on user interaction.

## 🛠️ Tech Stack

*   **Language:** Python 3
*   **GUI Framework:** Kivy (Open source Python library for rapid development of applications that make use of innovative user interfaces).
*   **Networking:** Python `socket` module / WebSockets (for client-server communication).
*   **OS:** Linux (Ubuntu/Debian recommended).

## 🚀 Installation & Usage

To run this simulation on your local machine, follow these steps:

1.  **Clone the repository:**
```bash
git clone https://github.com/SalehTvl/Painting-App.git
cd Painting-App
```

2. **Create a virtual environment (Recommended):**
``` bash
python3 -m venv venv
source venv/bin/activate
```

3. **Install dependencies:**
```bash
pip install kivy pygame pillow
```

4. **Run the application:(Run Server and Client apps)**
``` bash
python server.py
python client.py
```