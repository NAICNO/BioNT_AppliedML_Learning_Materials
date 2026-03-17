[![DOI](https://zenodo.org/badge/1149796176.svg)](https://doi.org/10.5281/zenodo.19075305)

# BioNT

![alt text](content/images/image.png)

[BioNT](https://biont-training.eu/training.html) is an international consortium dedicated to providing high-quality training and fostering a community for digital skills in the biotechnology and biomedical sectors. The project's training model is built on three core missions:

## Course name

- Applied Machine Learning for Biological Data

## Course description

- [Description provided in the course registration page](https://www.cecam.org/workshop-details/1465)

## Trainers

- Sabry Razick (University of Oslo)
- Pubudu Saneth Samarakoon (University of Oslo)
- Burcin Buket Ogul (University of Oslo)
- Milan De Cauwer (SINTEF Norway)
- Katarzyna Michalowska (SINTEF Norway)
- Elias Myklebust (Simula Research Laboratory)

## Workshop structure and link to learning materials

### Module 1

- [Introduction to Module 1](https://coderefinery.github.io/NumPy-and-Pandas-fundamentals-for-handling-biological-datasets/)

Module 1 (optional) provides a solid foundation in scientific computing with Python. Across two half-day sessions, participants will explore essential data handling techniques using NumPy and Pandas—tools widely adopted for manipulating and analyzing biological data.


| Day | Topics                                                                                                         |
| --- | -------------------------------------------------------------------------------------------------------------- |
| 1   | [NumPy: Fundamentals](https://coderefinery.github.io/NumPy-and-Pandas-fundamentals-for-handling-biological-datasets/0.Numpy_for_bioinformatics/) |
| 2   | [Pandas: Fundamentals](https://coderefinery.github.io/NumPy-and-Pandas-fundamentals-for-handling-biological-datasets/7.Pandas_lesson%20plan/) |

### Module 2

Module 2 spans five full days and begins by introducing core concepts in machine learning. On the first day, the participants will be introduced to unsupervised learning, and they will implement clustering algorithms and dimensionality reduction techniques using real-world genomics data. The workshop then dives into supervised learning with a focus on classification and regression, including logistic regression and tree-based methods. Participants will construct and evaluate ML models, perform cross-validation, and tune hyperparameters in hands-on sessions tailored to cancer genomics datasets. Later sessions introduce deep learning concepts and the PyTorch framework. Participants will learn to build and train simple neural networks and explore a deep learning-based bioinformatics tool used in genomic variant calling. The final day introduces accelerated genomics through GPU-powered workflows. Participants will learn about GPU technology and how to use containerized bioinformatics tools. They will also implement high-performance, GPU-accelerated pipelines using Parabricks.

### Learning Outcomes: 

By the end of this workshop, you will be able to:

- Apply data manipulation techniques using NumPy and Pandas.
- Define essential machine learning terminology and differentiate between supervised and unsupervised learning approaches.
- Implement and evaluate regression and classification models on biological datasets through hands-on coding exercises.
- Apply regularization techniques and hyperparameter tuning to optimize model performance while preventing overfitting.
- Analyze biological questions to determine the most appropriate machine learning approach (regression, classification, clustering).
- Interpret and evaluate machine learning models using appropriate metrics and cross-validation techniques to ensure reliability.
- Develop scripts using PyTorch to build and train simple neural networks and implement deep learning based bioinformatics tools using genomics datasets. 
- Design end-to-end machine learning workflows for biological applications, from data preprocessing to model deployment.
- Implement containerization using Docker to enhance reproducibility and scalability in bioinformatics workflows.
- Compare CPU-native versus GPU-accelerated approaches for genomic data processing and identify computational bottlenecks.


| Day | Topics                                                                                                         |
| --- | -------------------------------------------------------------------------------------------------------------- |
|  1   | [ML terminology and ML in Bioinformatics](Day1/0_Introduction_ml_terminology.pdf)                                                                                                                     |
|     | [Unsupervised Learning: Clustering (K-Means Clustering, Hierarchical clustering, Clustering evaluation metrics)](Day1/1_Unsupervised_Learning.pdf)                                                                                                                     |
|     | [Unsupervised Learning: Dimensionality reduction (Principal component analysis - PCA)](Day1/1_Unsupervised_Learning.pdf)                                                                                                                     |
|     | [Hands-on session demonstrating PCA and clustering in cancer genomics](https://naicno.github.io/BioNT_Module2_handson/1.PCA_n_Clustering/)                                                            |
| 2   | [Classification: Logistic regression; Tree-based methods; Matrices for classification evaluation](Day2/2_ML_classification_topics.pdf)                                                                                                                     |
|     | [Hands-on session demonstrating Logistic regression in cancer genomics](https://naicno.github.io/BioNT_Module2_handson/2.Logistic_regression/)                                                                 |
|     | [Regression: Regression mechanics, Loss function, Regularised regression, Matrices for regression evaluation](Day2/3_ML_Regression_topics.pdf)                                                                                                                     |
| 3   | [Model validation and optimisation (Overfitting and underfitting, Standardising Data, Handling missing data)](Day3/4_Model_optimization_and_validation.pdf)                                                                                                                     |
|     | [Model validation and optimisation (K-fold cross-validation)](Day3/4_Model_optimization_and_validation.pdf)                                                                                                                     |
|     | [Hands-on session: ML workflow with biological data](https://naicno.github.io/BioNT_Module2_handson/3.ML_workflow/)                                                                                                 |
| 4   | [Introduction to deep learning (Basic concepts of Neural Networks - NN; Simple NN with PyTorch)](Day4/introduction_to_deep_learning.pdf)                                                                                                                     |
|     | [Hands-on session demonstrating deep-learning-based variant calling via DeepVariant](https://naicno.github.io/BioNT_Module2_handson/4.DeepVariant/)                                                                                  |
| 5   | [Introduction to Accelerated Genomics (NGS data analysis, GPU introduction)](https://coderefinery.github.io/BioNT_Lesson_Accelerated_Genomics)                                 |
|     | [GPU introduction](https://coderefinery.github.io/BioNT_Lesson_Accelerated_Genomics)                                                                                           |
|     | [Docker introduction](https://training.pages.sigma2.no/tutorials/gpu-intro/)                                                                                        |
|     | [Hands-on session on implementing accelerated Genomics workflows with Parabricks on VM with GPUs](https://coderefinery.github.io/BioNT_Lesson_Accelerated_Genomics/04.Hands-on/)                                                 |


- [Link to the Sphinx Page](https://naicno.github.io/BioNT_AppliedML_Learning_Materials/)
