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
The data dictionary for the processed dataset can be seen as follow


      #   Column                          Data Type      Description
     ---  ------                          -----          -----     
      0   Country/Region                  object         Name of a country, geographic region, or economic grouping
      1   Year                            object         The year that the data were collected
      2   GDP (in billions)               float64        GDP, in billions USD, of a country
      3   GDP Growth                      float64        GDP Growth, in %, of a country
      4   GNI per Capita                  float64        GNI per Capita, in USD, of a country
      5   Inflation Rate                  float64        Inflation Rate, in %, of a country
      6   Unemployment Rate               float64        Unemployment Rate, in %, of a country
      7   Primary Sector (% of GDP)       float64        % of GDP contributed from the Primary Sector
      8   Secondary Sector (% of GDP)     float64        % of GDP contributed from the Secondary Sector
      9   Tertiary Sector (% of GDP)      float64        % of GDP contributed from the Tertiary Sector
 

### Potential issues
According to the World Bank's website, "much of the data comes from the statistical systems of member countries" (i.e., countries that made up the World Bank). Therefore, there's a potential that countries might deliberately misreport their economic data.
