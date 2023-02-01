# Modeling EEG signals using polynomial regression

---
![GitHub](https://img.shields.io/github/license/maladeep/Modeling-EEG-signals-using-polynomial-regression-in-R) 
![GitHub repo size](https://img.shields.io/github/repo-size/maladeep/Modeling-EEG-signals-using-polynomial-regression-in-R)



---
## Introduction to EEG signals?

<a href='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fstatic1.squarespace.com%2Fstatic%2F56530999e4b0991ab31b67b1%2Ft%2F57485e378a65e22d87e5a155%2F1464360526430%2F&f=1&nofb=1&ipt=43a80badae603840e97e1f550187a8e3f13333fb7a3db115ff3c0c356233a826&ipo=images'><img src='https://external-content.duckduckgo.com/iu/?u=https%3A%2F%2Fstatic1.squarespace.com%2Fstatic%2F56530999e4b0991ab31b67b1%2Ft%2F57485e378a65e22d87e5a155%2F1464360526430%2F&f=1&nofb=1&ipt=43a80badae603840e97e1f550187a8e3f13333fb7a3db115ff3c0c356233a826&ipo=images' align="right" height="12.5" /></a>

EEG stands for Electroencephalogram which are electrical signals that measured the electrical activity of the brain (St et al., 2016). 
To get the EEG result, electrodes consisting of small metal discs with thin wires are pasted onto scalp. The electrodes detect tiny electrical charges that result from the activity of your brain cells and thus obtained charges are amplified and appear as a graph on a computer screen, or as a recording that may be printed out on paper. 
The main purpose of EEG is to detect potential problems (encephalitis, hemorrhage, epilepsy,Parkinson's disease and other) with brain cell communication by painless method (Healthline, 2012).

Here in the data set, we have four input EEG signals, one output signals and time for each signals.


## After understanding and working with this notebook, you will be able to do:

1. Visualize the trend and patterns in the EEG signals over time.
2. Assess the fit of the polynomial regression model to the EEG signals and estimate the parameters of the model.
3. Use a simulation-based approach to estimate the posterior distribution of the model parameters, allowing for uncertainty in the model and data..
ion-based approach to estimate the posterior distribution of the model parameters, allowing for uncertainty in the model and data.

## Requirements

| Attribute | Value |
| --- | --- |
| Platform | aarch64-apple-darwin20 |
| Arch | aarch64 |
| OS | darwin20 |
| System | aarch64, darwin20 |
| Major | 4 |
| Minor | 2.2 |
| Year | 2022 |
| Month | 10 |
| Day | 31 |
| SVN Rev | 83211 |
| Language | R |
| Version String | R version 4.2.2 (2022-10-31) |
| Nickname | Innocent and Trusting |


## Libraries Used

The following libraries are used in this project:

- `ggplot2` - implementation of the grammar of graphics for complex visualizations
- `GGally` - creates a matrix of scatter plots, with histograms or density plots
- `tidyverse` - data manipulation, exploration, and visualization
- `tidymodels` - splits the data into training and testing
- `moments` - calculates and plots descriptive statistics
- `dplyr` - a data manipulation toolkit for working with structured data
- `ggExtra` - adds additional functionality to ggplot2
- `readr` - a fast and friendly library for file reading
- `ggpubr` - customizes ggplot2 based publication ready plots



## Contributing

Contributions are what make the open source community such an amazing place to learn, inspire, and create. Any contributions you make are greatly appreciated.

If you have a suggestion that would make this better, please fork the repo and create a pull request.


## License

Distributed under the MIT License. See `LICENSE.txt` for more information.




