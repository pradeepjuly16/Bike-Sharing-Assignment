
# Bike-sharing-assignment
A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

# General Information
   A US bike-sharing provider BoomBikes has recently suffered considerable dips in their revenues due to the ongoing Corona pandemic. The company is finding it very difficult to sustain in the current market scenario. So, it has decided to come up with a mindful business plan to be able to accelerate its revenue as soon as the ongoing lockdown comes to an end, and the economy restores to a healthy state. 
   
### The company wants to know:
- Which variables are significant in predicting the demand for shared bikes.
- How well those variables describe the bike demands

## Technologies Used
- numpy - version 1.20.3
- pandas - version 1.3.4
- matplotlib - version 3.4.3
- plotly - version 5.6.0
- seaborn - version 0.11.2
- statsmodels - version 0.12.2
- sklearn - version 0.24.2
- scipy - version 1.7.1   

## Conclusion
Significant variables to predict the demand for shared bikes


* Temperature (temp) - A coefficient value of ‘0.375922’ indicated that a unit increase in temp variable increases the bike hire numbers by 0.375922 units. <br>

* Weather Situation 3 (weathersit_3)(Light Snow, Light Rain + Thunderstorm + Scattered clouds, Light Rain + Scattered) - A coefficient value of ‘-0.333164’ indicated that, w.r.t Weathersit_3, a unit increase in Weathersit_3 variable decreases the bike hire numbers by 0.333164 units.<br>

* Year (yr) - A coefficient value of ‘0.232965’ indicated that a unit increase in yr variable increases the bike hire numbers by 0.232965 units.<br>
