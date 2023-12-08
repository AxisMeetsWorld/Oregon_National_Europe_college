## This is a basic project in a follow up to a request I had to compare the cost of college in Oregon to some European college countries
The project required gathering data from countries that have a "flat" or flatter cost of tuition like France and Germany to countries that had more of a "scale" based on major,
and location of the university.
There were a number of different techniques used in the data gathering:
- Pulling data into a tab-separated text file, importing into Excel, and aggregating similar data (like data based on majors)
  - Finding population percentage for outlier tuition costs (for example in Great Brittain, medical school costs more) and comparing outlier tuition against the average of all other tuition costs
  - Then multiplying presumed population percent of outlier tuition payers and presumed population of the remaining population with their respective tuition costs to obtain an average.
- Getting a flat average tuition cost when it is available from a source
- Finding the general tuition in countries where most public universities are government funded (flat tuition)
- For data that there is an opportunity to see trends, creating a historical trend analysis
- Getting a currency conversion between different countries and the US dollar
- Finally creating a few charts with Matplotlib in Google Colab

*This project might be expanded should the original requestors ask for more.*

### Countries studied
<code style="color : blue">United States, Great Brittan, France, Germany, Canada</code>


![You can see the final graph here:](https://github.com/AxisMeetsWorld/Oregon_National_Europe_college/blob/main/Final%20Graph.png)

<code style="color : purple">*Please note that the values for all geographics outside of Oregon are based on out of state tuition.*</code>
