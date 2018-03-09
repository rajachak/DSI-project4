## PREDICTING WEST NILE VIRUS IN THE CITY OF CHICAGO

**Team members: Raj Chakrabarty, Sian Lewis, Zaheer Rangwala and Joshua Sung**

Our group project is based on the Kaggle West Nile Virus challenge. We were challenged to:
-create a model to predict the presence of the West Nile Virus in the city of Chicago, and
-create a cost-benefit analysis regarding prevention of West Nile Viurs in Chicago.

**PROBLEM STATEMENT & GUIDING QUESTIONS**
To prevent an outbreak of West Nile Virus, our guiding questions include:
-When and where will West Nile Virus occur in Chicago?
-How do we reduce the incidences of WNV?
-What are the costs and benefits of WNV prevention?
-How do we best use preventative methods like pesticide spraying?


**OUR METHOD**
We set out to do four things: 
  a) create a model or series of models that predict the presence of WNV (Raj and Zaheer)
  
  b) conduct a cost-benefit analysis of West Nile prevention (Sian),
  
  c) describe the data that we have (Joshua), and,
  
  3) properly allocate our team, time, and resources to accomplish our goals (Sian). Find our project management document here: https://docs.google.com/spreadsheets/d/14TeazAnTMHAXWEu64KRec7Q9ASqSNv_p1B5oPRuYuQ4/edit?usp=sharing


**OUR FINDINGS** (see our presentation here https://docs.google.com/presentation/d/1cFFLw9rq9zW0AIquXChgikRqONU4G6UBGT8EeFmeynM/edit?usp=sharing)
To predict West Nile, we used an Adaptive Boosting machine learning algorithm (Adaboost). The ROC-AUC score measures the accuracy of our model. The lowest score of 50% and the highest score of 100%. Our model achieved a Kaggle ROC AUC score of 0.728%. This was the highest in our class, and we are proud of our efforts. Here are more findings:
-The most “predictive” feature is the day of the year
-The weather for a particular time period is best used for predicting presence of WNV
-It is economically prudent to spray the city to prevent WNV (find our detailed Cost-Benefit Analysis here: https://docs.google.com/presentation/d/1cFFLw9rq9zW0AIquXChgikRqONU4G6UBGT8EeFmeynM/edit?usp=sharing

**Files:**

  -Project 4 - EDA.ipynb:          Jupyter notebook with inital exploratory data analysis 
  
  -Project 4 model builder.ipynb:  Jupyter notebook with predictive modeling
  
  -test_csv.csv:                   Model output, submitted to Kaggle for final score
  
  -West Nile Virus.pdf:            Slides from final presentation
  
  -spray.csv:                      Data file downloaded from Kaggle
  
  -test.csv:                       Data file downloaded from Kaggle 
  
  -train.csv:                      Data file downloaded from Kaggle
  
  -weather.csv:                    Data file downloaded from Kaggle
  
