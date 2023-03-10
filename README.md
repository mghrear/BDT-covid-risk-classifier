# Covid risk classifier
Repository for my entry into the ICS635 covid kaggle competition (https://www.kaggle.com/c/covid-19-risk-2022). This was amongst the top 3 classifiers in the competition.

The classifier determines the risk of death given information about the patient.


## process_data.ipynb
A notebook for cleaning and processing the provided data. The notebook also introduces new data (long and lat coordinates) that helps the classifier.

## BDT_classifier.ipynb

A notebook that optimizes, trains, and tests A boosted decision tree classifier and creates a submission file for the competition.
