---
layout: page
title: Anytime Automatic Algorithm Selection for TSP
tagline: 
---
Link to paper: [https://www.sciencedirect.com/science/article/abs/pii/S0957417421013014](https://www.sciencedirect.com/science/article/abs/pii/S0957417421013014)

This work presents a new **metaheuristic for the euclidean Traveling Salesman Problem (TSP)** based on an **Anytime Automatic Algorithm Selection** model using a portfolio of five state-of-the-art solvers. We introduce a new spatial representation of nodes, in the form of a matrix grid, avoiding costly calculation of features. Furthermore, we use a new compact *Staggered representation* for the ranking of algorithms at each time step. Then, we feed inputs (matrix grid) and outputs (staggered representation) into a classifying convolutional neural network to predict the ranking of the solvers at a given time. We use the available datasets for TSP and generate new instances to augment the number, reaching 6,689 instances, distributed into training and test sets. Results show that the time required to predict the best solver is drastically reduced in comparison to previous traditional feature selection and machine learning methods. Furthermore, the prediction can be obtained at any time and, on average, the metasolver is better than running all the solvers separately on all the datasets, obtaining 79.8% accuracy.

### TSP Instances

* [Generated Instances](https://drive.google.com/drive/folders/1OKzNy0mv0W0jlhauDmmoBiLKIhBDmGlh?usp=sharing) (train)
* [Public Instances](https://drive.google.com/drive/folders/1M4OZIpD2MilHUEp283ofgBTezQcDdnmh?usp=sharing) (test)

### Instance-Solver Executions

* [Solutions](https://drive.google.com/drive/folders/1X9m-mvj1sEovwhRiNpnTrm3ID8SAdVT0?usp=sharing)
