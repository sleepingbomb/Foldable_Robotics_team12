# 🦗 Grasshopper-Inspired Jumping Mechanism

[![GitHub Pages](https://img.shields.io/badge/Demo-GitHub%20Pages-blue)](https://sleepingbomb.github.io/Foldable_Robotics_team12/)
![Jupyter Notebook](https://img.shields.io/badge/Jupyter-81.7%25-orange)
![HTML](https://img.shields.io/badge/HTML-18.3%25-red)

A biomimetic robot utilizing foldable robotics principles and MuJoCo physics simulation to replicate the explosive locomotion of grasshoppers. This project was developed as part of the **RAS 557 - Foldable Robotics** course at **Arizona State University**.

## 📋 Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Getting Started](#getting-started)
- [Project Milestones](#project-milestones)
- [Team](#team)
- [License](#license)

## Overview

This project explores bio-inspired robotics design through the development of a grasshopper-inspired jumping mechanism. By studying the biomechanics of grasshopper legs and implementing a four-bar linkage system, we created a foldable robot capable of store-and-release energy cycles for explosive jumping motion.

**🌐 Live Demo:** [https://sleepingbomb.github.io/Foldable_Robotics_team12/](https://sleepingbomb.github.io/Foldable_Robotics_team12/)

## Features

- **Biomimetic Design** — Four-bar linkage mechanism replicating grasshopper leg kinematics
- **Physics Simulation** — MuJoCo-based dynamic simulation with accurate contact modeling
- **Design Optimization** — Parameter tuning for optimal jumping performance
- **Foldable Construction** — Laser-cut laminate fabrication from cardstock materials
- **Servo Actuation** — ESP32 microcontroller with SG90 servo motors
- **Experimental Validation** — Real-world testing and performance analysis

## Project Structure

```
Foldable_Robotics_team12/
├── assets/
│   └── css/                    # Stylesheets for documentation website
├── project1/                   # Project Proposal
│   └── index.html              # Initial research and project scope
├── project2/                   # Final Robot Implementation
│   ├── Working_Model.html      # MuJoCo simulation and dynamic analysis
│   ├── optimization.html       # Design optimization and parameter tuning
│   ├── parameter-identification.html  # System parameter characterization
│   ├── manufacturing.html      # Laser-cut fabrication workflow
│   ├── experimental-validation.html   # Testing and performance analysis
│   └── report-and-video.html   # Final documentation and demo
├── index.html                  # Main project website
├── _config.yml                 # GitHub Pages configuration
└── README.md                   # This file
```

## Technologies Used

| Category | Technology |
|----------|------------|
| **Simulation** | MuJoCo Physics Engine |
| **Programming** | Python, Jupyter Notebook |
| **Visualization** | Plotly, k3d, PyThreeJS |
| **Fabrication** | Laser-cut cardstock laminates |
| **Hardware** | ESP32 Microcontroller, SG90 Servo Motors |
| **Mechanism** | Four-bar linkage system |

## Getting Started

### Prerequisites

- Python 3.8+
- Jupyter Notebook
- MuJoCo (for simulation)

### Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/sleepingbomb/Foldable_Robotics_team12.git
   cd Foldable_Robotics_team12
   ```

2. Install required Python packages:
   ```bash
   pip install mujoco numpy matplotlib plotly jupyter
   ```

3. Open Jupyter notebooks in the `project2/` directory to explore simulations and analysis.

### Viewing the Documentation

Visit the [GitHub Pages site](https://sleepingbomb.github.io/Foldable_Robotics_team12/) for complete project documentation, or run locally:

```bash
python -m http.server 8000
```

Then navigate to `http://localhost:8000` in your browser.

## Project Milestones

### Project 1: Research & Proposal
- Exploration of grasshopper biomechanics
- Selection of foldable robotics approach
- Definition of project scope and objectives
- Initial kinematic analysis

### Project 2: Final Implementation
- **Working Model** — MuJoCo physics simulation and dynamic analysis
- **Design Optimization** — Parameter tuning for performance
- **Parameter Identification** — Characterizing system parameters from experiments
- **Manufacturing** — Laser-cut laminate fabrication workflow
- **Experimental Validation** — Real-world testing and analysis
- **Final Report & Demo** — Complete documentation with video demonstration

## Team

| Member | Role |
|--------|------|
| **Abhijit Sinha** | Robotics Engineer |
| **Shivakumar Sridhar** | Robotics Engineer |
| **Anusha Chatterjee** | Robotics Engineer |

## License

This project was developed for educational purposes as part of RAS 557 at Arizona State University.

---

<p align="center">
  <strong>© 2025 Team 12 — Arizona State University — RAS 557</strong>
</p>
