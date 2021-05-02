# Machine Learning Final Project
### Zach Morrissey
### Rees LaBree

The goal of this project is to predict new COVID case numbers per day for each county in Colorado. We will predict using several different models and features to tune and find 
the best hyperparameters, documenting progress along the way.

We split this project into two sections. These sections are documented in [`project-random-forest-adaboost.ipynb`](https://github.com/zmorrisseyj/CSCI4622/blob/main/project-random-forest-adaboost.ipynb) and [`project-k-means.ipynb`](https://github.com/zmorrisseyj/CSCI4622/blob/main/project-k-means.ipynb).

## K-Means
This section is a K means algorithm using pandas and numpy. We've ran it for several values of K and included accuracy and elbow plots. Further hyperparameter tuning required but the methods are effective. Details and results are documented and discussed in the K means specific notebook.

## Random Forest and Adaboost
Process documentation for the Random Forest and Adaboost methods exists in the notebook. For these two methods we used SciKitLearn's built in `RandomForestClassifier` and `AdaBoostClassifier` functions. We used nested for loops to calculate and store the accuracies associated with each hyperparameter. From this we were able to determine the optimal hyperparameter values and use those to predict and qualify against April's infection rate data.
