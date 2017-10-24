Springboard 1st Capstone Project Proposal
RentHop.com Rental Listing Popularity Prediction
By Merrill Heddy

Problem Trying To Solve:
Predict how popular or how much interest a new apartment rental listing receives on the web site RentHop.com.

Client Identification, and How It Benefits the Client:
RentHop.com, and owners and agents that list with RentHop are the client.  RentHop cares about this problem because it will help RentHop better handle fraud control, identify potential listing quality issues, and allow owners and agents to better understand renters’ needs and preferences.

Data Source:
The data comes from RentHop.com, and is in a Kaggle.com data repository.   The data for predicting how popular an apartment rental listing is consists of the listing content like text description, photos, number of bedrooms, price, listing’s creation date and other features.  These apartments are located in New York City.  The target variable (interest level) is defined as a three level category variable of ‘high’, ‘medium’, and ‘low’ that is determined while the listing is live on the site.
Classification label:
interest_level: this is the target variable. It has 3 categories: 'high', 'medium', 'low'

In more detail the feature variables from RentHop.com are:
bathrooms: number of bathrooms
bedrooms: number of bathrooms
building_id
created
description
display_address
features: a list of features about this apartment
latitude
listing_id
longitude	
manager_id
photos: a list of photo links. You are welcome to download the pictures yourselves from renthop's site, but they are the same as imgs.zip. 
price: in USD
street_address

An addition exogenous feature variable, subway entrance distance, will be derived from RentHop.com data, and exogenous subway entrance longitude, and latitude data.   

Proposed Approach:
The data is arranged to be a multiclass (3 level) classification problem.  Possibly, One-Vs-All Classification or All-Vs-All Classification that uses a binary classifier such as a SVM or RLSC as its basis will be used to perform the classification.   

Deliverables:
Code
Deck of Slides
Final Brief Report







