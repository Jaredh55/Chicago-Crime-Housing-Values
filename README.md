# Chicago Crime and Housing Values

This is my second capstone project of the Springboard Curriculum. 
\
\
My goal is to try to predict housing prices using crime data and what types of crime have the largest impact on housing prices
\
\
Crime data: https://data.cityofchicago.org/Public-Safety/Crimes-2001-to-present/ijzp-q8t2
\
Housing value data: https://www.zillow.com/research/data/
\
Neighborhood to Community Area mapping: https://en.wikipedia.org/wiki/Community_areas_in_Chicago
\
Population data: https://datahub.cmap.illinois.gov/dataset/2010-census-data-summarized-to-chicago-community-areas/resource/b30b47bf-bb0d-46b6-853b-47270fb7f626
\
\
The main presentation is located in ChicagoCrimeHousingValues.pdf
\
\
The code is broken up into 5 notebooks:
1. Data_Wrangling.ipynb
2. EDA.ipynb
3. Current_Models.ipynb (predicting current month housing values)
4. Future_Models.ipynb (predicting future month housing values)
5. LSTM.ipynb

\
Other documentation:
- Capstone 2 Consolidated Report.docx describes the project in detail including data wrangling, EDA, and models.
- CommunityArea_dictionary.csv provides numbers and populations for all Chicago community areas
- Neighborhood_MedianValuePerSqft_AllHomes_chicago.csv contains the used Zillow data
- Neighborhood_dictionary.csv contains the mapping of Zillow neighborhoods to Chicago community areas
- model_data.csv contains the unmodified dataframe after combining Zillow and crime datasets
- model_data2.csv contains the modified dataframe used in modeling

\
Crime data too large to publish

