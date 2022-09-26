# bikesharing

## Overview
The purpose of this project is to use 2019 data from CitiBike in New York City to answer questions about who uses these services. Insights from data visualization could be applied to starting a similar bikesharing program located in Des Moines, Iowa. Jupyter Notebook and the Pandas library are used to convert the tripduration column to datetime data type, and export the dataframe into a new csv which is to be used with Tableau to create visualizations. The resulting Tableau visualizations are tied into a story which is linked at the bottom of this page. 
## Results
### Checkout Times for Users

<img width="542" alt="checkout_times" src="https://user-images.githubusercontent.com/107224097/192395893-e7012bb2-4cdf-4dbd-9cc6-bddab83e81fc.PNG">
This visualization shows that the majority of trips are short, often less than 10 minutes. 

### Checkout Times by Gender

<img width="541" alt="checkouttimesbygender" src="https://user-images.githubusercontent.com/107224097/192395926-a76bdee7-ddcd-44f9-bfef-cf7bf424d050.PNG">
This visualization again shows that the majority of trips are relatively short. When breaking down trip duration by gender, there is no significant difference in trip duration shown. 

### Trips by Weekday for Each Hour

<img width="527" alt="tripsperweekdaybyhour" src="https://user-images.githubusercontent.com/107224097/192395966-640aa08c-634a-4c81-ad23-f60caa2a1710.PNG">
Monday and Thursday appear to be especially popular. The hours between 6 a.m. and 9 a.m., as well as the hours between 5 p.m. and 6 p.m. also appear to be especially popular. This suggests that these bikes are used more frequently for transportation to and from work. There is a slight increase later in the day Saturday, from 11 a.m. to 7 p.m., but this increase does not come close to the ride frequency in the morning and evening on week days. 

### Trips by Gender (Weekday per Hour)

<img width="541" alt="tripsbygenderwdhr" src="https://user-images.githubusercontent.com/107224097/192396011-b6a78f45-2cfc-4e5a-a752-7a71f44b4a32.PNG">
This shows a similar pattern to trips by weekday for each hour. 

### Trips by Customer Type

<img width="522" alt="customertype" src="https://user-images.githubusercontent.com/107224097/192396100-ee22a01c-983e-49e6-90eb-0a6e2bbe6d43.PNG">
Most of the trips customers take are from subscribers rather than one-time customers.

### Trips by Starting Location

<img width="544" alt="startinglocations" src="https://user-images.githubusercontent.com/107224097/192396134-c4cccd0f-7329-4749-a283-140dddbd2b15.PNG">
This shows the most popular starting locations by both size and color of the markers. 

### Trips by Weekday and Gender

<img width="537" alt="gendercustomerweekday" src="https://user-images.githubusercontent.com/107224097/192396921-6e2f3d26-3ba7-488e-8eed-dd91950b46d8.PNG">
Monday, Thursday, and Friday again appear to be the most popular days for trips for both male and female genders. 

## Summary
The trips by customer type visualization makes it clear that the vast majority of CitiBike users are subscribers as opposed to one-time customers. Roughly 19% of CitiBike trips for this month are accounted for by one-time customers. With this dataset, additional visualizations could be performed; such as comparing trip starting locations to trip ending locations, or identifying the most used bike ID's so that they could be inspected or repaired.

[link to dashboard](https://public.tableau.com/app/profile/spencer.kopp/viz/BikeSharing_16642286476750/Story1?publish=yes)
