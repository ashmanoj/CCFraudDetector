# Process

Our process was fairly simple, and for all three of our models, we used the same process as outlined below:

Importing necessary models and installing if they are not already
Reading the csv file using pandas and converting to data frame
    Printing the first 10 rows and separating the features and label
Importing functions from installed libraries for resampling purposes
Split the dataset into training and testing groups, and printing the counts to ensure correct splitting
Resampling - The following steps are repeated for each sampling method:
    Fitting the sampler and setting a random state so its reproducible
    Assigning new, resampled data to new data frames and printing to ensure balanced dataset
Importing Classifier
Creating functions for:
    Confidence score
    Model metrics
    Histogram plotting
    Confusion matrix plotting
Importing SHAP
    Creating function to plot SHAP values
Importing LIME
    Creating function to plot LIME values
 Training/Testing - The following steps were done for each sampling method
    Creating a new classifier for the sampling method 
    Fitting the classifier
    Make a prediction, save it to a variable
    Obtain Confidence scores and accuracy score
    Print model metrics from the function
    Plot confidence score intervals
    Plot confusion matrices
    Fit the Shap explainer, for 10% of the data and plot the values
    Plot an absolute value version of the graph
    Plot 2 LIMEs, one for a fraud and one for a on-fraud case
Saving the best model
    Saved the best model using pickle
