End-to-End-Chest-Cancer-Classification-using-MLflow-DVC

Workflows

1: Update config.yaml

2: Update secrets.yaml [Optional]

3: Update params.yaml

4: Update the entity

5: Update the configuration manager in src config

6: Update the components

7: Update the pipeline

8: Update the main.py

9: Update the dvc.yaml


dagshub
MLFLOW_TRACKING_URI=https://dagshub.com/Abhishek1234567899/Chest-Cancer-Classification.mlflow

MLFLOW_TRACKING_USERNAME=Abhishek1234567899

MLFLOW_TRACKING_PASSWORD=2d643829b746068def0baeb649a115ba9972a347
python script.py

Run this to export as env variables:

export MLFLOW_TRACKING_URI=https://dagshub.com/Abhishek1234567899/Chest-Cancer-Classification.mlflow

export MLFLOW_TRACKING_USERNAME=Abhishek1234567899

export MLFLOW_TRACKING_PASSWORD=2d643829b746068def0baeb649a115ba9972a347

DVC cmd

1: dvc init

2: dvc repro

3: dvc dag
