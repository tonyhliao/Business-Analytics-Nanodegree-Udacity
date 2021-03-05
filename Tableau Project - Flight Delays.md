```
I completed this project as part of the Business Analytics course by Udacity
```
# Tableau Project: Flight Delays

### Introduction
<p align="justify">
I used Tableau Desktop and Tableau Public to create three different visualizations to reveal insights from a data set. This data set tracks the on-time performance of US domestic flights operated by large air carriers in 2015. I provided images of the visualizations below, as well as hyperlinks to view the interactive versions.
</p>

### Left JOINs on Source Data
<p align="justify">
Before creating the visualizations, I used the Left Join function on flights.csv and airlines.csv, as well as between flights.csv and airports.csv, so that I could have access to the airline and airport names, instead of only the Iata Codes. This helps viewers understand more clearly which airlines or airports are being compared.
</p>

## Insight 1 – Which months have the smallest and largest Arrival Delays for Spirit Air Lines?
<div class='tableauPlaceholder' id='viz1614798066164' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;ArrivalDelaysbyMonth&#47;Sheet1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='ArrivalDelaysbyMonth&#47;Sheet1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Ar&#47;ArrivalDelaysbyMonth&#47;Sheet1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>      

### <a href="https://public.tableau.com/profile/tony.liao#!/vizhome/ArrivalDelaysbyMonth/Sheet1">Total Arrival Delay by Month</a>
<p align="justify">
From the line chart, we can see which months have the smallest and largest Total Arrival Delays (in minutes). Using the Airlines column as a filter, we can either see the delays for all the airlines combined, or select a specific airline. For Spirit Air Lines, June has the most delay across all flights, at a total of 17, minutes, while April has the least amount of delay, at 3001 minutes.
</p>

## Insight 2 – Which state has the most Departure Delay on Monday?
<div class='tableauPlaceholder' id='viz1614797865181' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TotalDepartureDelaysinU_S_States&#47;Dashboard1&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='TotalDepartureDelaysinU_S_States&#47;Dashboard1' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;To&#47;TotalDepartureDelaysinU_S_States&#47;Dashboard1&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>    

### <a href="https://public.tableau.com/profile/tony.liao#!/vizhome/TotalDepartureDelaysinU_S_States/Dashboard1">Total Departure Delays by U.S. State</a>

<p align="justify">
From the dashboard, we can see which states have the most amount of Departure Delay. For this
dashboard, I used the Day of Week as the filter. For Day 1 of the week (Monday), CA is the state with the
highest Departure Delay, at 55,515 minutes.
</p>

<p align="justify">
The map has a blue-orange color palette, so that color-blind individuals may also view the dashboard with
ease.
</p>

## Insight 3 – What time of day are Security Delays most prevalent?
<div class='tableauPlaceholder' id='viz1614798014671' style='position: relative'><noscript><a href='#'><img alt=' ' src='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Se&#47;SecurityDelaysThroughouttheDay&#47;Sheet4&#47;1_rss.png' style='border: none' /></a></noscript><object class='tableauViz'  style='display:none;'><param name='host_url' value='https%3A%2F%2Fpublic.tableau.com%2F' /> <param name='embed_code_version' value='3' /> <param name='site_root' value='' /><param name='name' value='SecurityDelaysThroughouttheDay&#47;Sheet4' /><param name='tabs' value='no' /><param name='toolbar' value='yes' /><param name='static_image' value='https:&#47;&#47;public.tableau.com&#47;static&#47;images&#47;Se&#47;SecurityDelaysThroughouttheDay&#47;Sheet4&#47;1.png' /> <param name='animate_transition' value='yes' /><param name='display_static_image' value='yes' /><param name='display_spinner' value='yes' /><param name='display_overlay' value='yes' /><param name='display_count' value='yes' /><param name='language' value='en' /></object></div>              

### <a href="https://public.tableau.com/profile/tony.liao#!/vizhome/SecurityDelaysThroughouttheDay/Sheet4">Security Delays Throughout the Day</a>
<p align="justify">
From this line chart, we can compare the length of security delays to the Scheduled Departure. We see
that most Security Delays above 0 min are between 5:00 and 23:00. The longest average delay for a
particular time was 27 min at 6:42, with a second longest average delay of 26.75 min at 7:06.
</p>
<p align="justify">
I have also included in this worksheet a tooltip, where if one hovers over any of the scatter points, the
popup will also give the average Departure Delays for that time. For example, hovering at the point of 27
min at 6:42, the average Departure Delay is 2.7 min, suggesting that there are many other flights at this
particular time that depart early to pull the average down.
</p>

