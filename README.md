# GANs for Fraud Detection 

![License](https://img.shields.io/static/v1?label=license&message=CC-BY-NC-ND-4.0&color=green)

## Master's in Data Science and Engineering | Advanced Topics of Machine Learning

Authors: [Cátia Teixeira](https://github.com/crdsteixeira) | [Henrique Ribeiro](https://github.com/henriquebr31) | [Ian Karkles](https://github.com/iankarkles) | [Vitor Pereira](https://github.com/vepereira7)

## Description
This work explores the topic of anomaly detection
for credit card fraud. The article provides the background and
characterization of the problem, an overview of related work
and techniques for this task as well as a description of the
methodology and implementation details of a total of fourteen
models. The aim is to explore the task of anomaly detection using
both Data Augmentation and no Data Augmentation, as well as
different Generative Adversarial Networks (GANs) architectures
and different Classification approaches. 

Three different GANs
were used for Data Augmentation: Vanilla GAN (VGAN), Con-
ditional Tabular GAN (CTGAN) and Wasserstein GAN (WGAN).
Three different classification approaches were applied for each
Data Augmentation approach: Classic Machine Learning, Deep
Neural Network (DNN) and Long-Short Term Memory (LSTM).

A WGAN was also used for Anomaly Detection. Additionally,
an innovative Multi-Critic Classifier approach was implemented
based on the probability aggregation of the previously obtained
models (Baseline-DNN, VGAN-DNN, CTGAN-DNN and WGAN-
DNN).


The best results were obtained by the Multi-Critic
Classifier with the better compromise of higher rates of True
Positives (TP) and True Negatives (TN) and lower percentages
of False Positives (FP) and False Negatives (FN): 0.91, 0.95, 0.05
and 0.09 respectively.

<p align='center'>
<img src="https://github.com/crdsteixeira/Advanced-Topics-of-Machine-Learning_Credit-Fraud-Detection-Using-GANs/assets/113851507/21619b5c-bdf6-423d-ae23-6c98ecb926c2"/>
</p>


## Instructions 
- The dataset for this study was obtained through [Kaggle](https://www.kaggle.com/datasets/mlg-ulb/creditcardfraud). It
contains transactions made by credit cards in September 2013 by European cardholders.

- project part A.ipynb: VGAN training and data aug-
mentation as well as its classification using CatBoost,
DNN and LSTM models.

- project part B.ipynb: Baseline classification (without
data augmentation) using CatBoost, DNN and LSTM
models. WGAN training and data augmentation and its
classification using CatBoost, DNN and LSTM models.
Anomaly WGAN implementation. Multi-Critic approach
using Baseline-DNN, VGAN-DNN, CTGAN-DNN and
WGAN-DNN trained models for Classification.

## Credits

The authors would like to thank the Machine Learning
Group of Université Libre de Bruxelles (ULB) for making
the dataset available publicly, and also for its collection
and anonymization preprocessing in collaboration with Wor-
line company.
An additional appreciation to all the referred authors in the report.
