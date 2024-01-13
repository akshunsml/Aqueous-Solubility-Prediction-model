Aqueous Solubility prediction model using machine learning algorithms, ie. linear regression and random forest. This could be important in the fact that 
its crucial for biologists and chemists in determining whether a molecule is soluble in water and solvents, and whether that molecule would be a good drug candidate or not.

I had this data, collection of chemical descriptors and corresponding solubility values represented by this(logS) served as my target variable y and the other chemical descriptors constituted the features(denoted with X)
then I split the dataset into training and testing sets, this ensures that our model learns from a subset of the data and is then evaluated on a seperate, unseen portion, to check its predictive capabilities.

then I am using Linear regression and Random forest, to train the model,  
The fit method computes the coefficients (slope and intercept) of the linear regression model that best fits the given training data. 
After this line is executed, the lr, rf object contains the trained linear regression and random forest model.
