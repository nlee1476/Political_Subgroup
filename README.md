# Political Subgroups
This project explores the data distributions of various political subgroups within the United States after the 2018 Midterms  
Author: Nathan Lee
---------------------------------------
### Problem Statement 
---------------------------------------
- To see what political subgroups exist in the United States today, and identify key characteristics about them.
- Fill missing data using the neural network Datawig 
- Use an unsupervised learning algorthim to classify different political subgroups using surveys. 
---------------------------------------

### Data
---------------------------------------
The survey used was the National Election Exit Poll Data from the 2018 Midterms 
  - The survey was conducted by Edison Research with assistance from CNN, NBC, and CBS 
  - The survey took place after November 6th, 2018 
  - It contained existing voters, new voters, and early/absentee voters
  ---------------------------------------

 ### Methodology:
 ---------------------------------------
Since my classification was in mangled, I would not recommend using my methodology. Yet, I'll share with you my theory
  - With this dataset there are four versions of this survey. With around 20 uniform features
    - These features included basic demographic information such as age, race, sex, and political features such as party affilation and political ideology 
    - The theory was that I could use one version of the survey to predict results for the other versions using Datawig 
    - However this did not work, as whenever I added a feature to the uniform features, the accuracy score would decrease for each of the other features 
 ---------------------------------------
#### Failed Methodology Notebooks
  1. Data Cleaning.ipynb
  2. Data labeling.ipynb
  3. Failed Data Imputation.ipynb
    - This notebook containds my attempt to use datawig. 
  4. Unsupervised_Classification_EDA_and_Modeling.ipynb
    - This notebook contains my attempt to use unsupervised algorithims on my categorical data. 
  ---------------------------------------
 #### Relevant Notebooks 
  1. Final Clean.ipynb
  2. Data Visualization and EDA Survey Version 1.ipynb
  3. Data Visualization and EDA Version 2.ipynb
  4. Data Visualization Version 3 .ipynb
  5. Data Visualization Version 4.ipynb
 




