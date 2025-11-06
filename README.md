# Shiny Visualization Project

This repository contains the Shiny-based interactive visualization system developed for the dissertation project in Probability and Statistics Education.  
This tool enables learners to explore probability distributions through interactive graphics, hands-on experimentation, and storytelling elements that bring abstract ideas to life.

## Project Overview

The Shiny application helps students learn key probability concepts through simulation and dynamic visualization.  
Users can interactively manipulate parameters, visualize how probability functions change, and explore statistical relationships in real time.

### Core Modules

| Module | Description |
|:--------|:-------------|
| **Main Application (`main.R`)** | Integrates all modules into a unified Shiny dashboard. |
| **Probability Distribution (`module_probability.R`)** | Visualizes major discrete and continuous distributions, including Bernoulli, Binomial, Poisson, and Normal. |
| **Game: Discrete (`module_game_discrete.r`)** | An interactive detective-style probability game that strengthens conceptual understanding through contextual tasks. |
| **Joint Distribution (`module_joint.R`)** | Enables users to construct and explore joint PMFs, marginal, and conditional distributions. |
| **Conditional Distribution (`module_conditional.R`)** | Demonstrates how conditional probabilities evolve based on different given conditions. |
| **Expectation (`module_expectation.R`)** | Allows learners to compute and visualize expectations of random variables using table-based PMFs. |

---

## Included Resources

The packaged file `Project_PPeek1ng.zip` includes:
- All R source files listed above  
- Image and visualization assets used across modules  
- A structured directory ready for deployment on RStudio or Shiny Server

---

## How to Run

1. Download or clone this repository:
   ```bash
   git clone https://github.com/D1OK1NG/Shiny-Visualization-Project.git
   ```
2. Unzip `Project_PPeek1ng.zip`  
3. Open the project folder in RStudio  
4. Run the app:
   ```R
   shiny::runApp("Project_PPeek1ng")
   ```
5. The dashboard will open in your default browser.

---

## Academic Context

This project was developed as part of a Master’s dissertation focused on enhancing probability and statistics learning through interactive visualization.  
It combines statistical theory, pedagogical design, and data-driven user interaction using R and Shiny.

The project was completed under the academic supervision of **Dr. Azam Asanjarani** and **Dr. Heti Afimeimounga**, whose guidance and insights were invaluable in shaping the educational design and overall structure of this work.

For detailed methodology, educational design, and system architecture, please refer to the dissertation document.

---

## Repository Structure

```
Shiny-Visualization-Project/
│
├── Project_PPeek1ng.zip          # Full Shiny project archive
├── README.md                     # Project documentation
└── (unzipped folder contents)
    ├── main.R
    ├── module_probability.R
    ├── module_game_discrete.r
    ├── module_joint.R
    ├── module_conditional.R
    ├── module_expectation.R
    └── images/
```

---

## License & Citation

This project is shared under the MIT License for academic and educational purposes.  
If you reference or reuse this work, please cite:

> Wu, Chunyi (2025). *Shiny-Based Probability Visualization Project.* University of Auckland.  
> GitHub: [https://github.com/D1OK1NG/Shiny-Visualization-Project](https://github.com/D1OK1NG/Shiny-Visualization-Project)

---

## Contact

**Author:** Chunyi Wu  
**Institution:** University of Auckland — Master of Professional Studies in Data Science  
**Supervisors:** Dr. Azam Asanjarani, Dr. Heti Afimeimounga  
**Email:** cwu112@aucklanduni.ac.nz  
**GitHub:** [https://github.com/D1OK1NG](https://github.com/D1OK1NG)
