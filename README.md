# Rock or Mine Prediction System

This project builds a system in Python that predicts whether an object is a **Rock** or a **Mine** based on SONAR data. We use a **Logistic Regression** model for the prediction.

## Project Overview

This system classifies objects based on the SONAR dataset, which consists of different features representing sound frequencies bounced off from objects. The goal is to determine if the object is a rock or a mine based on this data.

## Dataset

- The dataset used in this project is the **SONAR data**.
- It has 60 features (representing sound frequencies) and a target label (either `R` for Rock or `M` for Mine).
- You can download the dataset from [this Google Drive link](https://drive.google.com/drive/folders/1_63Ie10w_RQZ8KUVoaPN_p_1mexa_vlN?usp=sharing).

## Dependencies

The project uses the following libraries:
- `numpy`
- `pandas`
- `scikit-learn`

You can install these dependencies by running:

```bash
pip install -r requirements.txt
