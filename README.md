# Datanest

This project is part of the submission for the Datanest Competition hosted by the Ramjas College,University of Delhi on Dare2Compete platform.

As part of this competition we were provided a dataset and were asked to clean the dataset and visualize it.
The data provided consisted of almost 1000 entries and with various features.Data was largely focused on individuals looking for job and their backgrounds such as their education level,experience etc.

## Objective

This dataset has been designed to understand the factors that lead a person leave his current job, and the goal of this task is building model(s) that uses the current details to predict the probability of a candidate looking for a new job or will work for the company.

The dataset provided had several missing points and so we needed to first clean it and then visualize it.
For missing data points we either replaced them with the mode value or with all the classes based on the current probability distribution of the dataset.
There after we used python libraries for visualizing the dataset and to draw inferences from it.

Libraries used:

```

Pandas
Numpy
Matplotlib
Seaborn
Scipy
Sklearn
XGBoost

```

### Some Visualizations are attached here as follows:
Categorical Data features
![alt text](images/plot1.PNG)
Categorical Data features
![alt text](images/plot2.PNG)
Numerical Data Features
![alt text](images/plot4.PNG)
Data Correlation
![alt text](images/plot3.PNG)

### Relation between Target variable and other features
![alt text](images/plot5.PNG)

![alt text](images/plot6.PNG)

![alt text](images/plot7.PNG)

![alt text](images/plot8.PNG)

![alt text](images/plot9.PNG)

![alt text](images/plot10.PNG)

![alt text](images/plot11.PNG)

## Inferences

```

From the above figures, we can say that the data contains much more instances of Male candidates, graduate candidates, employees working in small companies and private companies, candidates with major discipline being STEM and most of them did not enroll in any university.

Most of the people were associated with either Private or Pubic jobs with the Private job people being volatile in changing the jobs and Public Sector being the most stable and the people in STEM and humanities were supposedly taking jobs for and year or two and then based on their experience would either shift from the job or retain it.

Most of the cities had a high development rating as well and the training hours were also following the normal distribution with the mean around 30 to 40 hours.

Enrollment in university was a useful indicator as people who were never enrolled had a difficult time in finding jobs as compared to fully enrolled and partially enrolled.

Data also pointed to the fact that most of the people were graduates and experienced i.e. if a person finds a stable job then most likely he settles down with it.

```

For data fitting we had used two algorithms one belonging to the Decision Tree family (XGBoost) and other being Logistic Rgression.
