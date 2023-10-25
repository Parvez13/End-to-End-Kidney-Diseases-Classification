# End-to-End-Kidney-Diseases-Classification

## Objective:

Develop a binary classification model to distinguish between kidney tumors and normal kidney tissues.

## Background:

Kidney diseases, especially kidney tumors, can be life-threatening if not detected and treated early. Early detection can significantly improve the prognosis and reduce the severity of the disease. Therefore, there is a pressing need for reliable methods to classify kidney tissues as either normal or tumorous.

## Dataset Description:

The dataset comprises medical images (or other relevant data types) of kidney tissues from patients across various demographics.

Each entry in the dataset contains:

* `Patient ID`: A unique identifier for each patient.
* `Age`: Age of the patient.
* `Gender`: Gender of the patient.
* `Medical Image`: A medical image (e.g., MRI, CT scan) of the kidney tissue.
* `Label`: A binary label indicating whether the tissue is Normal (0) or Tumorous (1).

## Workflows

* Update config.yaml
* Update secrets.yaml [Optional]
* Update params.yaml
* Update the entity
* Update the configuration manager in src config
* Update the components
* Update the pipeline
* Update the main.py
* Update the dvc.yaml
* app.py

## Deployment
* App deployed on AWS: <https://54.241.138.215/8080>

