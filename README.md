># Data Science Blog Post ![Static Badge](https://img.shields.io/badge/version-1.0.0-green)

## Where is it best to be a developer?

### Using the 2025 Stack Overflow Developer Survey data this <code>notebook</code> presents the method followed to analyse the survey results to attempt to gain insights into where best it might be to be a developer! Both in terms of geographic location and industry, through answering the following questions,  

1. Where are respondents from? Both interms of Country and Industry.  
2. Is there a link between Compensation (Salary) and Job Satisfaction? What might that look like?
3. Which countries have the highest paid and most satisfied developers?   
4. Which Industry has the highest paid and most satisfied developers?

#### Additionally, we seek to understand if the use of AI in development has any effect on compensation and job satisfaction.   

#### Lastly, what should a developer be earning? I make an attempt at predicting developer salaries based on a subset of the survey features


## Created
- Project created: November 2025
- Readme updated: 11 November 2025

## Dependencies
You will need <code>python</code> along with the 'standard' data science related libraries we all know and love to run the <code>notebook</code> as well as some you may not have yet used

Libraries we know

- numpy
- pandas
- matplotlib
- seaborn
- scikit learn (sklearn)

And if you haven't tried it yet,

- [XGBoost](https://xgboost.readthedocs.io/en/stable/install.html)


### Useful Resources
- using Scikit Learn: [Scikit Learn](https://scikit-learn.org/stable/)

## Data Required
The 2025 [Stack Overflow Annual Developer Survey](https://survey.stackoverflow.co/) results data are used for the analysis and predictions, namely the 'survey_results_public.csv' file



## Repository Files

- Jupyter notebook: dsnd_ds blog post_draft_v1.ipynb -- this file contains the documented python code used to perform the analysis answering the questions where is it best to be a developer as well as the developer salary predictions. 

## Analysis and Prediction Results

The analysis of the developer survey results in terms of the questions we asked showed the following,

- ~42% of respondents were from 4 countries, the largest proportion coming from the USA at 20.4%
- From an Industry persepctive the largest proportion of respondents came from Software Development at 48.4%

- From about $250k and up there appears to be a directly proportional link between compensation and job satisfaction. Below $200k we see many very satisfied and unsatisfied developers!

- On the question of compensation and job satisfaction by country, we look at the Top20 countries by volume of responses. The US, Switzerland and Australia stand-out as higher earners with mostly satisfied employees. While colleges in the UK appear to be fairly well compensated but are apparently not too happy! This in contrast to Brazil where pay levels are comparitively low but goodness, most seem to be smiling none the less, with second highest job satisfaction rating next to Denmark.

- Then we look at which Industry may be the best place to be. Ignoring possible sample bias with regards Software Development industry catagory... its interesting to note that we see very distinct cases where pay does not equal great satisfaction. For example 'Higher Education' - apparently the lowest paid industry, ~1.7 standard deviations below mean, but apparetnly more satisfying than Fintech, a new, exciting and better paying industry by the look of it. Overall 'Computer Systems Design and Services' stands out as highest paying, most satisfiying industry.

- We find that there appears ot be no conclusive link between the use of AI assistance in development and compensation or job satisfaction.

- Lastly we attempt to predict what a developers salary should be based on certain features of the dataset and a Linear Regression model. Initial results with un-tuned regressor models are very innacurate. However with some basic data pre-processing and hyper-parameter tuning we are able to improve to an R2 score of ~0.5 and an RMSE $50k. These are not great prediction results but are a vast improvement over the initial attempts.

## Credits
A huge thanks to the Udacity and StackOverflow teams without whom this project would not have been possible.

## License
This software is open and free to use as you wish.

We ❤️ [Udacity!](https://udacity.com)

