# Module-9-Challenge  Surfs_up
Advanced Data Storage and Retrieval with Jupyter Notebook, SQLite and SQLAlchemy.<br>
![ice_cream](/surfs_up/Image/ice_cream.png) <br>

# Overview of Project #
The purpose of this Project is to analyze the weather trends in **Oahu, Hawaii**. This data will be used to understand whether opening a Surf and Shake in Oahu will perform well. The Oahu shop serves surf boards and ice cream to tourist. If the shop in Oahu does well, they could expand to other islands. Specifically, summary statistics of temperature trends data has been requested for the months of June and December, in order to determine if the surf and ice cream shop business is sustainable year-round.

The analysis consisted of the following:
1. The Summary Statistics for June
2. The Summary Statistics for December

# Resources #
- Data Source: hawaii.sqlite
- Programming Files: SurfsUp_Challenge.ipynb, climate_analysis.ipynb
-	Data Tools: Python SQL toolkit (SQLAlchemy), Object Relational Mapper, pandas, numpy
- Software: SQLlite, Python 3.9.2, Flask, Jupyter Notebook

# Results #
## The Summary Statistics for June ##
The data gives summary statistics for the temperature trends in June form the Measurements table in the hawaii.sqlite database.<br>
The following depicts the June temps DataFrame:<br>
![June](/surfs_up/Image/June_temp.png) <br>

The average temperature recorded in June is about 75 degrees F and it is approximately 23 degrees c. It is clear with this analysis that June is one of the favourable month for the sustainability business of surfing and ice cream in the year.<br>

June Recorded Temps Visualization (Temperature and Frequency)<br>
![june_hist](/surfs_up/Image/june_hist.png) <br>

## The Summary Statistics for December ##
The data gives summary statistics for the temperature trends in December form the Measurements table in the hawaii.sqlite database.<br>
The following depicts the December temps DataFrame:<br>
![dec_temps](/surfs_up/Image/dec_temps.png) <br>

The average temperature recorded in December is about 71 degrees F and it is approximately 22 degrees c. By this analysis,It is clear with that December is also favourable month for the sustainability business of surfing and ice cream in the year. We can analyze that Oahu is a great location for the new surf shop.<br>

December Recorded Temps Visualization (Temperature and Frequency)<br>
![June](/surfs_up/Image/dec_hist.png) <br>
<br><br>

### Analysis Key Differences in Weather Detween June and December ###
The Analysis for both months June and December are as follows:<br>
![june_dec_temps](/surfs_up/Image/june_dec_temps.png) <br>
- The average recorded temperature in June is about 75 degrees F, 4 degrees higher than the average temp in December. This represents a 5% change in average temperature from June to December.
- June had a low temperature of 64??F and a high temperature of 85??F whereas December had a low temperature of 56??F and a high temperature of 83??F. 
- June and December had roughly similar standard deviations. June's standard deviation of 3.26 and December's standard deviation of 3.75 tells  that their temperature records are concentrated around both of their average temperatures. 

## Summary ##
- The summary Statistics for both the months June and December indicates that these two seasons had relatively warm temperatures and are good for business.

- The summary statistics of temperatures recorded by station for each month.This can help determine geopgraphically where in Oahu to build shop. By comparing the variances in temperatures and the frequencies recorded, we can select the appropriate location.<br>
![station](/surfs_up/Image/station.png) <br>
- There are other factors that we have to keep in mind to select the location apart from temperature such as precipitation, wave swells and wind condition.
## Further Analysis ##
The following depicts the analysis conducted for temperatue trends for entire year.<br>
![Whole_year_temp](/surfs_up/Image/Whole_year_temp.png) <br>
- The analysis representes that the temperatue between april and december is more favourable in entire year. As the temperatue is warmer.
- According to our analysis August is the most favourable month.<br>

The following depicts the visual repesentation for the average temperature by month:<br>
![avg_temp](/surfs_up/Image/avg_temp.png) <br>
<br><br>
