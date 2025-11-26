# SystemDynamics-YouthHomelessness-HF4Y
Supplementary Materials for: Breaking the Cycle of Chronic Neglect
# Breaking the Cycle of Chronic Neglect: A Pattern-Oriented System Dynamics Analysis

## Overview
This repository contains the supplementary materials, simulation model equations, and parameter documentation for the research paper: **"Breaking the Cycle of Chronic Neglect: A Pattern-Oriented System Dynamics Analysis of the 'Survival Crime Trap' and Housing First for Youth (HF4Y)."**

This study utilizes a System Dynamics (SD) approach to investigate the structural mechanisms of youth homelessness, criminalization, and the efficacy of the Housing First for Youth (HF4Y) intervention.

## Repository Contents

* **`Model_Equations.txt`**: The core mathematical formulations of the model, including the logistic functions for survival crime probability and the allostatic load accumulation process.
* **`Parameters.csv`** (Optional): Key parameter values used for sensitivity analysis (e.g., Threshold ranges 0.5 - 0.7).
* **`Simulation_Results_Summary.pdf`**: (Optional) Additional graphs showing the decay of recurrence and the age-crime curve patterns.

## Model Structure
The model is built upon three primary feedback loops:
1.  **R1 Loop (Survival Crime Trap)**: Reinforcing loop linking resource deprivation to neurobiological stress (Allostatic Load) and crime.
2.  **R2 Loop (Stigma-Isolation Nexus)**: Reinforcing loop describing the erosion of social capital due to toxic shame.
3.  **B1 Loop (Iatrogenic Policy Resistance)**: Balancing loop (dysfunctional) showing how strict shelter rules lead to involuntary discharge.

## Software Requirements
* The model logic is compatible with **Vensim DSS / PLE** or **Stella Architect**.
* The provided equation text can be implemented in any equation-based modeling environment (e.g., Python, AnyLogic).

## Citation
If you use this model or code for your research, please cite the original paper:
> [Your Name]. (2025). *Breaking the Cycle of Chronic Neglect: A Pattern-Oriented System Dynamics Analysis*. [Journal Name, if accepted].

## License
This project is licensed under the MIT License - see the LICENSE file for details.

