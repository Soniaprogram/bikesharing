# bikesharing

## Overview of analysis
The purpose of this analysis is to use Tableau to create effective visualizations from Citi Bike data in New York City. This analysis will be used to impress potential investors for a bike sharing business in Des Moines similar to Citi Bike in NYC.


#### Deliverable 1: Change Trip Duration to a Datetime Format
Using Python and Pandas functions, I converted the "tripduration" column from an integer to datetime datatype to get the time in hours, minutes, and seconds (00:00:00). After converting the "tripduration" column to a datetime datatype, I exported the DataFrame as a CSV file to use for the trip analysis in Deliverable 2.
See NYC_CitiBike_Challenge.ipynb

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

[link to dashboard](<div class='tableauPlaceholder' id='viz1617484312660' style='position: relative'><noscript><a href='#'><img alt='User Trips by Gender by Weekday ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NY&#47;NYC_Citibike_Challenge_16174335957650&#47;UserTripsbyGenderbyWeekday&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='NYC_Citibike_Challenge_16174335957650&#47;UserTripsbyGenderbyWeekday' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;NY&#47;NYC_Citibike_Challenge_16174335957650&#47;UserTripsbyGenderbyWeekday&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>                <script type='text/javascript'>                    var divElement = document.getElementById('viz1617484312660');                    var vizElement = divElement.getElementsByTagName('object')[0];                    vizElement.style.width='100%';vizElement.style.height=(divElement.offsetWidth*0.75)+'px';                    var scriptElement = document.createElement('script');                    scriptElement.src = 'https://public.tableau.com/javascripts/api/viz_v1.js';                    vizElement.parentNode.insertBefore(scriptElement, vizElement);                </script> "link to dashboard")


## Results
Results: Using the visualizations you have in your Tableau Story, describe the results of each visualization underneath the image


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


