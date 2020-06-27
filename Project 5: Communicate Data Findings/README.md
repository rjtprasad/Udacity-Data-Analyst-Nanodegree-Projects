# Exploring Bay Wheels Rides Data
### by RAJAT PRASAD

## Dataset

Bay Wheels is a regional public bicycle sharing system in the San Francisco Bay Area, California operated by Motivate in a partnership with the Metropolitan Transportation Commission and the Bay Area Air Quality Management District. Bay Wheels is the first regional and large-scale bicycle sharing system deployed in California and on the West Coast of the United States. It was established as Bay Area Bike Share in August 2013. As of January 2018, the Bay Wheels system had over 2,600 bicycles in 262 stations across San Francisco, East Bay and San Jose. On June 28, 2017, the system officially re-launched as Ford GoBike in a partnership with Ford Motor Company. After Motivate's acquisition by Lyft, the system was subsequently renamed to Bay Wheels in June 2019.

More information about [Bay Wheels](https://en.wikipedia.org/wiki/Bay_Wheels).

For the project I am using Bay Wheels ride dataset for year 2019 from month January to December. The dataset contains about 2,506,983 rows and 15 columns. For data set and summary of all variables avilable in dataset https://www.lyft.com/bikes/bay-wheels/system-data.

## Summary of Findings

About 82.23% of total rides are done by subscriber of Bay Wheels and only 17.77% of rides done by customer and about 92.25% of rides where users don't have price reduction option and only 7.85% of rides where users have CalFresh, SFMTA's Lifeline pass or PG&E's CARE discount.
Most of rides are done on regular days specially 8 in the morning and at 5 in the evening. Most of the rides are of duration 10 to 15 minutes for distance 1 to 2 km.

Most of the rides starts from Market St at 10th St and Berry St at 4th St. Customer ride more for longer duration and distance than subscriber. More rides are done by subscriber over days of weeks or months.

People ride for longer duration and distance on weekends than regular days. Subscriber ride for longer distance and duration in the morning and ride less in evening. Customer ride for longer distance and duration in the evening and ride less in morning.


## Key Insights for Presentation

- Proportion of rides done by each user type.
- Distribution of ride duration and distance.
- Average ride duration and distance for each user type.
- Rides by days of week and month for each user type.
- Peak hours of rides.
- Hourly and Weekly Rides for Each User Type.

## Resources

- [How to combine multiple CSV files](https://www.freecodecamp.org/news/how-to-combine-multiple-csv-files-with-8-lines-of-code-265183e0854/)
- [Bar Chart Annotations With Pandas and Matplotlib](https://robertmitchellv.com/blog-bar-chart-annotations-pandas-mpl.html)
- [Visualization with Seaborn](https://jakevdp.github.io/PythonDataScienceHandbook/04.14-visualization-with-seaborn.html)
- [Program for distance between two points on earth](https://www.geeksforgeeks.org/program-distance-two-points-earth/#:~:text=For%20this%20divide%20the%20values,is%20the%20radius%20of%20Earth.)
-[Seaborn Barplot Tutorial for Python](https://wellsr.com/python/seaborn-barplot-tutorial-for-python/#:~:text=If%20you%20want%20to%20display,have%20to%20do%20work%20around.&text=You%20can%20see%20that%20the,be%20stored%20in%20a%20variable.)