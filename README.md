# AnalyzeDataSet Part 2

This dataset comprises of multiple signals from isolated pure cells, mixed cells(type 1) and mixed cells (type2). The goal of this task is to evaluate both data sets and infer relationships between the two datasets i.e. Use the data from the isolated pure cells can you predict how many of each cell type are present in the mixed cell population.

## Tasks
### Data Preparation and cleaning
* Look at the known cells measurement and suggest a data cleaning procedure or approach to create a training data set (i.e.Cell_A, Cell_B and Cell_C)
* This can include removing duplicates, correcting errors, dealing with missing values, normalization, data types conversions etc.
* Split this data set into training and evaluation data sets (i.e. split data from Cell_A, Cell_B and Cell_C)

### Create a training model
* Identify or propose a method to create the training model set i.e. What methods would you use and why? 
* Next implement it. Yes, go ahead and create a training model 
* Evaluate your model - what metrics would you use to quantitatively measure the performance of your model

### Predict
* Use these training models to predict the total counts of the individual cell types in mixed cells i.e Mixed_Cells_Type_1 and Mixed_Cells_Type_2

## Dataset
A link to the dataset will be sent to you in the email. The datasets contains a few thousand data points for each cells.
Each CSV is a single cell

The datasets comprises of the following folders:
### Measurement data from pure Isolated known cells
* Cell_A (Total Cells: 1206)
* Cell_B (Total Cells: 1543)
* Cell_C (Total Cells: 1379)

### Mixed cells
* Mixed_Cells_Type_1
* Mixed_Cells_Type_2

All the folders contain zipped datasets denoted as dV.zip and dVV.zip and both contain data about each cells. Cell are numerically marked in file names.

Use the code in combine_data.py as a starting point to combine single cell data

## Submission
* Create a branch with your submission
* Create a pull request
* Submit a 2 page summary by email regarding your choices and summary of results by email. 
 * Include any challenges or problems you faced along with suggested solutions
 * Go over you approach and reason for choices of method
 * Summarize the data and results
 * Do you see any issues with the data itself. If so, how would you improve or make changes. Alternatively, how would you (or how did you) clean the data?


## Do's
* Include visualizations and share insights
* Reach out to us with questions
* Reach out to the team if you have issues accessing the data
* Use Python - WE LOVE PYTHON, R works as well
* If you exceed the timelines, do propose and describe in your summary your approach

## Do not 
* Spend more than 4 hrs working on this. (Do not include time to download data into this timeline. The dataset is large and depending on your computer and network, download speeds could vary)
* Spend more that 30 mins documenting your work i.e code and summary

## What we are looking for:
* You data analysis/cleaning/wrangling skills
* Ability to use statistics or other methods to understand data trends behaviour
* Ability to create a models to enable classification
* Can you solve the problem efficiently to propose solution to better understanding the data.


