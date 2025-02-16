# Single cell habituation models

Code to reproduce the simulations and figures in the following paper:

Lina Eckert, **Maria Sol Vidal-Saez**, Ziyuan Zhao, Jordi Garcia-Ojalvo, Rosa Martinez-Corral and Jeremy Gunawardena. Biochemically plausible models of habituation for single cell learning, *Current Biology*, Vol 34, Issue 24 (2024). 

This study explores how single cells can exhibit habituation, a fundamental form of learning typically associated with animals. The authors propose mathematical models based on biochemical networks that replicate all seven single-stimulus habituation hallmarks identified in neuroscience. These models rely on common molecular motifs, such as: negative feedback and incoherent feedforward loops.


See [paper](https://www.cell.com/current-biology/fulltext/S0960-9822(24)01430-1) for more details. 

The code allows to simulate habituation of a system defined as a set of ODEs in response to a square-wave input and calculate relevant properties like habituation time (ht) and recovery time (rt). Specific systems with appropriate parameter sets are also provided.
All figure papers can be reproduced from the notebook paper_figures_all.ipynb.
There is also the code to reproduce the models originally proposed by Staddon, as we discuss in the paper. 

