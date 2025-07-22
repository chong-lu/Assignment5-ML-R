# Assignment 5: Machine Learning in R

This project contains a simple machine learning workflow using the Iris dataset in R. Multiple classification algorithms are trained and evaluated using the `caret` package. The process is documented in a Jupyter Notebook using the R kernel.

## Project Structure

```
Assignment5-ML-R/
├── environment.yml             # Conda environment definition for R kernel and dependencies
├── machine-learning-in-r.ipynb # Main notebook with R-based modeling code
├── iris.csv                    # input data file
└── README.md                   # Project documentation
```

## Goals

* Load and explore the Iris dataset
* Apply a set of linear, nonlinear, and ensemble classification algorithms
* Use stratified k-fold cross-validation for model evaluation
* Compare model performance using accuracy as the metric and visualization

## Models Implemented

* Linear Discriminant Analysis (LDA)
* Classification and Regression Trees (CART)
* K-Nearest Neighbors (kNN)
* Support Vector Machines with Radial Basis Kernel (SVM-RBF)
* Random Forest

## Evaluation Method

* Stratified K-Fold Cross-Validation (k=10)
* Accuracy used as the evaluation metric
* `train()` and `resamples()` from the `caret` package

## R Packages Used

The following R packages are used in this project:

* `caret`
* `ggplot2`
* `MASS`
* `rpart`
* `class`
* `randomForest`
* `kernlab`

## Getting Started

### Requirements

You can set up the project environment using the provided `environment.yml` file:

```bash
conda env create -f environment.yml
conda activate ml-r
```

### Running the Notebook

1. Clone the repository:

```bash
git clone https://github.com/chong-lu/Assignment5-ML-R.git
cd Assignment5-ML-R
```

2. Launch Jupyter Lab:

```bash
jupyter lab
```

3. Open `machine-learning-in-r.ipynb` and run each cell sequentially.

## License

This repository is intended for educational use only.

## Acknowledgments

* Based on Jason Brownlee's structured workflow, adapted to R using the caret package

Source: [https://machinelearningmastery.com/machine-learning-in-r-step-by-step/](https://machinelearningmastery.com/machine-learning-in-r-step-by-step/)
