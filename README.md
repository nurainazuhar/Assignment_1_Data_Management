# Iris Species Classification with Spark MLlib



## Project Overview
This project was developed for STQD6324 Data Management Assignment 1. The objective of this assignment is to perform a multiclass classification task using the Iris dataset with Spark MLlib.

Several machine learning classification algorithms were implemented, tuned, evaluated, and compared to identify the best-performing model for iris species prediction.

The project demonstrates the complete machine learning workflow including:

- Data Loading: Automated retrieval of the Iris dataset from a public repository.
- Data Preprocessing: Transforming categorical labels using StringIndexer and combining features into vectors with VectorAssembler.
- Model Training & Tuning: Systematic hyperparameter optimization using CrossValidator and ParamGridBuilder.
- Evaluation: Comparing models using Accuracy and F1-Score to ensure performance across all classes.
- Visualization: Visualizing classification boundaries and logic to interpret model behavior.
  
## Dataset
The project uses the famous Iris dataset, which contains measurements of iris flowers from three different species:

| Iris Setosa | Iris Versicolor | Iris Virginica |
|:---:|:---:|:---:|
| <img src="setosa.jpg" width="200"> | <img src="versicolor.jpg" width="200"> | <img src="virginica.jpg" width="200"> |

### Features
The dataset contains four numerical features:
- Sepal Length:	Length of sepal (cm)
- Sepal Width:	Width of sepal (cm)
- Petal Length:	Length of petal (cm)
- Petal Width:	Width of petal (cm)

 ### Target Variable
 - Species:	Iris flower species
   
## Methodology

## Results
