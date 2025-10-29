# Enhanced Detection of Specific Attack Types in the NSL-KDD Dataset through Machine Learning Techniques

## Introduction

In the realm of cybersecurity, the detection of network intrusions is a critical challenge. Intrusion Detection Systems (IDS) are essential for identifying unauthorised access or anomalies in network traffic. With the advent of sophisticated cyber threats, effective IDS mechanisms are crucial for maintaining the integrity of information systems.

This report aims to analyse the problem of network intrusion detection, focusing on the application of machine learning techniques to the NSL-KDD dataset. The goal is to recognise a specific attack type in the traffic.

### Problem Analysis

Network intrusion detection is a classification problem in the domain of machine learning. It involves categorising network traffic into 'normal' or 'malicious', with malicious traffic further classified into specific attack types, such as Denial of Service (DoS), Probe, Remote to Local (R2L), and User to Root (U2R) attacks.

#### Challenges

- Imbalanced Data: Intrusion datasets often have an imbalance between normal and attack instances, complicating the training process of machine learning models.
- Evolving Attack Techniques: As attack methods evolve, IDS must adapt to recognise new patterns.
- Feature Selection: Identifying the most relevant features from a large set is crucial for effective model performance.
- Model Generalisation: The model must generalise well to new, unseen data while maintaining high accuracy and low false positives.
- Computational Complexity: The model must be able to process large amounts of data in a reasonable amount of time.
- Interpretability: The model must be interpretable to allow for the identification of attack patterns.

### Literature Review

In the landscape of intrusion detection, the NSL-KDD dataset has been a benchmark for evaluating the performance of various machine learning models. Tavallaee et al. (2009) conducted comprehensive experiments to assess the effectiveness of different algorithms in recognising attack patterns within this dataset. Their study revealed a spectrum of accuracy results, underscoring the varying capabilities of each model. Specifically, the J48 algorithm demonstrated a accuracy of 81.05%, followed closely by the Random Tree model at 81.59%. The performance of the Random Forest model was also notable, achieving an accuracy of 80.67%. Other models, including the NB Tree and Multilayer Perceptron, reported accuracies of 80.02% and 77.41%, respectively. The Naive Bayes model, with an accuracy of 76.56%, and the SVM model, with 69.52%, also contributed valuable insights into the dataset's complexity and the models' predictive abilities.

Building on the foundational work of Tavallaee et al., this project will aim to improve on these results by exploring advanced modeling techniques, fine-tuning model parameters, and employing state-of-the-art preprocessing methods.

## Table of Contents

- [Installation](#installation)

## Installation
