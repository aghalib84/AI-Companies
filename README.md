# AI-Companies
An analysis of AI companies around the world for determining which factors are ideal for entry into the market.

Method and Procedures

***Here I will outline the procedures I took in finding, preparing, cleaning and analyzing the data.***

I decided, for my portfolio project, to address the hypothetical problem of knowing some of the necessary requirements for starting an AI company and competing within that space. The main stakeholder would be a client who wishes to start a company offering AI services but would like to get a better picture of the current market. 

I downloaded the dataset that was used for this project from Kaggle. The name of the dataset is “Ai Companies Dataset”. The dataset can be found here: https://www.kaggle.com/datasets/vineethakkinapalli/ai-companies?datasetId=2266575

The original dataset was taken from the website here: https://clutch.co/developers/artificial-intelligence?page=1 which provided a list of 5,139 AI companies around the world. The dataset as I had downloaded it from Kaggle consisted of 3,096 companies. Eventually, I had to expunge approximately one-third of all those records from the dataset as those records had the value “Undisclosed” in either the Min Project Cost or Avg Hourly Rate columns or both. I also had to delete rows where ‘Location’ was blank. This left me with a total of 1,790 records for analysis.

First, I uploaded the dataset into Google Sheets and proceeded to clean it before analysis: 
I found and fixed one entry where the input was put into the wrong fields. I found two blank rows which I deleted. Found five potential duplicates most of which were different companies with the same name. Found two genuine duplicates and deleted those. 

I uploaded the partially clean dataset into OpenRefine. I merged locations with the same name but different spelling. I would make sure that they all had the same name in their values.

I split city and state as they were joined together in one column called, “Location”. Some cities were given without a state and some cities were joined with a state and some were joined with a country. I inputted the proper state/country for each city. I eventually had cities in one column, states in another, and country in a third column. This helped a great deal when working in Tableau.

I deleted the columns for the name of the company and website link because I decided that these variables/attributes were not relevant to the proposed problem.

I then proceeded on to analysis where I created a number of pivot tables in Google Sheets. I focused on the five variables that I laid out in my PowerPoint presentation. I examined different combinations of these variables in order to find any possible relationships between them.

After creating my pivot tables, I moved over to Tableau where I created the graphs, using my cleaned data, that would be incorporated into my presentation. I included in the speaker notes various caveats to the data that I would want stakeholders to be aware of when drawing conclusions from the data.


