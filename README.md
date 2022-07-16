# Customer Segmentation

## Topic
Customer Segmentation 

## Why Customer Segmentation
Customer segmentation is a vital source of a company's overall business success. Majority businesses are customer centric. They would
like to succeed by reaching their target audience and marketing the right product to the targeted age group. Customer segmentation
data analysis will give us the opportunity to experience the marketing strategies and enhance the understanding of product launch 
management.

## Description of the source data
The source data was obtained from Kaggle where it was originally provided by Dr. Omar Romero-Hernandez, an economics researcher at UC Berkeley. The data describes the customers' attributes (i.e. age, education, marital status, number of kids), amount spent on products the business carries, history of customer orders/purchases, and customers' interactions with customer service (complaints and response).  

## Problem Question
Carry out a customer personality analysis to create well defined customer segments that help retail grocery businesses to understand different buying customer trends and behaviours.

## Hypothesis & Expected Results
Areas of interest include examing the relationship between:
- family size and purchasing habits  
- education, income and healthier food choices  
- 
Proposed findings and a hypothesis of results (i.e. business problem contextualized with data driven results)  
Analysis Ideas/Data Analysis Notes:
How the growth of the size of the family increases their buying habits.
Education and healthier products


## Github repo and everyone has merged with the main branch at least once  
1. To clone the new repo  
- git clone url -> Replace url with the project url  
2. Creating a new Branch and pushing the code in the branch.  
- git branch branchname  -> branchname is the branch to be created.
- git branch -> To check the available branches. * indicates the branch we are currently in.  
- git checkout branchname -> Switch to the preferred branchName.  
- git add .   -> Add all the files  
- git commit -m "Add the comments" -> Commit the code with appropriate comments.  
- git push -u origin branchname -> Replace branch name with the actual branch name.  
- Check the status before merging into main, if required use pull request and then merge.<br>


## Technology/Tools Overview
![DataPipeline](/Pipeline.PNG) 

<br> https://drive.google.com/file/d/1APNQWqY7bScOVwQ1omL61U-CXKvQPcZ5/view?usp=sharing  <br>

### Data Cleaning and Analysis
The Pandas library in Jupyter notebook is used to clean the data and perform exploratory analysis. 
- Load the csv in a dataframe.
- Check for duplicates.
- Check for NAN values.
- Eliminate Redundant data.
- Convert any column data type according to the need of the end result.
- Divide the data frame into further different dataframe as per the requirement, these data frames  will represent as individual tables in the database.
- Data is ready for initial storage.
- Any changes made or files added will be placed in the github final project folder.
<br>


### Database Storage
PostgreSQL with AWS cloud is used for the database requirement.
Data tables have been created to organize data and its functionality.
Customer segmentation ERD has been created to further elaborate the data and its attributes.
Project architecture has been implemented using google collab (ConnectDB File) . Spark session has been integrated  with machine learning provisional database.

#### Database Mock Up (Preferably a ERD - Entity Relationship Diagram) 
![Customer segmentation ERD](https://user-images.githubusercontent.com/96637236/179373640-56fca98c-a7c3-44d7-b189-596236bc2d3e.png)

Data Integration via AWS and Google collab-Jupyter notebook

![Connect DB ](https://user-images.githubusercontent.com/96637236/179373879-83e3a074-f349-4859-b4a5-ad1e0071eb2e.png)


### Machine Learning
SciKitLearn is the ML library that will be used to create a classifier. We will use agglomerative clustering of unsupervised machine learning which are "K-means clustering" and "hierarchical clustering" in this project.
Our training and testing will be split up into a 70:30 ratio. 
1. Retrieve the data from the storage using the SQL functions.
2. Join or merge the database if required and store it in a different dataframe.
3. Prepare the data for machine learning. Since we will use both the K-Means algorithm and Hierarchical clustering, each step below will be repeated for both the type of models with minimal or any changes required.

- Prepare the training data.
- Prepare the model.
- Fit the model.
- Measure the accuracy.
- Plot the graph.
- Final observation and analysis. <br>
#### ML Mockup
<br> ![MLMockUp](/MLMockUp.PNG)<br>


### Dashboard
Tableau will be used for visualization of the results.
<br>
