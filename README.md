# Finance Fault Detector

## Table of Contents
1. [Introduction](#introduction)
2. [Project Structure](#project-structure)
3. [Installation](#installation)
4. [Usage](#usage)
5. [Model](#model)
6. [Dataset](#dataset)
7. [Preprocessing](#preprocessing)
8. [Training and Evaluation](#training-and-evaluation)
9. [Deployment](#deployment)
10. [License](#license)

## Introduction
The Finance Fault Detector project aims to identify faults in financial data using a Fully Connected Neural Network (FCNN) built with TensorFlow and Keras. The project involves data preprocessing with Sci-kit learn, training and evaluating the model, and deploying it for testing.

## Project Structure
The project is organized as follows:
```sh
finance-fault-detector
┣ 📂 Cap13
┃ ┣ 📜 dataset.csv
┃ ┣ 📜 novos_dados.csv
┣ 📜 finance-fault-detector.ipynb
┗ 📜 README.md
```

## Installation
To run this project, you need to have Google Colab or a local Jupyter Notebook setup. Follow the instructions below to get started:

1. **Open Google Colab**: Go to [Google Colab](https://colab.research.google.com/).

2. **Upload the Notebook**:
   - Click on `File` > `Upload notebook`.
   - Choose the `finance-fault-detector.ipynb` file from your local machine.

3. **Set Up the Environment**:
   - Ensure you have a Google account to save and execute the notebook.

## Usage
To use the finance fault detector, follow these steps:

1. **Execute the Notebook**:
  - Run each cell in the finance-fault-detector.ipynb notebook sequentially.
  - The notebook includes the following steps:
    - Data loading and preprocessing
    - Model creation and training
    - Model evaluation
    - Model deployment

## Model
 ### Fully Connected Neural Network (FCNN)
    - Framework: TensorFlow and Keras
    - Description: The model is built using TensorFlow and Keras to detect faults in financial data. It consists of multiple fully connected layers.

## Dataset
 ### Cap13 Folder
    - dataset.csv: Contains the primary dataset used for training and evaluating the model.
    - novos_dados.csv: Contains new data for testing the model post-deployment.

## Preprocessing
 ### Library: Sci-kit learn
    = Steps: The data preprocessing involves cleaning, normalizing, and splitting the data into training and testing sets.

## Training and Evaluation
 The notebook includes sections for training and evaluating the FCNN model:
  1. **Training: The model is trained on the preprocessed dataset using TensorFlow and Keras.**
  2. **Evaluation: The model is evaluated on a separate test set to measure its performance.**

## Deployment
  The notebook includes steps to deploy the trained model, allowing it to be tested on new data (found in novos_dados.csv).

## License
  This project is licensed under the MIT License. See the LICENSE file for more information.

---

Feel free to explore the notebook and experiment with different configurations to see how the model performs!
