a)	WHAT COUNTRIES HAVE THE HIGHEST AND LOWEST POPULATIONS? 

Within the SELECT statement, I used the MAX and MIN functions to retrieve highest and lowest population which i named AS highest_population and lowest_population respectively. I then used the ORDER BY function to organize the output in ascending and descending order. Owing to the large number of countries I applied a LIMIT of 5 on both categories.

b)	WHICH COUNTRIES EXPERIENCED THE HIGHEST YEARLY CHANGE IN POPULATION GROWTH?

Under the SELECT statement, I used the MAX function to retrieve the max yearly change in 2020 which i named AS highest_yearly_change. I then used the ORDER BY function to organize the output in DESC order. I applied a LIMIT of 5 to restrict the results to the top five highest. 

In both, the SELECT statement had the country and net change column. I utilized the ORDER BY clause, specifying net change with DESC and ASC to ensure the results are arranged in descending and ascending order respectively. Lastly I applied a LIMIT of 5 to restrict the output.

c)	WHICH COUNTRIES HAD THE HIGHEST AND LOWEST POPULATION NET CHANGE?
In both, the SELECT statement had the country and net change column. I utilized the ORDER BY clause, specifying net change with DESC and ASC to ensure the results are arranged in descending and ascending order respectively. Lastly I applied a LIMIT of 5 to restrict the output.

d)	WHAT COUNTRIES HAVE THE HIGHEST POPULATION DENSITY AND HOW DOES IT RELATE TO URBANIZATION?
I opted to create a new percentage column. To do this, I multiplied urban population by 100 with the alias AS Urban Pop Percentage. On the same, I applied the CAST function with the alias AS INT which ensured the absence of decimal points. The ORDER BY clause was employed to arrange the Density P Km in descending order, and finally, the LIMIT clause was applied to retrieve the data for the top 10 most densely populated countries.

e)	WHICH COUNTRIES HAVE THE LARGEST LAND AREA AND HOW DOES IT CORRELATE TO THEIR POPULATION SIZE?

This question required me to calculate the population densities of the largest countries by size. To do this, I divided population by land area and multiplied by 100. I also used the ORDER BY function to organize the land area output in DESC order and applied a limit of 10.

f)	WHICH COUNTRIES HAVE THE HIGHEST NET MIGRATION AND HOW DOES IT CORRELATE TO THEIR POPULATION GROWTH?
I calculated the net migration rate by dividing migrants net by population and multiplying by 100. By listing the migrants net in DESC order under the ORDER BY function, I was able to compare highest populations against migrant net.

g)	What countries have the highest and lowest fertility rates and how do they compare to population growth?
utilized the ORDER BY function in DESC and ASC order respectively to organize the fertility results in order of highest to lowest and vice versa.  

h)	WHICH COUNTRIES HAVE THE LOWEST AND HIGHEST MEDIAN AGES?
I utilized the ORDER BY function to arrange the ages in both ascending and descending orders. The initial query returned the highest median ages, ranging from 46 to 48, corresponding to Japan, Martinique, Italy, Portugal, and Greece. The second query returned ages in the range of 15 to 17, corresponding to Niger, Mali, Angola, Uganda and DR Congo.




















