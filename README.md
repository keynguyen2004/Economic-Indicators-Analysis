# Economic Indicators Analysis

### Project goal
This project aims to analyze the relationship between different economic indicators, particularly focusing on


    1. GDP vs GNI per Capita
    2. Economic sectors
    3. GDP Growth, Inflation Rate, and Unemployment Rate


### API documentation
We'll be using datasets from World Bank through `pandas_datareader` libary, which allow up-to-date remote data access. The documentation of `pandas_datareader` can be found here: https://pandas-datareader.readthedocs.io/en/latest/


### License of data
The World Bank's license for its datasets is under CC-BY 4.0. In short, one is free to 


    1. Share - copy and redistribute the material in any medium or format
    2. Adapt - remix, transform, and build upon the material for any purpose, even commercially
    
    
The World Bank's license for its datasets can found here: https://datacatalog.worldbank.org/public-licenses


### Data type and description
The data dictionary can be seen as follow


      #   Column                         Data Type  
     ---  ------                           -----  
      0   Country/Region                  object 
      1   Year                            object 
      2   GDP                             float64
      3   GDP Growth                      float64
      4   GNI per Capita                  float64
      5   Inflation Rate                  float64
      6   Unemployment Rate               float64
      7   Primary Sector (% of GDP)       float64
      8   Secondary Sector (% of GDP)     float64
      9   Tertiary Sector (% of GDP)      float64
 

### Potential issues
According to the World Bank's website, "much of the data comes from the statistical systems of member countries" (i.e., countries that made up the World Bank). Therefore, there's a potential that countries might deliberately misreport their economic data.
