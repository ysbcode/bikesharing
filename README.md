# NY_Citibike_Sharing

## Overview and Purpose
We are reviewing the New City Citibike usage data for the month of August 2019. The purpose of the review is to gain more information on usage patterns and distribution in order to roll out a similar program in Des Moine, Iowa. We created a story dashboard [data visualization](https://public.tableau.com/app/profile/yuvraj.bhati/viz/NYCCitibikeSharingProject/NYCitibikeSharing?publish=yes) of our results using Tableau. Please click on the hyperlink to view the tableau workbook.

## Results
From our review, we have identified the following criterias and characteristics which can be useful if the program is launched in Des Moine, Iowa. 

For the month of August 2019, there were approximately 2.34 Million rides availed by patrons of the service. Citibike seems to be most popular for short rides with the highest usage numbers in the 0-10 minute range. This usage pattern is uniform across different genders.

![](https://github.com/ysbcode/bikesharing/blob/main/screenshots/NY%20Citibike%20Summary.PNG?raw=true)

![](https://github.com/ysbcode/bikesharing/blob/main/screenshots/Checkout%20Time%20by%20Users.PNG?raw=true)

![](https://github.com/ysbcode/bikesharing/blob/main/screenshots/Checkout%20Time%20by%20Gender.PNG?raw=true)

The service is subscription based even though it is open to casual users. From our data, we observed that approximately 81% of the 2,4 million rides were done by subscribers. There is a distinct usage pattern between subscribers and casual users. The subscribers are more likely to avail the service during weekdays while casual users are more likely to use the service during weekends.

![](https://github.com/ysbcode/bikesharing/blob/main/screenshots/Trips%20Weekday%20per%20Hour%20by%20Users.PNG?raw=true)
 
The most popular usage times are in the mornings (8-10am) and evenings (5-7pm) in the weekdays and in the weekends the most popular usage times are in the afternoons (10am to 5pm). 
 
  ![](https://github.com/ysbcode/bikesharing/blob/main/screenshots/Usage%20by%20Gender%20for%20Time%20and%20Day%20of%20Week.PNG?raw=true)
  
If we combine the above two observations, we can conclude that subsribers use the serivce in the morning and evening to commute to and from work while casual users avail this service on the weekends as a leisure activity. 
 
This observation is further reinforced by our review of starting and ending stations. We noted that the most popular starting locations in the mornings are residentation areas such as the West Village or Alphabet City. The most popular ending stations in the morning are commercial areas such a Midtown and Tribecca. In the evenings, this is reversed with commercial areas being popular starting locations and residential areas being popular ending locations. This shows that the bike is used to commute to and from work by users. 

 ![](https://github.com/ysbcode/bikesharing/blob/main/screenshots/Popular%20Start%20and%20End%20Time.PNG?raw=true)
 
## Summary
We believe the citibike program is useful in densely populated urban areas where peoples average commute times are short. The service appears to be popular commuting tool for short commutes and leisure rides on the weekends. For future analysis, I would like to make two additonal visualizations: 
  - popular starting and ending points between subsribers and customers. So far we did not make this distinction. 
  - Average number of rides availed by each subsriber and each customer. This will help us determine the prices we can charge at Des Moine for casual use and monthly subsriptions.
