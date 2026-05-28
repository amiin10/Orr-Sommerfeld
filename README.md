# Orr-Sommerfeld Stability Analysis

This project implements a numerical solution to the **Orr-Sommerfeld equation** for analyzing the linear stability of Poiseuille flow, a parallel shear flow with a parabolic velocity profile. The code computes the eigenvalue spectrum, perturbation profiles, and neutral stability curve using the **Finite Difference Method (FDM)**.

## Table of Contents

- [Overview](#overview)
- [Features](#features)
- [Requirements](#requirements)
- [Installation](#installation)
- [Usage](#usage)
- [Presentation](#presentation)
- [Contributing](#contributing)
- [License](#license)

---

## Overview

The Orr-Sommerfeld equation is a fundamental tool in hydrodynamic stability, used to determine whether small perturbations in a flow decay (stable) or grow (unstable), potentially leading to turbulence. This implementation focuses on:
- **Poiseuille flow**: A parabolic velocity profile \( U(y) = 1 - y^2 \) in a channel domain \( y \in [-1, 1] \).
- **Temporal stability analysis**: Solving the eigenvalue problem to find complex wave speeds \( c = c_r + i c_i \), where \( c_i > 0 \) indicates instability.
- **Numerical approach**: Discretizing the equation using FDM and solving the resulting generalized eigenvalue problem.
- **Outputs**: Eigenvalue spectra, perturbation profiles (\( v \)- and \( u \)-perturbations), and the neutral stability curve.
![Eigenvalue Spectrum](Figs/Picture2.png)
![Stability Analysis](Figs/Picture1.png)
---

## Features

- Numerical solvers for the Orr-Sommerfeld equation.
- Visualization of eigenvalues and eigenfunctions.
- Tools for analyzing flow stability.
- Interactive Jupyter Notebooks for experimentation and learning.

---

## Requirements

To use this repository, ensure you have the following installed:

- Python 3.x
- Jupyter Notebook

---

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/Aminhs0/Orr-Sommerfeld.git
   cd Orr-Sommerfeld
   ```

2. Create and activate a virtual environment (optional but recommended):
   ```bash
   python3 -m venv venv
   source venv/bin/activate  # On Windows: venv\Scripts\activate
   ```

---

## Usage

1. Launch Jupyter Notebook:
   ```bash
   jupyter notebook
   ```

2. Open the desired notebook file and run the cells to perform analyses.

3. Explore the provided notebooks to study the stability of specific flow profiles under various parameters.

---

## Presentation

This repository includes a presentation that provides a comprehensive overview of the Orr-Sommerfeld equation, its applications, and the results generated using the tools in this repository. 

### Access the Presentation:
You can find the presentation file [here](Orr-Sommerfeld.pdf).

---

## Contributing

Contributions are welcome! If you have any ideas, suggestions, or improvements, feel free to:

1. Fork the repository.
2. Create a new branch for your feature or bug fix:
   ```bash
   git checkout -b feature-name
   ```
3. Commit your changes and push to your fork:
   ```bash
   git commit -m "Add new feature"
   git push origin feature-name
   ```
4. Open a pull request to the main repository.

---

## License

This repository is licensed under the [MIT License](LICENSE).

Feel free to use, modify, and distribute this code responsibly.

---

## Acknowledgments

Special thanks to the fluid dynamics community and contributors who have provided valuable resources and insights into the Orr-Sommerfeld equation.

If you find this repository helpful, consider giving it a ⭐ on GitHub!

---
