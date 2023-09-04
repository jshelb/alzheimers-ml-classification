# Alzheimers-Classification
Machine Learning - Final Project [S2023]

Contributions from:

Jackson Shelby 

Josh Scherer

Michelle Wang

Alex Zhang

# File Structure

```
Alzheimers-Classification (this repository)
+-- project-checkpoint
|   +-- Neural_Network_Guided_Practice.ipynb
|   +-- Images_For_Checkpoint
|   |   +-- table_queries
+-- model
...

data (Not inside this repository)
+-- AugmentedAlzheimerDataset
|   +-- MildDemented
|   +-- ModerateDemented
|   +-- NonDemented
|   +-- VeryMildDemented
+-- OriginalDataset
|   +-- MildDemented
|   +-- ModerateDemented
|   +-- NonDemented
|   +-- VeryMildDemented

pickles (Also not inside this repository)
```

# Important Notes

* We did not include the data directory inside of the repository to avoid file size issues with GitHub
* Services such as AWS may be used to avoid local storage if desired, but is not required

# Instructions for Obtaining Data
* Go to https://www.kaggle.com/datasets/uraninjo/augmented-alzheimer-mri-dataset
* Download the dataset. It should be in a zip file called archive.zip
* Extract all files into a sibling directory from this repository called data

# Models
All ML models and analysis can be found under the `models` directory

Each model used has a sub-directory within `models` where this analysis is conducted

It is important to note that all files are Notebooks, and are intended to hold results (and, therefore, not necessarily intended to be re-run)

# Data Exploration
All data exploration is conducted under the `data-exploration` directory

Here, we explore our dataset and reach key conclusions that will be used when creating our ML models

