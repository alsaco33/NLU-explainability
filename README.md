# NLU Final Project repository

This is the code repository supporting the paper entitled *Towards a holistic framework to evaluate NLP model explanations* written by Paz Vives and Alejandro Saez.

<!-- TABLE OF CONTENTS -->
## Table of contents
  <ol>
    <li> <a href="#context-of-the-study">Context of the study</a> </li>
  <li> <a href="#results-obtained">Results obtained</a> </li>
    <li><a href="#repository-structure">Repository structure</a></li>
  </ol>



<!-- CONTEXT -->
## Context of the study

This paper aims to develop a holistic framework for evaluating Natural Language Processing (NLP) model explanations, considering the critical role of understanding the reasoning behind Machine Learning systems in decision-making. Although various explainability methods exist, their suitability for specific tasks and datasets remains uncertain. Additionally, the ambiguity of what qualifies as an explanation and the lack of commonly agreed-upon ground-truth labels further complicate the issue. This paper proposes an approach to assess the degree of model dependency of popular NLP explainability methods, allowing for a comprehensive evaluation across a range of supervised models, and metrics. The paper's contributions include addressing research biases, providing guidance for evaluating explainability methods, and answering key questions such as the suitability of gradient versus perturbation-based methods for determining explainability under a fixed architecture.

<!-- RESULTS OBTAINED -->
## Results obtained

The results together with supporting discussion and relevant figures can be found under reports/paper.pdf

<!-- REPOSITORY-STRUCTURE -->
## Repository Structure

Below one can find the structure of the repository. A directory containing the raw twitter data with labels and gold explanations can be found under data/train.csv, and 3 sequential notebooks are executed to bridge from raw data to results as seen in /code.

```
NLU-explainability
│   README.md
└───data
│   └───train.csv
└───code
│   └───0. Explainability extraction.ipynb
│   └───1. Metric calculation.ipynb
│   └───2. Metric analysis.ipynb
└───reports
│   └───paper.pdf
```
