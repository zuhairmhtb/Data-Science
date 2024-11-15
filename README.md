# Notes on Data Science and Machine Learning

**Python version: 3.12.6**

This repository contains notes on different topics of Data Science and Machine Learning. Each topic contains a detailed discussion, with implementation of the topic using python, and examples that have been solved using each topic. This will hopefully help a person to not only understand the theoretical concepts behind different topics of mathematics and statistics, but also help them to understand how the knowledge can be applied to solve different real world problems.

The folders are numbered according to their increasing order of difficulty. For example, we start with the complete basics of statistics and move on to advanced topics like hypothesis testing and regression. The folders are numbered so that the reader can go through each folder sequentially and thus obtain a clear understanding of the concepts.

I have covered the following topics in this repository:

1. Probablity - Added

2. Statistics - Added

3. Regression - In Progress

4. Clustering

5. Classification

6. Calculus

7. Matrices and Vectors

8. Linear Algebra

9. Supervised and unsupervised learning

10. Multi Layered Perceptrons and the basics of Neural Networks

11. Deep Neural Networks

12. Autoencoders and Transformers

13. Vision and Natural Language Processing

14. Reinforcement learning

15. Transfer learning and fine tuning

16. Basics of computational neuroscience


## Prerequisites

1. Python

2. Mathematics

3. Biology


## Installed packages

1. Scipy

```
conda install anaconda::scipy
```

2. Statsmodel

```
conda install anaconda::statsmodels
```

3. Plotly

```
conda install plotly::plotly
```

4. Kaleido

```
conda install conda-forge::python-kaleido
```

5. Matplotlib

```
conda install conda-forge::matplotlib
```

6. Openpyxl

```
conda install anaconda::openpyxl
```

7. Cufflinks

```
conda install conda-forge::cufflinks-py
```

8. Notebook

```
conda install anaconda::notebook
```

## Running the notebooks

1. To run the notebooks, please install python version 3.12.x using Anaconda.

```
conda create --prefix ./venv python=3.12
```

2. Activate the environment. Install the packages mentioned in requirements.txt using the command:

```
conda activate ./venv
pip install -r requirements.txt
```

3. Run the notebook using the command:

```
conda activate ./venv
jupyter notebook
```

## Issues

1. If you are using plotly and Kaleido in Windows OS system, you may receive the following error if your path to the notebook contains a space in folder name. For example, if the path to your notebook is D:\Accessories\Data Science\notebook.ipynb, you may receive the following error:

```
ValueError: Failed to start Kaleido subprocess. Error stream:

'D:/Accessories/Data' is not recognized as an internal or external command,
operable program or batch file
```

This issue occurs when you have a space in the name of your folder. You can view details [here](https://github.com/plotly/Kaleido/issues/85).

To resolve the issue - delete the venv file, rename your folder to not contain space e.g. DataScience, and reinstall conda environment. 

Another way is to update the library and fix the issue as mentioned in the link above.