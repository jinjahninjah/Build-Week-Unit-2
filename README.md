# Build-Week-Unit-2

## Looking for Employees?
A Classification model to predict whether or not a trainee will seek employment with the company or search for a job else where.

### Introduction
The dataset I’m using is based off a Data Science company’s course data obtained through a series of trainings the company offers. Once someone finishes these training courses, the company wants to know if they will want to apply for an open position, or if the trainee wants to look for a job elsewhere. The data contains information such as demographic, education, location, experience, and the like. **

Hiring talent can be a costly endeavor given all the different aspects that goes into it: labor, contracts, vendors, recruiting firms or website subscriptions, all these can pile up to a nice chunk of change. According to Glassdoor.com, the average cost of hiring an employee is $4,000! If we can help identify potential candidates, we have the potential of saving quite a large sum of money.

This dataset was pretty easy to use; the target was clearly defined as “target”. I started with an accuracy score, then moved on to a classification report to see our precision and recall scores. I plotted some permutation importances and ROC curves as well. There wasn’t really any leakage in the data, although I did have to under-sample the majority class to balance out my class distribution.

This model should be useful in predicting which trainees want to apply for a job at the company; thereby, allowing resources to flow more concisely to avoid costly labor waste.
