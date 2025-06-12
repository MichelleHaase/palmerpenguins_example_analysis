# An example Analysis of the Palmer Penguins Dataset in Python and R
**credit to**:    
Data were collected and made available by Dr. Kristen Gorman and the Palmer Station, Antarctica Long Term Ecological Research (LTER) Program made available by Allison Horst, Alison Hill, and Kristen Gorman.    
https://github.com/mcnakhaee/palmerpenguins for the python dataset import.   
https://allisonhorst.github.io/palmerpenguins for the R Package   

## Questions
the questions were posed by ChatGPT in 6 difficulty levels and will be answered by me in each a Quarto (R) and a Jupiternotebook (Python) each named after each level.

### Level 1

1. How many penguins are there in the dataset?

2. What species of penguins are included, and how many penguins are there of each species?

3. What are the unique values for the island and sex columns?

4. Are there any missing values in the dataset, and in which columns?

### Level 2

1. What is the average body mass of penguins per species?

2. What is the distribution of bill length across different islands?

3. What is the minimum and maximum flipper length for each species?

4. How many male and female penguins are there per island?

### Level 3

1. Is there a correlation between flipper length and body mass?

2. What are the average measurements (bill length, bill depth, flipper length) grouped by species and sex?

3. Visualize the relationship between bill length and depth using a scatterplot, colored by species.

4. Compare the distributions of flipper length for each species using boxplots.

### Level 4

1. Perform a principal component analysis (PCA) on the numeric features and visualize the first two principal components.

2. Can a simple logistic regression model predict species based on bill length and flipper length?

3. Are there any significant differences in body mass across islands?

4. Create a pairplot of all numerical features colored by species.

### Level 5

1. Build and evaluate a classification model to predict penguin species using all available features.

2. Perform a cluster analysis: how many natural clusters are found, and how do they relate to species?

3. Use statistical testing to determine whether male and female penguins differ significantly in flipper length within each species.

4. Conduct a multivariate analysis of variance (MANOVA) to assess the effect of species and sex on multiple numeric features simultaneously.

### Level 6

1. Build a decision tree classifier to predict penguin species. Visualize the tree.

2. Train and evaluate a random forest model to classify species. Report accuracy, precision, recall, and F1-score.

3. Use cross-validation to compare the performance of logistic regression, decision tree, and k-nearest neighbors classifiers.

4. Build a regression model to predict body mass using flipper length, bill length, and bill depth. Evaluate its performance with RMSE and R².

5. Apply feature scaling and dimensionality reduction (e.g., PCA) before training a classifier. Does it improve performance?
