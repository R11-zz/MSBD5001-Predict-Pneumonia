# Predicting pneumonia in kidney transplant recipients
**MSBD5001 - Spring 2022 | yzhangml | 20797154**

## Table of Contents

* [1. Data Desciption](#1)
* [2. Data Exploration](#2)
* [3. Model](#3)
* [4. Results](#4)

## Contents

<h3 id="1">1. Data Desciption</h3>

Dataset is given in https://www.kaggle.com/competitions/msbd5001-spring-2022/data.

- train.csv - the training set
  - 12 attributes
  
    - 11 quantative attributes: 
        'MO HLADR+ MFI (cells/ul)', 'Neu CD64+MFI (cells/ul)','CD3+T (cells/ul)', 'CD8+T (cells/ul)', 'CD4+T (cells/ul)','NK (cells/ul)', 'CD19+ (cells/ul)', 'CD45+ (cells/ul)', 'Age','Mono CD64+MFI (cells/ul)'
    
    - 1 categorical attributes:
        'Sex 0M1F'
        
  - 1 label

- test.csv - the test set

<h3 id="2">2. Data Exploration</h3>

Before prediction, view the data distribution and correlation between attributes. [Data Exploration.ipynb](data/Data Exploration.ipynb)


<h3 id="3">3. Models</h3>

<h3 id="4">4. Results</h3>


