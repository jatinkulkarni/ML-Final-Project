# Project-1

The group project will be to use the methods learned in class to perform classification and/or regression and/or clustering on a dataset of your own choosing. You will try a variety of algorithms from class on the data and compare their results. You will want to use the appropriate metrics to measure each model's performance and you will want to use techniques learned in class (such as feature engineering and hyperparameter tuning) to try to improve those metrics.

You will not explicitly be graded on the performance of your models. In other words, if you are only able to get a 60% classification accuracy on your dataset, that is ok - a low accuracy (or F-score) will not affect your grade.

You will be graded on your methodology: What is the process you used, and what things did you do to try to improve the performance of the model?

## Project Dataset Selection Questions:
1. Describe the dataset. (ex: The number of microaneurysms found in a patient's eye and whether or not they have diabetic retinopathy; or Lending Tree loan data, including who defaulted and who paid off their loan.)

	Attendees asked questions within 4 minutes to determine if they'd like a second date.
2. How many records does the dataset have?

	8378 Datapoints
3. How many features does the dataset have? List or describe a few of them.

	123 Features (gender, age, race, field of study, attractiveness, etc)
4. What can you try to predict in this dataset? (ex: We can use the number of microaneurysms measured in the patient's eye to predict whether or not they have diabetic retinopathy; or We can try using the features, including age, income, home ownership status, etc, to predict whether or not someone will default on their loan.)

	Try to predict if the couple decide on a match
5. Is this a labeled dataset, appropriate for a supervised learning classification or regression problem? (In other words, if you are trying to predict whether or not someone has a disease, does your dataset contain whether or not each record has the disease?)

	Yes (match of yes/no)
6. Provide a link to the dataset, if there is one. If you are getting your data from somewhere other than a link, where are you getting it from?

	https://www.openml.org/search?type=data&sort=runs&status=active&id=40536

## Final Deliverable:
You will submit a Jupyter Notebook that walks a reader through your process. The notebook should effectively communicate the "story" of your model: what you did, why you did it that way, and whether or not it worked. 

You will want to start with a brief introduction to the problem (utilize markdown cells for this). What is the machine learning problem you are trying to solve? Why does the problem matter? What could the results of your predictive model be used for? Why would we want to be able to predict the thing you’re trying to predict?

Then describe the dataset that you will use to tackle this problem.

From here, proceed with the machine learning. Perform data cleaning, data exploration, feature engineering, etc. Use the markdown cells to describe each part of the process and the steps you are taking. 

Then move on to the modeling, and use the markdown cells to walk a reader through your  process. 

Finally, display and asses your results. 

