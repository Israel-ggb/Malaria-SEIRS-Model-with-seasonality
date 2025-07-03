# SEIRS Malaria Model with Seasonality

This project presents a compartmental SEIRS model to simulate malaria transmission dynamics, incorporating **seasonal variation** in transmission rates. It is implemented using **R** and visualized with **ggplot2**.

## 🔍 Objectives

- Simulate malaria transmission with a SEIRS model
- Incorporate seasonality to reflect real-world transmission fluctuations and mosquitoes impact
- Generate plots and dynamic visualizations of model outputs

## 📁 Project Structure

- `SEIRS malaria modelling..Rmd`: Main R Markdown file containing code, equations, and plots
- `SEIRS-malaria-modelling..pdf`: Rendered PDF output of the analysis
- `plot_seirs.png`: Example plot of the model output
- `README.md`: Project documentation
- `.gitignore`: Standard ignore rules for R projects
- `.Rproj`: RStudio project file

## 📦 Tools and Libraries Used

```r
library(deSolve)    # for solving differential equations
library(ggplot2)    # for plotting
library(tidyverse)  # for data manipulation
