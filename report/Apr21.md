# 4/21 Report
## Team Senioritis: Seonuk Kim, Brock Underberg, Ashley Witarsa

### MCMF
#### Progress/Accomplishments:
- Worked on MCMF data set in class
- Started out by cleaning column names
- Did some minor additional cleaning: removed a specific row that did not contain a program name (it was the only such instance) and also renamed a program name with a typing discrepancy to align with the broader group that it fits into
- Did some very basic overview and exploration in the excel file just to get a better sense of how the data is formatted and looks in general
- Following the instructions from last week's presentation on the data, we split the data into sessions that were in person and sessions that were over zoom. 
- Two dataframes were created to allow for dedicated analysis on in person and remote sessions
- Further split the in person dataframe into transportation provided and transportation not provided - because there are so few instances where transportation is provided will most likely go back and just make a groupby object to carry out any analysis on the instances where transportation is provided. Goal with looking at transportation provided vs. not provided is to investigate any possible signifiers of inequity among the two groups or identify possible issues that might be able to be alleviated by making changes to the type of programs that are in person vs. remote
- Began exploring the cost associated with certain programs and program types to investigate possibilities of inequity
- Grouped the data by cost and program type - created a pivot table with these two values to provide better clarity at how cost differs based on program type
#### Problems/Challenges:
- Have some questions to ask the MCMF group: Seeking further clarification on some variable names and some values in certain columns, ask about the possibility of grouping some values together such as science vs. science & math vs. academic support
#### Plan/Next Steps:
- Possible idea of creating a PowerBI dashboard for some visualization purposes - might be useful especially with geographic data considering that we have access to coordinates which PowerBI can effectively handle. 

### Kaggle
#### Progress/Accomplishments:
-	Download data & setup environment
-	Started brainstorming for EDA
#### Problems/Challenges:
-	Not sure how to shrink down predictors
-	Not sure how to approach feature engineering since I don’t know what predictors mean
#### Plan/Next Steps:
-	Create correlation matrix to shrink down predictors
-	Visualize distr. of variables & consider transformations
-	Handle missing values
-	Start modeling

