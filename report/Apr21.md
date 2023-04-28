4/21 Report

MCMF
- Worked on MCMF data set in class
- Started out by cleaning column names
- Did some minor additional cleaning: removed a specific row that did not contain a program name (it was the only such instance) and also renamed a program name with a typing discrepancy to align with the broader group that it fits into
- Did some very basic overview and exploration in the excel file just to get a better sense of how the data is formatted and looks in general
- Following the instructions from last week's presentation on the data, we split the data into sessions that were in person and sessions that were over zoom. 
- Two dataframes were created to allow for dedicated analysis on in person and remote sessions
- Further split the in person dataframe into transportation provided and transportation not provided - because there are so few instances where transportation is provided will most likely go back and just make a groupby object to carry out any analysis on the instances where transportation is provided. Goal with looking at transportation provided vs. not provided is to investigate any possible signifiers of inequity among the two groups or identify possible issues that might be able to be alleviated by making changes to the type of programs that are in person vs. remote
- Have some questions to ask the MCMF group: Seeking further clarification on some variable names and some values in certain columns, ask about the possibility of grouping some values together such as science vs. science & math vs. academic support
- Began exploring the cost associated with certain programs and program types to investigate possibilities of inequity
- Grouped the data by cost and program type - created a pivot table with these two values to provide better clarity at how cost differs based on program type
- Possible idea of creating a PowerBI dashboard for some visualization purposes - might be useful especially with geographic data considering that we have access to coordinates which PowerBI can effectively handle. 

Kaggle
- Download data & setup environment
- Start EDA
  - 700+ features... overfitting/multicollinearity might be an issue; see correl matrix?
  - visualize distr. of variables & apply transformations
  - feature engineering... going to be tough with so many predictors
  - check for & handle missing values
