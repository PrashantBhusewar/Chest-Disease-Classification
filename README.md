# Chest-Disease-Classification

## Project Overview:
Developed a deep learning model to classify CT scan images as either normal or indicative of Adenocarcinoma cancer. This project aims to assist radiologists in early and accurate detection of lung cancer, potentially improving patient outcomes.

## Objectives:

To preprocess CT scan images for optimal model training.
To build and train a convolutional neural network (CNN) for binary classification.
To evaluate the model's performance using appropriate metrics.

## Dataset:

Utilized a publicly available dataset of CT scan images.
Dataset included labeled images for normal and Adenocarcinoma cases.

## Model Used
VGG16 with custom dataset (Chest Dataset).

👨‍💻 Tech Stack Used
1. Python
2. Flask
3. Tensorflow
4. Docker
5. MLflow
6. DVC (Data Version Control)

🌐 Infrastructure Required.
1. AWS 
2. AWS EC2
3. AWS ECR
4. Git Actions
5. Jenkins

**Artifact**: Stores all artefacts created from running the application

**Components**: Contains all components of the Machine Learning Project

## Steps

### Main Components
- Data Ingestion
- Prepare Base Model
- Model Trainer
- Model Evaluation With MLflow

### Workflows
- Update config.yaml
- Update params.yaml
- Update the entity
- Update the configuration manager in src config
- Update the components
- Update the pipeline
- Update the main.py
- Update the dvc.yaml
