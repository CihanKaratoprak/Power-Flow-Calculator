Power Flow Analysis GUI

A Python-based GUI application for performing Power Flow (Load Flow) calculations in electrical power systems.
It provides iterative solving, logging of convergence steps, and real-time visualization of the single-line diagram.

🔑 Key Features
Power Flow Solver

Supports iterative methods for bus voltage and power flow calculation

Automatic bus type detection (Slack, PV, PQ)

Reactive power limit checks

Iteration Log

Tracks each iteration step with detailed values (voltages, angles, mismatches)

Displays convergence progress in a structured log

Network Visualization

Interactive single-line diagram drawing

Buses, generators, loads, and transmission lines are represented graphically

GUI Interface

Easy data entry for buses, loads, and lines

One-click calculation and results visualization

🛠 Tech Stack

Language: Python 3.x

GUI: Tkinter / PyQt5

Visualization: Matplotlib, NetworkX

Logging: Standard Python logging system

📦 Installation

Clone this repository:

git clone https://github.com/CihanKaratoprak/power-flow-gui.git
cd power-flow-gui


Install dependencies:

pip install -r requirements.txt


Run the application:

python main.py

📂 Project Structure
.
├── main.py          # Entry point
├── gui/             # GUI components
├── core/            # Power flow algorithms
├── utils/           # Helper functions (logging, plotting, etc.)
├── logs/            # Iteration logs
└── README.md

🖼 Demo

Define buses, lines, and load data

Run the solver

Check the iteration log

View the single-line diagram with power flow results

🤝 Contributing

Contributions are welcome! If you’d like to improve the solver, add new algorithms, or enhance the GUI:

Fork the repo

Create a new branch (feature/my-feature)

Commit your changes

Open a Pull Request

📌 Note

This project was developed individually as part of my work on power system analysis.
It is not licensed under MIT or any open-source license. All rights are reserved.

📬 Contact

If you have any questions, suggestions, or collaboration ideas, feel free to reach out:

📧 Email: cihankaratoprak0@gmail.com

💼 LinkedIn: https://www.linkedin.com/in/cihan-karatoprak-65b04136a/

🌍 GitHub: CihanKaratoprak
