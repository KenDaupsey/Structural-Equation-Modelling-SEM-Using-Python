# Structural Equation Modeling (SEM) Using Python

This repository provides a comprehensive implementation of Structural Equation Modeling (SEM) using Python and the `semopy` library. SEM is a statistical technique that combines factor analysis and path analysis to analyze the structural relationships between observed and unobserved (latent) variables.

## Project Overview

Structural Equation Modeling is a powerful statistical approach used in various fields, including psychology, social sciences, and economics. This project demonstrates how to define and fit an SEM model, analyze parameter estimates, calculate additional SEM statistics, and visualize the model and relationships.

The analysis includes the following steps:

1. **Data Loading and Exploration**: The project starts by loading the dataset and examining its structure, columns, and summary statistics.

2. **SEM Model Definition**: The SEM model is defined using the `semopy` library, specifying the measurement model (relationships between observed variables and latent variables) and the structural model (relationships between latent variables).

3. **Model Fitting**: The SEM model is fit to the dataset using the `semopy` library's `Model` class.

4. **Model Evaluation**: The project analyzes the parameter estimates and calculates additional SEM statistics, such as goodness-of-fit indices and model fit measures, using the `calc_stats` function.

5. **Visualization**: The project includes visualizations to aid in understanding the SEM model and its relationships, including a 3D scatter plot with color-coding based on observed variables and a SEM diagram generated using the `semplot` function.

## Dataset

The analysis is performed on the `StructuralEquationData.csv` dataset, which contains information about academic ability, motivation, test scores, homework completion, and disciplinary incidents for a sample of students.

## Requirements

To run this project, you need to have the following dependencies installed:

- Python 3.x
- pandas
- numpy
- statsmodels
- matplotlib
- semopy

You can install the required packages using pip:

```
pip install pandas numpy statsmodels matplotlib semopy
```

## Usage

1. Clone this repository to your local machine.
2. Navigate to the project directory.
3. Open the Jupyter Notebook or Python script file.
4. Run the cells or script to execute the code.

The code will perform the steps mentioned in the Project Overview section, including data loading, SEM model definition, model fitting, model evaluation, and visualization.

## Contributing

Contributions to this project are welcome. If you find any issues or have suggestions for improvements, please open an issue or submit a pull request.

## License

This project is licensed under the [MIT License](LICENSE).

## Acknowledgments

This project was inspired by the need to provide a comprehensive example of Structural Equation Modeling using Python and the `semopy` library.
