# Surfs_up Temperature Challenge

## Purpose 
Using the new dependent learned from this module, SQL Alchemy, we gained access of a database that allowed us to analyze multiple weather aspects of different areas. In this case, we looked at an engine that referenced the state of Hawaiii and focused on historic temperatures in the month of June and December. Using the tools we have previously learned to create dataframes and calculate statistics behind our data, we will have two statistic summaries to compare the temperature trends of December and June.

## Development Enviornment
  - Jupyter Notebook 
  - Visual Studio Code
  - Dependencies
      - Pandas library 
      - NumPy library
      - SQL Alchemy

## Analysis & Results
  - Analysis 
      - The first key difference you see in the data presented is that the mean for temperatures in December is 3 degrees lower than the mean in June.
          - While this is likley not a surprise considering the seasons, it is interesting that December's mean of 71.04 is not too far off of the mean of June at 74.94. All in all, this gives a great depiction that Hawaii is a wonderful place to vacation no matter what time of the year it is. 
          
      - Perhaps the largest numbers that ranged from one another when comparing the June and December data was the minmimum temperature. In June, it was recorded at 64 degrees, while December marked in at 54 degrees. 
          - This variance is expected somewhat, as it would be expected to be somewhat colder at the cooler levels of December versus June. 
     
      - One confusing aspect of the data is why the overall counts are not at least within a few integers of one another. All of the extracted data from June leads to an overall count of 1700, while December clocked in at 1517. 
          - When you look further into the data, what you realize is that the data set for December does not include any digits in 2017 for December, but includes them for June. I am not 100% sure why this occured that way, however, getting the December 2017 dataset might absolutely skew the data or change the numbers. 

    
## Summary
While our challenge was solely focused on extracting two months of solely temperature data using SCL Alchemy databases, it would be interesting to use the information we determined in the modules to combine our knowledge of multiple factors to find the best times for vacation in that area. Temperature considered, it would be my recomendation to for W. Avy to open that ice cream and shop in June and should feel comfortable running it year round even potentially in the winter months like December. 