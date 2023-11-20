# Digital Mind: Detecting Depression and Anxiety through Social Media Data

## Overview

This repository contains the code and report for the project "Unveiling the Digital Mind: Leveraging Social Media Data for Detecting Depression and Anxiety" conducted by Dina Khalid, Alaa Yasser, Omnia Sayed, and Mohammad Nasser from Cairo University, Egypt.

## Abstract

This project investigates the classification of mental health states (normal, anxiety, and depression) by combining two distinct datasets using machine learning algorithms. The achieved testing accuracies are approximately 95% on both datasets. By integrating results from individual classifications, a final model capable of accurately categorizing individuals into normal, anxiety, or depressed states is obtained.

## Team members

1. Dina Khalid - [Email](mailto:dina.salama00@eng-st.cu.edu.eg)
2. Alaa Yasser - [Email](mailto:alaa.hameed01@eng-st.cu.edu.eg)
3. Omnia Sayed - [Email](mailto:omnia.hassaunien99@eng-st.cu.edu.eg)
4. Mohammad Nasser - [Email](mailto:mohamed.mohamed0116@eng-st.cu.edu.eg)

## Table of Contents

- [Introduction](#i-introduction)
- [What will you find in the IEEE paper-like report and the code notebook?](#what-will-you-find-in-the-ieee-paper-like-report-and-the-code-notebook)
- [Related Work](#ii-related-work)
- [Dataset and Features](#iii-dataset-and-features)
- [Methods](#iv-methods)
- [Experiments](#v-experiments)
- [Results](#vi-results)
- [Code Notebook](#vii-code-notebook)
- [Conclusion](#viii-conclusion)
- [Future Work](#ix-future-work)
- [References](#references)

## Introduction

The project explores the potential of utilizing social media data to detect depression and anxiety. It employs machine learning and natural language processing techniques to identify indicators of mental health issues within user-generated content on platforms like Twitter, Facebook, or Reddit.

### What will you find in the IEEE paper-like report and the code notebook?
## Related Work

The related work section provides a literature review on classifying mental health states using social media data. It compares and analyzes relevant papers, highlighting the state-of-the-art and comparing them to the current project.

## Dataset and Features

This section explains the dataset used, preprocessing steps, and feature extraction techniques. It details the steps involved in preparing the data for model training, including the removal of punctuation, converting text to lowercase, and other preprocessing steps.

## Methods
<p align="center">
  <img align="center" src="https://github.com/alaayasser01/Unveiling-the-Digital-Mind/blob/main/readme_images/block%20diagram.png" alt="block diagram">
  <p align="center">block diagram</p>
</p>


The methods section outlines the machine learning model used, specifically the Support Vector Classifier (SVC) with a radial basis function (RBF) kernel. It explains the use of TF-IDF features and the rationale behind choosing this approach.

## Experiments

The experiments section discusses the development of sequential models and a dataset merging experiment. It includes information on preprocessing steps, feature extraction methods, and the rationale behind selecting the TF-IDF approach.

## Results

This section presents the results of various machine learning models, including Naive Bayes, Random Forest, Gradient Boosting, Decision Tree, Bagging Classifier, and Support Vector Classifier (SVC). It includes accuracy results and a confusion matrix for the selected SVC model.

<p align="center">
  <img align="center" src="https://github.com/alaayasser01/Unveiling-the-Digital-Mind/blob/main/readme_images/TFIDF%20results.png" width="300" alt="TFIDF results">
  <img align="center" src="https://github.com/alaayasser01/Unveiling-the-Digital-Mind/blob/main/readme_images/embedding%20results.png" width="300" alt="embedding results">
</p>

**Confusion Matrix for SVC:**
<p align="center">
  <img align="center" src="https://github.com/alaayasser01/Unveiling-the-Digital-Mind/blob/main/readme_images/confusion%20matrix%20for%20SVC.png" width="280" alt="confusion matrix for SVC">
</p>

## Code Notebook

The notebook includes code for data preprocessing, feature extraction, model training, and evaluation.

## Conclusion

The conclusion summarizes the key findings of the project, emphasizing the potential of using social media data and machine learning for proactive mental health support.

## Future Work

The future work section outlines potential enhancements and expansions of the project. It discusses plans for gathering a culturally relevant dataset in Arabic and incorporating multimedia elements into the data collection process.

## References

The references section lists the academic papers and resources referenced in the project.

## Your feedback and collaboration are highly valued. Feel free to delve into the details, and I'm open to discussions and contributions!
---
