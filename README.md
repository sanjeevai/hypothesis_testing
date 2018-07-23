# Data Analyst Nanodegree

## Practical Statistics

## Project: Analyze A/B Test Results

### Project Details

A/B Tests are very commonly performed by data analysts and data scientists. It is important to get some practice working with the difficulties of these.

This is the fourth project of Data Analyst Nanodegree at Udacity. For this project, we will be working to understand the results of an A/B test run by an e-commerce website (fictional).

Our task is to determine whether they should implement this new page, keep the old page, or perhaps run the experiment longer to make their decision.

### Files

- analyse_ab_test_results_notebook.ipynb:

This is the file where I performed the main work of this project including **data wrangling** and **hypothesis testing**.

- ab_data.csv

Input dataset with five features:

1. user_id

This is the unique identifier for this data set.

2. timestamp

3. group

Can have two values: *control* or *treatment*. *Control* means the old user group who are visting sites since a very long time. They generally see the *old landing page*. *Treatment* means the new user group who see the *new landing page*.

4. landing_page

It also has two values: *old_page* & *new_page*. New page is the one which we think may improve web traffic on website.

5. converted

It can be 0 or 1. 1 means the user converted and 0 means the user did not convert.

- countries.csv

Dataset to include the *countries* column as another independent variable.

- report.html

This is the HTML export of Jupyter Notebook.