# PULPO 🐙 Workshop

Welcome to the **[PULPO](https://github.com/flechtenberg/pulpo)** workshop! This guide will help you set up the environment, understand the repository structure, and provide an overview of the workshop.

---
## 🛠️ Environment Setup

To get started with the workshop, follow these steps to set up your environment.

### 1. Download the Repository
- Clone or download the repository and store the files in a folder named `pulpo_workshop`.

### 2. Create a Conda Environment
- Ensure you are using **Python 3.10** for this workshop, as **Python 3.11 or later is (currently) not supported**.
  
  **Command to create a conda environment**:
  ```bash
  conda create --name pulpo_brightcon_env python=3.10
  conda activate pulpo_brightcon_env
  ```

### 3. Install PULPO
- Once the environment is set up, install the PULPO package by running the following command:
  
  ```bash
  pip install pulpo-dev
  ```

### 4. Install Additional Dependencies for Notebook 03
- Notebook `03_PULPO_exercise.ipynb` requires additional dependencies. Install them by running the following commands:
  
  ```bash
  pip install python-louvain
  pip install networkx
  conda install conda-forge::ipopt=3.11.1
  ```

### 5. Install Additional Dependencies for Notebook 0X
- Notebook `0X_optimization.ipynb` requires additional dependencies. Install them by running the following commands:
```bash
pip install ipywidgets ipywidgets
pip install pdf2image
pip install ipympl
```
---

## 🗂️ Workshop Repository Structure

Here’s an overview of the contents of the workshop repository to help you navigate and understand the notebooks.

#### 1. `figures/`
- **Purpose**: Contains all the figures and visual aids referenced throughout the notebooks to help illustrate concepts.

#### 2. `00_computational_structure_of_LCA.ipynb`
- **Purpose**: Introduces the **computational structure of Life Cycle Assessment (LCA)**, a core concept explored in PULPO.
- **Content**: This notebook covers the theory and practical coding implementation of LCA using **NumPy**.

#### 3. `0X_optimization.ipynb`
- **Purpose**: An auxiliary notebook providing context, theory, and applications of **numerical optimization**.
- **Content**: Explains optimization terminology, formulation, and includes a case study solving a **heat exchanger problem** for both economic and environmental objectives.

#### 4. `01_introduction_to_PULPO.ipynb`
- **Purpose**: Serves as the **introductory notebook** to the PULPO package.
- **Content**: Provides a comprehensive text-based overview of PULPO's key features and capabilities.

#### 5. `02_rice_example_resolution.ipynb`
- **Purpose**: Demonstrates how to use **PULPO** to solve the "``Rice Example``".
- **Content**: Guides you through the problem setup, solving the optimization problem using PULPO, and interpreting the results.

#### 6. `03_PULPO_exercise.ipynb`
- **Purpose**: A **hands-on exercise** for participants to practice using PULPO.
- **Content**: Allows you to apply your knowledge to solve a new problem using the PULPO package.

#### 7. `03_PULPO_exercise_solution.ipynb`
- **Purpose**: Provides the **solution** to the hands-on exercise.
- **Content**: Offers a step-by-step solution to the exercise, which you can use to check your work or if you need help.

---
## 🗓️ Workshop Overview

Here is a brief overview of the topics and time allocation for the workshop:

1. **10 minutes**: Introduction to the computational structure of LCA (Notebook 00).
2. **10-15 minutes**: Overview of the PULPO package and theory (Notebook 01).
3. **20-25 minutes**: Walkthrough of the Rice Example (Notebook 02).
4. **20-30 minutes**: Hands-on exercise using PULPO (Notebook 03).

**Total Duration**: 60-80 minutes

---

We hope you enjoy the workshop!
