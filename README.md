### Bike Owners Dashboard Excel-Project

**Bike ownership around the globe**

This project identifies the relationship between bike ownership amongst certain demographics(age group, income, marital status, education etc.) in various regions of the world:

I downloaded the dataset from kaggle. the steps undertaken from the beginning to the end of the project are listed below;

1.	The First step was to eliminate any duplicate records within the dataset using the ‘Remove duplicates’ button underneath the ‘Data’ tab on the ribbon.

2.	The second step was checking for any spelling errors using the spellcheck function.

3.	Third step, alter the ‘M’ and ‘F’ categories to ‘Male’ and ‘Female’ in the Gender column. This provides better clarification for context. This was a simple process, the find and replace function was utilized in this transformation.

4.	The last step in the data cleaning process, involved creating various age groups for all specific age ranges.  People that are 30 and under were classified as ‘Young adult’, those that are 61 and below were classified as ‘Adults’, lastly ages 62 and above were classified as ‘Senior citizens.’ I utilized this nested ‘IF’ formula; (= IF([@Age]>=62, "Senior Citizen”, IF([@Age] <=30,"Young adult”, IF([@Age] <=61,"Adult", ))) to achieve this goal. 

5.	I converted the spreadsheet into a table. Indicating any modifications made to the worksheet are automatically updated. This ensures data integrity.

6.	Now time for some report analysis using pivot tables and charts. The first report indicates the average income of each age group that purchased a bike and those that did not.  As you can discern, the age group, ‘Adults’ have the highest average income, which suggests that higher income earners are more likely able to afford to purchase a bike. The statistics shown in the chart on the dashboard illustrates the correlation between income and purchasing a bike.

7.	The second graph illustrates how the distance of commute to work, school, park, the store etc.  impacts the customers decision of purchasing a bike. My analysis of the graph is; The shorter the distance of commute the more likely the person owns a bike, and the longer the distance the less likely the person owns a bike.

8.	The Pie chart illustrates the total number of people sampled in each region. It can be further filtered to those that purchased a bike by using the slicer labeled, ‘Purchased Bike’.

9.	The final graph on the dashboard illustrates the aggregate of those that purchased a bike and those that did not purchase a bike. It is further grouped by age group.






