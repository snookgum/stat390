# Progress Report: 5/8-5/12
## Ashley Witarsa
### Kaggle
#### Progress/Accomplishments: 
- EDA
	- Dropped columns with more than 5% null vals 
	- Imputed remaining null columns using KNeighbors 
	- Removed columns with > 0.9 correlation with other predictors 
	- Ran PCA (0.95 variance kept) for feature selection
- Models
	- Tuned XGBoost 
	- Lasso 
	- Ensemble models 
#### Problems/Challenges
- My RMSE becomes a little higher when I do feature selection with PCA vs just using top 30 predictors, might need to change threshold
#### Plan/Next Steps:
- Figure out why PCA yields higher RMSE by 5/17
- Ensemble more models by 5/19
- Use neural networks after tuning is covered in Stat 362