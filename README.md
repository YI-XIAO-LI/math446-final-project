# math446-final-project
Final Project on Ethereum and NVVH (Net Value vs. Hold) for MATH446

### Summary
We have defined a new metrics NVVH for assessing impermanent loss by taking transaction fee gained into account. </br>

### Machine Learning Model on NVVH
We also built a random forest classifition model based on factors highly correlated with NVVH (time in the pool, eth price at burn and mint time). </br>
The model predict a 6-scale NVVH with max-depth of 2, and it uses 75% of the data as train set and 25% as test set. </br>
The model has an r2 of 0.69. False positive and false negative rates are below 0.08 after giving one-scale false tolerance. </br>

### Versions
The Extended version of code contains all work (on impermanent loss, NVVH, and a few other topis) from data wrangling to machine learning model building. </br>
The Condensed version contains only the most fruitful analyses on NVVH. </br>
