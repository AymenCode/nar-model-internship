# NAR Model Estimators for Demand Forecasting

This repository contains the implementation of the Network Autoregressive (NAR) model, focusing on various estimators to forecast product demand using synthetic data. This project is based on the framework introduced by Hand Yin et al. (2023).

## Table of Contents

- [Overview](#overview)
- [Installation](#installation)
- [Project Structure](#project-structure)
- [Acknowledgements](#acknowledgements)

## Overview

This project applies the NAR framework to forecast product demand, focusing on the performance comparison of several estimators:

- **Ordinary Least Squares (OLS)**
- **Generalized Least Squares (GLS)**
- **Feasible Generalized Least Squares (FGLS) with factor-based error structure**
- **Feasible Generalized Least Squares (FGLS) with spatial autoregressive error structure**

Each estimator is tested on synthetic data generated specifically for this study. The effectiveness of each approach is measured using Mean Squared Error (MSE) and Mean Absolute Error (MAE).

## Installation

1. Clone the repository:
   ```bash
   git clone https://github.com/AymenCode/nar-model-internship.git
   ```
2. Navigate to the project directory:
   ```bash
   cd nar-model-estimators
   ```
3. (Optional) Create and activate a virtual environment:
   ```bash
   python3 -m venv venv
   source venv/bin/activate
   ```
4. Install the required dependencies:
   ```bash
   pip install -r requirements.txt
   ```

## Project Structure

- `NAR_model_OpenSourcePart.ipynb`: Contains the implementation of the different NAR model estimators.
- `README.md`: Project documentation.
- `requirements.txt`: List of dependencies.

## Acknowledgements

I would like to express my profound gratitude to my supervisor, Dr. Olga Klopp, for her exceptional guidance throughout my internship. Her mentorship and steadfast support made this experience highly valuable. Her regular check-ins and insightful discussions greatly enhanced my understanding of the model and the research process, helping me navigate various challenges. Her patience and welcoming attitude were instrumental in fostering a productive learning environment.
I also extend my sincere thanks to Dr. Adeline Fermanian and the Califrais team for allowing me access to their data, which provided invaluable experience with real-world data. Their guidance and responsiveness to my inquiries were immensely beneficial.
Additionally, I am grateful to Dr. Andrea Simonetto, my tutor at ENSTA Paris, for his support, advice, and guidance, which were essential for the progress of my internship.
The combined contributions and support from these esteemed individuals have greatly enriched my learning experience, making this internship both rewarding and enlightening.

