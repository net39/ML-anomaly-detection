# ML Abnormalities Detection in Daily Movements via Home Surveillance Cameras (A Student Project)

This repository contains Python code, Google Colab notebooks and related files for my academic project on anomaly detection using ML models techniques.

**Note:** This is a student research project and not a production-ready software.

## Contents
- Code scripts and Google Colab notebooks
- Model training and evaluation scripts
- References to external public datasets (used with permission)

## Project Objective

To develop a machine learning model for detecting anomalies in human daily behaviours, specifically targeting home surveillance settings and elderly care 
cenarios. The model will classify normal vs. abnormal activities using video and image datasets and explore multi-layer model integration with temporal behavioural 
analysis.

## License

The code in this repository is licensed under the [MIT License](LICENSE).  
You are free to use, modify, and share this code for educational and non-commercial purposes.

## Dataset Usage

This project uses public datasets from Kaggle,
Primary Dataset: Multiple Cameras Fall Dataset (video clips in .avi format)
Secondary Dataset: Human Action Recognition (HAR) Dataset (labelled images in .jpg + .csv)

- [MCFD Dataset](https://www.kaggle.com/datasets/soumicksarker/multiple-cameras-fall-dataset)
- [HAR Dataset](https://www.kaggle.com/datasets/meetnagadia/human-action-recognition-har-dataset/)

Please refer to the respective dataset licenses and terms of use on their Kaggle pages. The datasets are not redistributed in this repository, only referenced for reproducibility.

## Notebook

Various notebooks were created to fulfill this project, however shared in this space are the most relevant.

## Project Environment Setup Overview

Development Tools:
- Google Colab: for coding, training, and experimentation in Python notebooks.
- GitHub Repo: ML-anomaly-detection
- --MIT License applied
- --README.md created for project overview and documentation
- Google Cloud Storage (GCS):
- --Project: p2-anomaly
- --Bucket: p2-anomaly
- Raw data (videos + images from Multiple Cameras Fall and HAR Datasets)

## Steps done

1. Complete data upload into GCS.
2. Mount/connect GCS to Google Colab.
3. Perform dataset validation (file counts, formats, sample displays).
4. Set up directory structures in Colab environment.
5. Begin data preprocessing - Frame extraction from video clips
6. Secondary dataset classification using SVM Modelling
7. Primary dataset action prediction, human prediction and anomaly detection.
8. Models and Output evaluation

## Disclaimer

This is an academic project developed as part of a university course assignment. The code is shared for learning purposes and comes with no warranty.
