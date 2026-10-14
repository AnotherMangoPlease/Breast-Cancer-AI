# Breast-Cancer-AI

### Deep Learning for Breast Histopathology Image Classification

An educational biomedical AI research project exploring the use of deep learning to classify breast histopathology images into four tissue categories: **Normal, Benign, In Situ Carcinoma, and Invasive Carcinoma.**

> **Project status:** In development

## Overview

Breast cancer diagnosis involves examining tissue samples to identify abnormal cellular structures and determine whether cancer is present. Deep learning offers a potential way to analyse histopathology images and identify patterns that may be useful in research.

This project aims to develop a convolutional neural network (CNN) capable of classifying breast histopathology images into four categories. The model will be trained and evaluated using a labelled image dataset, with its performance assessed using appropriate classification metrics.

The broader objective is to explore how machine learning can contribute to biomedical image analysis and support future research into computational pathology.

## Objectives

* Develop a deep learning model for four-class histopathology image classification.
* Apply transfer learning to improve training efficiency.
* Evaluate model performance using quantitative metrics.
* Analyse classification errors to identify limitations and potential sources of bias.
* Build an interactive graphical user interface (GUI) for testing the trained model.
* Document the methodology, experiments, results, and limitations transparently.

## Classification Categories

| Class                  | Description                                                                                                      |
| ---------------------- | ---------------------------------------------------------------------------------------------------------------- |
| **Normal**             | Histopathology images labelled as normal breast tissue.                                                          |
| **Benign**             | Images labelled as benign, non-cancerous breast tissue.                                                          |
| **In Situ Carcinoma**  | Images labelled as carcinoma in situ, where malignant cells remain confined to their original tissue structures. |
| **Invasive Carcinoma** | Images labelled as invasive carcinoma, where cancer has invaded surrounding tissue.                              |

*These are image-level classification categories. The model is not necessarily detecting or locating individual cancer cells.*

## Technology Stack

| Technology         | Purpose                                      |
| ------------------ | -------------------------------------------- |
| Python             | Core programming language                    |
| PyTorch            | Deep learning model development and training |
| Torchvision        | Image transformations and pretrained models  |
| NumPy              | Numerical computation                        |
| Matplotlib         | Visualisation of training results            |
| Scikit-learn       | Classification metrics and evaluation        |
| Google Colab       | Cloud-based development and GPU training     |
| Gradio *(planned)* | Interactive model interface                  |
| GitHub             | Version control and project documentation    |


## Evaluation Metrics

Model performance will be assessed using:

* **Accuracy:** Proportion of correctly classified images.
* **Precision:** Proportion of positive predictions for a class that are correct.
* **Recall:** Proportion of actual examples of a class that are correctly identified.
* **F1-score:** Harmonic mean of precision and recall.
* **Confusion matrix:** Visualisation of correct and incorrect predictions across the four classes.

Where appropriate, additional analyses will examine class imbalance, uncertainty, and the limitations of the dataset.

**Results will be reported after experiments have been completed.** No performance figures are claimed at this stage.


## Dataset and Attribution

This project uses a breast histopathology image dataset obtained from the [Zenodo repository](https://zenodo.org/records/3632035).

The dataset is organised into four categories: Normal, Benign, In Situ Carcinoma, and Invasive Carcinoma.

Dataset attribution and use will follow the applicable licence and distribution conditions. The dataset itself will not be redistributed through this repository without appropriate permission.

## Limitations and Responsible Use

This project is intended for educational and research purposes.

* It is **not a clinically validated diagnostic system**.
* Its predictions must not be used to diagnose, exclude, or treat cancer.
* Performance on one dataset does not establish generalisability to other hospitals, scanners, staining protocols, or patient populations.
* Dataset labelling errors, class imbalance, and differe
