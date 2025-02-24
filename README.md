# Explainable_Battery_Twins
This repository contains the official implementation of the paper:
"Explainable Data-Driven Digital Twins for Predicting Battery States in Electric Vehicles"
by Judith Nkechinyere Njoku, Cosmas Ifeanyi Nwakanma, and Dong-Seong Kim (IEEE)

The main goal of this work is to leverage digital twins to predict the State of Charge (SoC) and State of Health (SoH) of electric vehicle batteries using deep learning models (DNNs, LSTMs). 
Additionally, we integrate Explainable AI (XAI) techniques (like SHAP, LIME, and surrogate modeling) to ensure that the predictions are transparent, interpretable, and trustworthy.

## Key Contributions
1. Data-Driven Twins: Establishing a pipeline that combines battery data with AI models to build robust digital twins for EV batteries.
2. Multi-Model Approach: Implementations of DNN and LSTM architectures for SoC/SoH prediction.
3. Explainable AI Layer: Integration of SHAP, LIME, and linear surrogate models to visualize and interpret predictive features and model decisions.
4. Comprehensive Evaluation: Use of metrics such as R², MSE, MAE, and run-time complexity to validate model performance in real or simulated BMS scenarios.

## Repository Contents
* XAI-Digital-Twin-Battery-SoC.ipynb
Demonstrates how to load the dataset, train a deep learning model (DNN or LSTM) to predict battery SoC, and apply XAI methods to understand predictions.

* XAI-Digital-Twin-Battery-SoH.ipynb
Similar structure to SoC, but tailored for SoH predictions. Also demonstrates how to use XAI frameworks to interpret the battery’s degradation patterns.

## Citation
If this work helps you in your research or project, please cite:


@ARTICLE{10555281,
  author={Nkechinyere Njoku, Judith and Ifeanyi Nwakanma, Cosmas and Kim, Dong-Seong},
  journal={IEEE Access}, 
  title={Explainable Data-Driven Digital Twins for Predicting Battery States in Electric Vehicles}, 
  year={2024},
  volume={12},
  number={},
  pages={83480-83501},
  keywords={Batteries;Estimation;Artificial intelligence;Predictive models;Digital twins;Electric vehicles;Long short term memory;Battery management systems;Explainable AI;Machine learning;Battery management systems;digital twins;artificial intelligence;XAI;explainable artificial intelligence;machine learning},
  doi={10.1109/ACCESS.2024.3413075}
}
