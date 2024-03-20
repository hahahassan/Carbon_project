#Questions:

## 1. The effect of Waste bag size and Waste bag count weekly on Carbon Emisson? (check interaction) -- model 1(create a new x)
    a. scatter plot
    b. lm model, F test
    c. interpret each coefficient
    d. use waste bag size and Waste bag count weekly to predict people's carbon emission (use test data)

## 2. the effect of recycling on Carbon Emission? -- model 2 = model 1 + recycling (create a category )
    a. we add this variable to model in question 1, use anova test to check if it is significant enough?
    b. then we use new model to predict, and compare the prediction results with model1 and model2
    
## 3. Model selection based on model 2, -- model final
    a. MASS::stepAIC(model2,scope= [upper,lower],direction=both)
    b. partial residual analysis on some variable, then do transformation
    c. check outliners and influential points
    4. check multicollinearity, cor, VIF() > 10
    5. use test data to do prediction and check the prediction accuracy  
    