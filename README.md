# Applied Machine Learning Project 2024
**Website**: [https://elib29.github.io/AML/](https://elib29.github.io/AML/)

## Team Members 
*If you encounter any difficulties or have feedback of any kind, please communicate with us through our institutional emails.*
- [Eliana Perea Barreto](mailto:youremail@example.com)
- [Sheptim Vesil](mailto:team1@example.com)
  
## Project Overview
This project demonstrates the use of various machine learning models, each documented in a separate R Markdown (.Rmd) file. The models included are Simple Linear Regression, Generalized Linear Model to Poisson, Generalized Linear Model to Binomial, Support Vector Machines (SVM), Additive Model, and Neural Network (NN). Additionally, there is an introductory `.Rmd` file that provides an overview of the project and the models used.

## Files Included
- `index.Rmd`: Provides an introduction to the project, outlines the objectives, and gives a brief overview of the machine learning models covered.
- `01-simple-linear.Rmd`: Details the implementation and evaluation of a Linear Regression model.
- `02-linear-to-poisson.Rmd`: Details the implementation and evaluation of a Generalized Linear Model to Poisson.
- `03-linear-to-binomial.Rmd`: Details the implementation and evaluation of aGeneralized Linear Model to Binomial.
- `04-support-vector-machine.Rmd`: Details the implementation and evaluation of a Support Vector Machine model.
- `05-additive-model.Rmd`: Details the implementation and evaluation of a Generalized Additivee Model.
- `06-neural-network.Rmd`: Details the implementation and evaluation of a Neural Network.

## Requirements
To run the R Markdown files, you need the following software and packages installed:
- R (version 4.3.2 or later)
- RStudio
- The following R packages:
  - `nycflights13`
  - `kableExtra`
  - `mgcv`
  - `ggplot2`
  - `caret`
  - `scales`
  - `plotly`
  - `dplyr`
  - `e1071`
  - `rmarkdown`

You can install the necessary packages by running:
```R
install.packages(c("caret", "e1071", "plotly", "rmarkdown", "..."))
```
## How to Run the Project
To run the project you have three options. 
- ### Option 1:
  Visit the [Applied Machine Learning Project Website](https://elib29.github.io/AML/) where all `.Rmd` files are presented in HTML format. 
- ### Option 2:
   Open this project directory in RStudio and select the desired `.Rmd` file. Render the file to a corresponding HTML format by clicking the "Knit" button.
- ### Option 3:
  Clone this project's [Git Repository](https://github.com/EliB29/AML) to your local machine.  Open the directory in RStudio and render each `.Rmd` file by clicking the "Knit" button to generate the corresponding HTML file.

## Project Structure
The project directory is structured as follows:
```
.
├── README.md
├── LICENSE
├── index.Rmd
├── 01-simple-linear.Rmd
├── 02-linear-to-poisson.Rmd
├── 03-linear-to-binomial.Rmd
├── 04-support-vector-machine.Rmd
├── 05-additive-model.Rmd
├── 06-neural-network.Rmd
└── doc/
    └── nn.png
    └── r_squared_4.png
    └── Simple Linear Regression.png
    └── Support Vector Machine.png
```
### Data 

DOC: The doc/ directory contains the images(s) used in the analyses. Ensure that the data files are placed in this directory before running the R Markdown files.

## Additional features
### Lincense
 This project is licensed under the MIT License - see the `LICENSE` file for details.
