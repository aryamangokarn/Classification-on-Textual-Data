# Classification-on-Textual-Data

This repository contains code and data for an end-to-end text classification pipeline to categorize news articles into different topics like sports, climate, etc. The project was completed as part of the ECE 219 Large-Scale Data Mining course at UCLA.

## Project Overview

Statistical classification broadly refers to the task of learning to identify a subset of categories that pertain to a data point (sample of text, an image, a video clip, a time-signal etc..) from a predefined (generally human-guided) larger set of categories. The model attempts to master the task given a training data set (that is kept separate from an evaluation set) in which each data point is pre-labeled with their “correct” category membership/s. In this project, we deal with the classification of text data. The project consists of building an end-to-end pipeline to classify samples of news articles and involves the following ML components:

1. **Feature Extraction:** Construction of TF-IDF representations of textual data.
2. **Dimensionality Reduction:** Principal Component Analysis (PCA) and non-Negative Matrix Factorization (NMF) - Generally necessary for classical ML methods.
3. **Application of Classification Models:** Applying common classification methods to the extracted features such as Logistic/Linear Classification and Support Vector Machines.
4. **Evaluation the Pipeline:** Evaluating and diagnosing classification results using Grid- Search and Cross Validation.
5. **Replace corpus-level features with pretrained features:** To apply pre-training to a downstream classification task and evaluate comparative performance.

## Usage
The notebook is self-contained with detailed explanations of each step.

## Results
The project report report.pdf describes the implemented approaches, analyzes the results, and provides visualizations of the models' performance on the test dataset.

## Acknowledgments
We thank Professor Vwani Roychowdhury and the course staff of ECE 219 for their guidance on this project.
