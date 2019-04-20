# Assignment4MLproject
This is the 4th assignment for PBA MLAI spring2019soft

# What it is
This is a repo consisting solely of a markdown file in response to [machine learning assignment4](https://github.com/datsoftlyngby/soft2019spring-ai/tree/master/project4)<br>
<br>
## Part 1
<br>
<b>Hand-in:</b><br>
  - A precisely formulated question using no more than 20 words<br>
  - At least 50 words of text that motivates why the business question is interesting<br>
  - At least 40 words of text that describes which concepts from class you will have to use to answer the question.<br>
<br>  
<br>
1.a)Be able to predict when and where crime will happen in Boston (year :2018)<br>
<br>
1.b) It would be interesting to be able to predict where crime will happen in order to be able to take preventive measures, this is will help reduce human suffering (being victim of a crime) and it will also help to target the police ressources and thereby reducing costs to the city. (Is it possible to enter last years crime stats and be able to predict this years crime stats)<br>
<br>
1.c) We plan on using the following concepts: predictive analysis using trained models. We will also be using correlation analysis to find the most (un)import features, we will be using scoring mechanisms to measure the accuracy of the predictions we make<br>
<br>
<br>
## Part 2
<b>Hand-in:</b><br>
  - A link to the data resource online along with at least 20 words of text describing the data source<br>
      - Include a description of the data features and the size of the data<br>
      - If you do not have enough data points, include the points from the section on 'If you do not have enough data points'<br>
  - An automated method to download the data in a .py file<br>
      - You do not have to do any preprocessing (yet)<br>
<br>
<br>
2.a) [Here is a link to our datasource](https://www.kaggle.com/ankkur13/boston-crime-data)<br>

This dataset has 2,60,760 rows and 17 columns.<br>
INCIDENT_NUMBER: (this is a unique identifier)<br>
OFFENSE_CODE: (Self explanatory) <br>
OFFENSE_CODE_GROUP: (this is a categorization of the offense) <br>
OFFENSE_DESCRIPTION: (Self explanatory)<br>
DISTRICT: (area(id) of city)<br>
REPORTING_AREA: (area(id) of city)<br>
SHOOTING: (we think this is whether or not the police have fired their weapon during a crime)<br>
OCCURRED_ON_DATE: (Self explanatory)<br>
YEAR: (Self explanatory) <br>
MONTH:(Self explanatory) <br>
DAY_OF_WEEK:(Self explanatory)<br> 
HOUR:(Self explanatory) <br>
UCR_PART: ([uniform-crime-report](https://en.wikipedia.org/wiki/Uniform_Crime_Reports) national category of the type of crime)<br>
STREET:(Self explanatory) <br>
LATITUDE:(Self explanatory) <br>
LONGITUDE:(Self explanatory) <br>
LOCATION:(LAT and LONG in one field)<br>
<br>
<br>

2.b we plan on using Pandas \*.read_csv(path to data) to download our data into the jupyter notebook<br>
<br>
<br>
## Part 3
<b>Hand-in:</b><br>
- At least 40 words describing how the data can help you answer your business question<br>
- At least 3 model types that can help you answer your business question<br>
- A list of features that you would like to include to answer your business question. For each feature you need to describe:<br>
- Feature name (what is it?)<br>
- What it explains (why is it relevant?)<br>


3.a)  We plan on dividing the data into 2 parts: year 2017 and 2018. We will then train our models using the crime data from year 2017 and then use the crime data from 2018 to verify whether or not our model is useful (accurate), if it is we should be able to input the crime data from 2018 to predict coming crimes for 2019 and so on. (*As an extra exercise it would be fun to examine what events occured in boston at which place and what time, and check correlation between these and crimes*)<br> 
<br>
3.b) we plan on using the following models: Neural network. support vector machine. Linear regression, to make our predictions, we might have to clean up the feature set as well, in this case we will use PCA.<br>
<br>
3.c) We need features like location, type of crime(category), date and time, all of these are relevant to predict where to target resources/efforts.<br>



