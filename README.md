## Introduction

This code follows from my research in modeling the Cahn-Hilliard equation in both the forward and inverse directions. Uses DeepXDE with Tensorflow as its backend, and matplotlib for visualizations.

## Files
- CA2d-**Forward**.ipynb : Notebook for forward problem. Models the phase seperation governed by the Cahn-Hilliard equation.
  
- CA2d-**Inverse**.ipynb : Notebook for inverse problem. Foward output .txt file formatted correctly for inverse input use $$(x, y, t)$$. Predicts epsilon from the data, which is defined in the forward case.
