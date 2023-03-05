# Lab 1 - Inventory-Policies
Class: DA350 - 02
DA 350 SP23 Lab 1 - Inventory Policies
![image](https://user-images.githubusercontent.com/77667121/222989302-5d810e2f-31e9-4f1e-8caa-2c5da4845179.png)
General Lab Instructions:
For lab assignments I will provide you the .ipynb file and associated data sets (if any) on Canvas. Please use this .ipynb file as a starting point and write your code and fill in your answers directly in the notebook. I will ask specific questions in bolded font . For written answers, please create the cell as a Markdown type so the text displays neatly. For code, comment sufficiently so I can understand your process. Please try to delete unnecessary, old code so it is easy for me to evluate.

Lab 1:
In this lab you will pose as consultants to help Whit's decide how much custard they should create and stock on a given day. Produce too little, and they lose potential sales and turn away customers. Produce too much, and it may spoil and they have to throw it out. You will explore the connection between predictive and prescriptive analytics and see how the latter can help make decisions like inventory stocking.

Note: The methods presented in this lab are not necessarily the best way to solve the problem. There may exist analytical formulations of the problem which could let us mathematically solve exactly without the need for computation. This lab is intended to introduce the differences between predictive and prescriptive analytics, and demonstrate one way (even if not mathematically the most elegant) to find optimal decisions.
```python
#Import packages
import numpy as np
import pandas as pd
import scipy
import matplotlib.pyplot as plt
```
