# ML Regression Project with Abalone Dataset

## Description
#### This dataset, relating to marine animals referred to as abalones, presented several features and a target. Thus, it was only natural to intend to predict the target, in this case Age, from the other columns by applying data analysis, visualizations, and machine learning algorithms in conjunction with preprocessing. 

#### As this was a considerably clean and ready dataset, there was no need to apply imputation methods, although this was still applied in the preprocessing pipeline, as was one hot encoding due to the presence of a categorical variable. There were histograms and scatterplots applied, and a few features were extracted using the data in the initial dataset. There was scaling of several numeric features and a preprocessing pipeline addressed numeric and categorical features by scaling and encoding, respectively, and new features were made in this same step. 

#### Several algorithms were applied to the training set and then the predictors would have their hyperparameters be tuned, with these algorithms involving linear regression, ridge regression, lasso regression, and elastic net regression. There was cross-validation and a comparison of root mean square errors, and then the optimal appearing model attained a considerably low generaliation error.

#### There are many machine learning algorithms, and each has their own benefits and downsides. Notably, though, context matters and here the dataframe had over 4100 instances with 8 non-target features and a target column. This would mean that several options could be applied, including algorithms relating to linear regression, a decision tree regressor, and a support vector regressor. However, a voting regressor was applied using the mentioned algorithms, as it is important to note that ensemble methods tend to perform better than individual algorithms when regarding voting regressors and voting classifiers. 

#### Being one of the most robust and popular programming languages, Python was used in this project. It has a very user-friendly syntax, is extremely popular, and this leads to Python having a vast collection of libararies for data analysis, visualizations, data cleaning, and machine learning. The predominant libraries applied in this project were NumPy, pandas, Matplotlib, and Scikit-Learn. NumPy provides application of functions to NumPy arrays, which are present in the dataset. This would be important when scaling features (i.e. using np.sqrt() and np.square()). pandas is essential to anything and everything dataframe related, including the loading of the data into the Jupyter Notebook. Due to pandas, we could use several methods to inspect, visualize, and clean the data. Matplotlib allowed for data visualizations that aided in data analysis. Scikit-Learn allowed the creation of a train set and test set, impuation methods, encoding, scaling, streamlining the pipeline process for cleaning the dataset for machine learning algorithms, and even the machine learning algorithms themselves including linear regression, decision tree regressor, support vector regressor, and voting regressors. Cross-validation, hyperparameter tuning, and scoring metrics were also available in Scikit-Learn.

#### This dataset was almost ready for the application of machine learning algorithms. However, scaling and encoding were still needed, and code was provided to present what would of needed to of been added in order to address missing data for numeric and categorical variables. Thus, the preprocessing streamlining would address any issues with the present dataframe if data were missing. 

#### I hope to implement even more insightful attributes, and to calculate even better feature engineering. While several algorithms were applied, I would like to see or personally apply other algorithms with optimzed hyperparameters, with the goal of having an even lower root mean square error and an even better generalization.

#### My goals are to improve in my skills and experience as an arising data scientist. I aim to practice in the data cleaning and visualization process more often, as well as improve in my abilities to extract features given limited features. Ultimately, I want to excel in the entirety of the machine learning process for the goal of attaining better metrics for predicting values in supervised learning, as well as for discovering insights into datasets. 

## Use
#### Anaconda should be downloaded and with it, Jupyter notebooks should be a familiar topic to any user that wants to use this project. The dataset was downloaded from the UCI Machine Learning Repository, and it is under a Creative Commons Attribution 4.0 International (CC BY 4.0) License. This specific project falls under the MIT License and should be treated accordingly.

## Features
#### Sex - One of three possibilities (M, F, I (infant)) - categorical
#### Length - Longest shell measurement - numeric (continuous)
#### Diameter - perpendicular to length - numeric (continuous)
#### Height - with meat in shell - numeric (continuous)
#### Whole_weight - whole abalone - numeric (continuous)
#### Shucked_weight - weight of meat - numeric (continuous)
#### Viscera_weight - gut weight (after bleeding)	- numeric (continuous)
#### Shell_weight - after being dried	- numeric (continuous)
#### Rings - +1.5 gives the age in years - numeric (integer)

## References
#### Géron, Aurélien. *Hands-on Machine Learning with Scikit-Learn, Keras, and TensorFlow: Concepts, Tools, and Techniques to Build Intelligent Systems*. 3rd ed., O’Reilly Media, 2022.

## Dataset Citation
#### Nash, W., Sellers, T., Talbot, S., Cawthorn, A., & Ford, W. (1994). Abalone [Dataset]. UCI Machine Learning Repository. https://doi.org/10.24432/C55C7W.
