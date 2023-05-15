# Centralized vs Decentralized Pricing Controls for Dynamic Matching Platforms: Simulation and Analysis Code

This repository contains the simulation and analysis code for the paper "Centralized Versus Decentralized Pricing Controls for Dynamic Matching Platforms." The paper examines the effects of centralized and decentralized pricing controls on online service platforms using a fluid model of dynamic two-sided matching. Our simulations and analysis compare various degrees of centralization and their impact on social welfare. 

The simulations were implemented in Mathematica and Python, and the data analysis and plotting were done in R. In this repository, you'll find the necessary files to replicate our simulations.

## Dependencies

The following software and package versions were used in this project:

### Mathematica

- Mathematica 11.2.0 for Microsoft Windows (64-bit)

### Python

- Python 3.7.3
- NumPy 1.16.2
- pandas 0.24.2
- scipy 1.2.1
- matplotlib 3.0.3

### R

- R version 4.1.0 (2021-05-18)
- ggplot2 3.3.6
- data.table 1.14.0
- gridExtra 2.3
- latex2exp 0.5.0
- ggnewscale 0.4.7
- plyr 1.8.6
- paletteer 1.5.0.9000
- grDevices 4.1.0
- ggpubr 0.4.0


## Directory Structure

- `mathematica/`: Folder containing Mathematica notebooks for the simulations
- `python/`: Folder containing Python scripts for the simulations
- `r/`: Folder containing R scripts for data analysis and plotting
- `data/`: Folder containing simulation results to generate the figures in the paper 

## Usage

### Running Mathematica Simulations

1. Open the desired Mathematica notebook in the `mathematica/` folder.
2. Run the notebook `MathematicaRunFile` to perform the simulations and generate output files. For detailed analysis of the underlying code, go to the notebook `SystemOfPolynomialsOnly`.

### Running Python Simulations

1. Navigate to the `python/` folder.
2. Run the desired simulation using the Jupyter notebook `SimulationCodeForSubmission.ipynb`.

### Analyzing and Plotting Results with R

1. Navigate to the `r/` folder in your terminal.
2. Run the R script in the Jupyter notebooks `Figures_RcodeForPiecewisePolynomials_Jupyter.ipynb` and `Figures_RcodeForSimulation_Jupyter.ipynb`.

## License

This project is licensed under the terms of the [MIT License](LICENSE).

## Contact

For any questions, issues, or concerns, please contact the author at omersaritac@gmail.com .


