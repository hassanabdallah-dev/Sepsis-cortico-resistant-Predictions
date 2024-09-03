# Corticosteroid Resistance Prediction in Sepsis Patients

## Authors
Hassan Abdallah

## Overview
This project was developed as part of the evaluation for the "Deep Learning" course in my Research Master's in Data Science. The goal is to predict whether a sepsis patient will become cortico-resistant (a bad outcome) or remain cortico-sensitive (a favorable outcome) after receiving corticosteroid medications over several days.

To accomplish this, I utilized an Adaptive Network-Based Fuzzy Inference System (ANFIS) algorithm.

## ANFIS Algorithm
The ANFIS algorithm used in this project is inspired by the work by Karaboga and Kaya:

*Karaboga, D. and Kaya, E., 2019. Adaptive network based fuzzy inference system (ANFIS) training approaches: a comprehensive survey. Artificial Intelligence Review, 52, pp.2263-2293.*

The implementation of ANFIS used in this project is available at the following repository:
[ANFIS Implementation on TensorFlow 2.0](https://github.com/gregorLen/AnfisTensorflow2.0)

I have customized this implementation to suit my specific problem, resulting in a modified version of the algorithm found in `myanfis.py` located in the `code` folder.

## Project Structure
- **`src/`**: Contains the modified ANFIS implementation (`myanfis.py`).
- **`Training.ipynb`**: Jupyter notebook used to train and validate the ANFIS algorithm. This notebook was executed on Google Colab.
- **`Results/`**: Contains the results obtained from the training and validation of the algorithm.

## How to Run
1. Clone this repository.
2. Navigate to the `src/` directory and review the `myanfis.py` implementation.
3. Open `Training.ipynb` in Google Colab to train the model and validate its performance.
4. Review the results stored in the `Results/` folder.

## References
- Karaboga, D. and Kaya, E., 2019. *Adaptive network based fuzzy inference system (ANFIS) training approaches: a comprehensive survey*. Artificial Intelligence Review, 52, pp.2263-2293.
- [ANFIS Implementation on TensorFlow 2.0](https://github.com/gregorLen/AnfisTensorflow2.0)
