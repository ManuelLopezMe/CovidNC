# Covid in NC

In this project I looked at the relationship between COVID related deaths by county and the percentage of the population that is African American.
I chose to compare the mortality rate to the African American population to see how vitamin D defiency (which many African Americans suffer from) affects COVID mortality.

The Data I collected on the amount of deaths by county was collected from the NCDHHS website on November 6, 2020. This data can be found in the County_Cases.csv file

I used Federal census data to find the total population by county and percent african american population by county and these can be viewed in the population.csv and aa_population.csv files respectively. This data was retrieved from IndexMundi (African American population data) and North Carolina Demographics by Cubit (County population data).

The statistical results in the jupyter notebook analysis.ipynb

The results show that the percentage of African Americans and the COVID mortality by county have a pearson correlation value of 0.513921 and that the former is a statistically significant variable at the 5% level. 

The linear regression also gives a R-squared value .264 indicating that more variables may be needed to explain the variance in the data. These could be things such as median age, population density, or something else. However, the purpose of this project was not to create that could best fit the data, but rather observe a relationship between vitamin D deficiency and mortality.
