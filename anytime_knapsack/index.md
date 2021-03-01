---
layout: page
title: Anytime Automatic Algorithm Selection for Knapsack
tagline: 
description: Minimal tutorial on making a simple website with GitHub Pages
---
Link to paper: https://www.sciencedirect.com/science/article/abs/pii/S0957417420304371

In this work we address the Algorithm Selection Problem, i.e., the decision of which algorithm to use from a set of alternatives, given an instance. For the selection, we take into account a given time limit as a parameter. Hence, the learning is based on the anytime behavior of the algorithms. We test this approach over the well known **Knapsack Problem**.

### Dataset

* [Knapsack instances](https://drive.google.com/drive/folders/1vr-cJKPvfwQpJDqK5S8iokLqjloJ2SCV)
* [Features](https://drive.google.com/file/d/1AQxOkVo2B7ufJbAUsLuY4k6Y_k2iiPID/view): 21 features for the 15,000 instances. The instance identifier is the index.
* [Solver results](https://drive.google.com/file/d/1bqnlNtV6E3Ct76iKyvL6kB3QKEVfIdHX/view)

For Python, we recommend using pandas to open the files:
```python
import pandas as pd
features = pd.read_csv("features.csv")
solver_results = pd.read_csv("solver_results.csv")
```
