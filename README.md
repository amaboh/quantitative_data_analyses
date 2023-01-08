# quantitative_data_analyses
This is a model of housing prices based using multiple regression and logistic regression in R. 
This is a joint personal course work for my master program for two courses namely, Quantitative Data Analyses and Modern Data 

Quantitative Data analysis is a statistics using R taught at Brunel University by Isabel Sasoon 
Modern data is a data manipulation course based on R taught at Brunel Unviersity London by Martins Shepperd

To initialize this file clone this repo with the following command
git clone git@github.com:amaboh/quantitative_data_analyses.git

Alternatively you can fork this repository and make a copy of yours 

Then cd into the quantitative_data_analyses folder

The main file is the rmd file 


Our file is structured in the following format
1. Organise and clean the data
1.1 subset the data into the specific data subset allocated 1.2 data quality analysis
1.3 data cleaning
2. Exploratory data analysis 3. Modelling
3.1 explain your analysis plan
3.2 build a model for property price
3.3 critique your model using relevant diagnostics
3.4 based on 3.2 and 3.3 suggest improvements to your model
4. Extension work:


Below is Metadata table 
Variable (Column) name     Description
id    : Property id
Price   :  Sale price of the property
mq     :Total square meters of the property
Floor    : Entrance floor of the property
n_rooms     :Total number of rooms
n_bathrooms     :Total number of bathrooms
has_terrace     :Property has a terrace
has_alarm     :Property has an alarm
heating     :Type of heating (“autonomous”, “ other” ) has_air_conditioning     Property has Air conditioning
has_parking     :Property has parking
Is_furnished :was the property sold with its contents (furnishings) or not? (0,1)