# bikesharing

## Overview of analysis
The purpose of this analysis is to use Tableau to create effective visualizations from Citi Bike data in New York City. This analysis will be used to impress potential investors for a bike sharing business in Des Moines similar to Citi Bike in NYC.

#### Deliverable 1: Change Trip Duration to a Datetime Format
Using Python and Pandas functions, I converted the "tripduration" column from an integer to datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After converting the "tripduration" column to a datetime datatype, I exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.

See NYC_CitiBike_Challenge.ipynb
![img](https://github.com/Soniaprogram/bikesharing/blob/main/images/del1.PNG)

#### Deliverable 2: Create Visualizations for the Trip Analysis
Using Tableau, I created the following 5 visualizations:

Visualizations 1-2: Show the length of time that bikes are checked out for all riders and genders
* Line graph displaying the number of bikes checked out by duration for all users and the graph can be filtered by the hour
* Line graph displaying the number of bikes that are checked out by duration for each gender by the hour and the graph can be filtered by the hour and gender

Visualizations 3-4: Show the number of bike trips for all riders and genders for each hour of each day of the week
* Heatmap showing the number of bike trips for each hour of each day of the week
* Heatmap showing the number of bike trips by gender for each hour of each day of the week and the heatmap can be filtered by gender

Visualization 5: Shows the number of bike trips for each type of user and gender for each day of the week.
* Heatmap is created showing the number of bike trips for each type of user and gender for each day of the week and can only be filtered by user and gender

#### Deliverable 3: Create a Story and Report for the Final Presentation
[Link to Dashboard](https://public.tableau.com/views/NYC_Citibike_Challenge_16174335957650/CitiBikeinNYCUserActivity?:language=en&:display_count=y&publish=yes&:origin=viz_share_link "Link to Dashboard")

## Results
#### Access Tableau Dashboard Visualizations and Story here:
[Link to Dashboard](https://public.tableau.com/views/NYC_Citibike_Challenge_16174335957650/CitiBikeinNYCUserActivity?:language=en&:display_count=y&publish=yes&:origin=viz_share_link "Link to Dashboard")

### Checkout Times for Users
![img1](https://github.com/Soniaprogram/bikesharing/blob/main/images/1_checkouttimesforusers.PNG)
The bike checkout times peaked at 0h 5 minutes with 146,752 views.

### Checkout Times for Users by Gender
![img2](https://github.com/Soniaprogram/bikesharing/blob/main/images/2_checkouttimesbygender.PNG)
73.7% of the bike checkout times at the peak time stated above consisted of males at 108,087 views. (108,087/146,752 * 100 = 73.7%)

### Trips by Weekday per Hour
![img3](https://github.com/Soniaprogram/bikesharing/blob/main/images/3_tripsbyweekdayperhour.PNG)
Most trips were taken during Monday-Friday during 7am-9am and Monday-Friday during 5pm-7pm. The peak being at Thursday at 5pm with 43,982 trips and at 6pm with 44,905 trips.

### Trips by Gender (Weekday per Hour)
![img4](https://github.com/Soniaprogram/bikesharing/blob/main/images/4_tripsbygender.PNG)
During the peak times above, it appears males take the most trips. At the peak time on Thursday at 5pm, males took 30,561 trips (30,561/43,982 * 100 = 69.5%) and at 6pm, males took 30,749 trips (30,749/44,905 * 100 = 68.5%). 

### User Trips by Gender by Weekday
![img5](https://github.com/Soniaprogram/bikesharing/blob/main/images/5_usertripsbygenderbyweekday.PNG)
The most trips were taken by males and by subcribers during the weekdays. The maximum trips taken by male subscribers are 259,316 trips on Thursday. 

#### Added 3 more visualizations:

### Customers
![img6](https://github.com/Soniaprogram/bikesharing/blob/main/images/6_customers.PNG)

### August Peak Hours
![img7](https://github.com/Soniaprogram/bikesharing/blob/main/images/7_Augustpeakhours.PNG)

### Gender Breakdown
![img8](https://github.com/Soniaprogram/bikesharing/blob/main/images/8_genderbreakdown.PNG)

## Summary
Summary: Provide a high-level summary of the results and two additional visualizations that you would perform with the given dataset.

In Tableau, create a new Story using visualizations that will support the key findings you want to show.

You must use the five visualizations that you created in Deliverable 2.
You must use at least two visualizations that you created in this module.

In your README markdown file, include the following:
Results:
There are at least seven visualizations for the NYC Citibike analysis (7 pt)
There is a description of the results for each visualization (7 pt)
Summary:
There is a high-level summary of the results and two additional visualizations are suggested for future analysis (5 pt)


