## Escuela Colombiana de Ingeniería

# Alzheimer data set

This project is an analysis of the [Alzheimer Features](https://www.kaggle.com/datasets/brsdincer/alzheimer-features) data set taken from Kaggle where it reads a cvs file, gives information of the missing values of the data set with a graph, imputes data in the missing values, and plots an histogram, a scatter plot and its correlation matrix.

### Prerequisites

+ R
+ Jupyter Notebook
+ Git

### Installing

To download this project, you must run the following command down below.

```
https://github.com/JuanPablo70/PGAD-Assignment02.git
```

If you haven't set the R kernel on your computer, download and install [R for Windows](https://cran.r-project.org/bin/windows/base/) on your computer. Once R is installed, run the following commands in the R terminal:

```
install.packages(c('repr', 'IRdisplay', 'evaluate', 'crayon', 'pbdZMQ', 'devtools', 'uuid', 'digest'))

install.packages('IRkernel')

IRkernel::installspec() or IRkernel::installspec(user = FALSE) #install system-wide
```

Taken from [RUNNING R ON JUPYTER NOTEBOOK WITH R KERNEL (NO ANACONDA)](https://simply-python.com/2019/06/24/running-r-on-jupyter-notebook-with-r-kernel-no-anaconda/).

### Running the notebook

Once you have opened the ```AlzheimerFeatures.ipynb``` file, run each cell with ```shift``` + ```Enter``` or go to the Cell tab and click on ```Run All``` and see the results.

### Author

Juan Pablo Sánchez Bermúdez
