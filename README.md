Machine Learning for Economists (57750)
================

### Spring 2023 @ Hebrew University of Jerusalem

Instructor: [Itamar Caspi](https://itamarcaspi.rbind.io)

Teaching assistant: [Ariel Karlinsky](https://akarlinsky.github.io/)

:spiral_calendar: Second semester, 2022-2023
:alarm_clock:     16:30 - 19:15
:hotel:           Social Sciences 2202
:writing_hand:    [github.com/ml4econ](https://github.com/ml4econ/lecture-notes-2023)
:family:          [Moodle Discussion Forum](https://moodle2.cs.huji.ac.il/nu22/mod/forum/view.php?id=286095)

-----

## Overview

This course encompasses a wide range of topics including data science, machine learning, and econometrics. Its primary objective is to acquaint students with the fundamental concepts of machine learning that can potentially enhance empirical economics. The course introduces popular supervised and unsupervised machine learning methods, while emphasizing the challenges and opportunities of incorporating these methods in empirical economics. Additionally, it highlights the relevance of machine learning to policy analysis and causal inference. The course utilizes real-world applications, empirical articles, and hands-on assignments to illustrate various topics.

## Learning objectives

During the course, attendees will gain proficiency in the following:

1. Implementing data science best-practices in the context of empirical research within economics.

2. Acquiring comprehensive and pragmatic knowledge of the obstacles and prospects encountered in applied empirical work utilizing high-dimensional data.

3. Assimilating techniques and insights from the field of machine learning into applied empirical research conducted in economics.


## Prework

It is anticipated that participants in the course will:

1. Possess their own computers with R, RStudio (Posit), Git, and GitHub Desktop installed.

2. Register for a GitHub and Kaggle account, which are available at no cost.


## Schedule

The following schedule is subject to change based on class interests and time constraints. Our pace will be guided by class discussions, and we kindly request that you check this page regularly for updates.

| Week                  | Topic                                               |
|:----------------------|:----------------------------------------------------|
| [**1**](#week-1)      | Course Overview                                     |
| [**2**](#week-2)      | Basic ML Concepts                                   |
| [**3**](#week-3)      | Reproducibility & ML Workflow                       |
| [**4**](#week-4)      | Regression and Regularization                       |
| [**5**](#week-5)      | Classification                                      |
| [**6**](#week-6)      | Trees and Forests                                   |
| [**7**](#week-7)      | Causal inference                                    | 
| [**8**](#week-8)      | High-Dimensional Counfounding Adjustment            |
| [**9**](#week-9)      | High-Dimensional Heterogeneous Treatment Effects    |
| [**10**](#week-10)    | Text Analysis                                       |
| [**11**](#week-11)    | Large Language Models                               |


## Slides

### Part I: Supervised Machine Learning

1. Course Overview [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/01-overview/01-overview.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/01-overview/01-overview.pdf) 

2. Basic ML Concepts [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/02-basic-ml-concepts/02-basic-ml-concepts.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/02-basic-ml-concepts/02-basic-ml-concepts.pdf) 

3. Reproducibility and Version Control [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/03-reprod-vc/03-reprod-vc.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/03-reprod-vc/03-reprod-vc.pdf)  

4. A Typical (Supervised) ML Workflow [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/04-ml-workflow/04-ml-workflow.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/04-ml-workflow/04-ml-workflow.pdf)

5. Regression and Regularization
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/05-regression-regularization/05-regression-regularization.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/05-regression-regularization/05-regression-regularization.pdf)  
  5.1 [Prepare browser data](https://raw.githack.com/ml4econ/lecture-notes-2023/master/05-regression-regularization/05-prepare-browser-data.html)  
  5.2 [Ridge and lasso simulation](https://raw.githack.com/ml4econ/lecture-notes-2023/master/05-regression-regularization/05-simulations.html)  
  5.3 [Ridge, lasso, PCR and PLS: A Tidymodels Workflow](https://raw.githack.com/ml4econ/lecture-notes-2023/master/05-regression-regularization/05-tidymodels-workflow.html)

6. Classification
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/06-classification/06-classification.html) [(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/06-classification/06-classification.pdf)  
  6.1[Classification: A Tidymodels workflow](https://raw.githack.com/ml4econ/lecture-notes-2023/master/06-classification/06-tidymodels-workflow-covid.html)
  
7. Trees and Forests
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/07-trees-forests/07-trees-forests.html) [(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/07-trees-forests/07-trees-forests.pdf)

### Part II: Causal Inference and ML

8. Causal Inference
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/08-causal-inference/08-causal-inference.html) [(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/08-causal-inference/08-causal-inference.pdf)

9. High-Dimensional Confounding Adjustment
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/09-lasso-ate/09-lasso-ate.html) [(PDF)](https://github.com/ml4econ/lecture-notes-2023/blob/master/09-lasso-ate/09-lasso-ate.pdf)

10. High-Dimensional Heterogeneous Treatment Effects
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/10-trees-cate/10-trees-cate.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/10-trees-cate/10-trees-cate.pdf)

### Part III: Language Models

11. Text Mining
[(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/11-text-mining/11-text-mining.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/11-text-mining/11-text-mining.pdf)

12. Large Language Models (LLMs) [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/12-llms/12-llms.html) [(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/12-llms/12-llms.pdf)  

### Part IV: Miscellaneous

TBA

### Projects

A. Kaggle competition [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/a-kaggle/a-kaggle.html)
[(PDF)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/a-kaggle/a-kaggle.pdf)  
B.Replication Project Example [(HTML)](https://raw.githack.com/ml4econ/lecture-notes-2023/master/b-replication/Ariel%20Karlinsky%20-%20Replication.html)


## Readings

Can be found [here](https://github.com/ml4econ/lecture-notes-2023/blob/master/resources.md).

## People

+ [**Itamar Caspi**](https://itamarcaspi.rbind.io) is Head of the Monetary Analysis Unit in the Research Department of the Bank of Israel, and an adjunct lecturer at the Hebrew University, having started off in 2010 as an Economist at the Ministry of Finance. In 2012 he moved to the Bank of Israel, and was promoted in 2018 to Senior Economist and elected to represent the Bank as a Research Fellow for three months at the Bank for International Settlements in Switzerland. He holds a BA in Economics and Business Administration from Ben-Gurion University, MA in Economics from the joint research program at Hebrew University and Tel-Aviv University, and a PhD in economics from Bar-Ilan University.

+ [**Ariel Karlinsky**](https://akarlinsky.github.io/) is an Economist and Statistician, a PHD Student in Economics at the Hebrew University.He mostly does empirical work, my primary research interests are Labor Economics, Data Science, Economics of Conflict, Health Economics, Economics of Israel and Economic History. Ariel is the creator and maintainer of the World Mortality Dataset, an open dataset that tracks all-cause-mortality data from around the world. I’m a member of the World Health Organization Technical Advisory Group on COVID-19 Mortality Assessment. member of The Israeli Economic History Association and Midaat, an NGO dedicated to promoting public health via evidence based medicine and practices.
-----

![](https://i.creativecommons.org/l/by/4.0/88x31.png) This work is
licensed under a [Creative Commons Attribution 4.0 International
License](https://creativecommons.org/licenses/by/4.0/).

