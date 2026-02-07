# Ames Housing Data Analysis

This repository contains an analysis of the Ames Housing Dataset --- a dataset widely used in statistics and machine learning --- implemented in **R**.

### Contents
- A compilation of home search criteria and recommendations from real estate agents  
- Exploratory Data Analysis (EDA) of the dataset
- Missing data handling
- New feature creation, variable transformations
- Linear regression
- AIC/BIC evaluation, predictor selection
- Evaluation on the test set, model tuning
- Predictions on the validation set  

The rendered HTML report is called `ames_data_analysis.html` and is located at the top level of the repository.

You can view it as follows:

1. Click on `ames_data_analysis.html` to view the file

2. Copy the contents of the file and paste them in a file with `.html` extension on your computer

- Open your HTML file in a web browser


### Project Files

The project files are available in the `src/` directory and include:

| File                   | Contents                                   |
|-----------------------|---------------------------------------------|
| `ames_train.Rdata`       | Training dataset                         |
| `ames_test.Rdata`        | Test dataset                             |
| `ames_validation.Rdata`  | Validation dataset                       |
| `codebook.txt`           | Dataset codebook (variable descriptions) |
| `ames_data_analysis.Rmd` | RStudio project (R code and markdown)    |

### Running the Project

To reproduce the analysis yourself:
1. Open `src/ames_data_analysis.Rmd` in **RStudio**.
2. Run the code or click the **Knit** button to regenerate the HTML report.

### License
This project is dedicated to the public domain under [CC0 1.0 Universal].  
See `LICENSE.txt` for details.
