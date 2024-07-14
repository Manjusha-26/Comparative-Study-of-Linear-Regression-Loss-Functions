# Comparative Analysis Linear Regression Loss Functions

## Project Overview
This repository is dedicated to a detailed study of different loss functions used in linear regression models. The project was designed to analyze how Mean Squared Error (MSE), Mean Absolute Error (MAE), and Huber Loss affect the performance and robustness of linear regression algorithms, particularly under varying conditions including outliers. This analysis includes visualizing these loss functions, implementing and comparing both gradient descent and stochastic gradient descent techniques, and examining their efficacy through extensive simulations.

## Detailed Description

### Objectives
- **Visualize Loss Functions**: To understand and compare the behavior of quadratic, absolute, and Huber loss functions under a range of conditions.
- **Implement Optimization Algorithms**: To code gradient descent and stochastic gradient descent from scratch for the specified loss functions.
- **Analyze Model Performance**: To simulate data scenarios and measure how each loss function performs, focusing on stability and accuracy under different conditions including noise and outliers.

### Methodology
- **Loss Function Overlay**: Loss functions are graphed to demonstrate their impact on regression outcomes. Different values of δ for the Huber loss provide insights into sensitivity to outliers.
- **Algorithm Implementation**: Custom implementations for batch and stochastic gradient descent methods are developed to optimize the loss functions.
- **Simulation Studies**: The data is simulated under controlled conditions to test and compare the effectiveness of each approach in practical scenarios. This includes situations with and without outliers to assess the robustness of each loss function.

## File Structure

- `Manjusha_sml-hw2.Rmd`: Comprehensive R Markdown document containing all project code, visualizations, and detailed comments explaining each step of the analysis.

## Installation Instructions

### Prerequisites
Ensure you have the following installed:
- R (Version 4.0 or later recommended)
- RStudio

### Setup
To set up the project environment:
1. Clone this repository: https://github.com/Manjusha-26/Comparative-Study-of-Linear-Regression-Loss-Functions
2. Open the `Manjusha_sml-hw2.Rmd` file in RStudio.

## How to Use
Follow these steps to run the project:
1. Navigate to the R Markdown file in RStudio.
2. Run the chunks sequentially to generate the loss function plots, perform the simulations, and view the results.

## Results
The project outcomes reveal significant differences in how each loss function copes with variability and outliers in data. These results are crucial for understanding which loss functions are best suited for specific real-world data scenarios.

## Contributions
Your contributions are welcome! For major changes, please open an issue first to discuss what you would like to change. Ensure to update tests as appropriate.

## Acknowledgments
- DS 5200 Course Staff
- All data and resources utilized in this project are cited within the R Markdown document.

