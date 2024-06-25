# Bike Sharing Assignment

> A bike-sharing system is a service in which bikes are made available for shared use to individuals on a short term basis for a price or free. Many bike share systems allow people to borrow a bike from a "dock" which is usually computer-controlled wherein the user enters the payment information, and the system unlocks it. This bike can then be returned to another dock belonging to the same system.

## Table of Contents

- [General Info](#general-information)
- [Technologies Used](#technologies-used)
- [Conclusions](#conclusions)
- [Acknowledgements](#acknowledgements)


## General Information

* They want to understand the factors affecting the demand for these shared bikes in the American market. The company wants to know:
    * Which variables are significant in predicting the demand for shared bikes.
    * How well those variables describe the bike demands


## Conclusions

Top features effecting the demand of shared bikes positively are

- Temperature: As temperatures rise, motorbike riding becomes more comfortable and enjoyable. This can entice more people to opt for motorbike sharing for commuting or leisure rides.
- Year: Over time, motorbike sharing services might become more established and convenient. Increased awareness, wider availability, and potentially lower pricing compared to car rentals could lead to a year-on-year rise in demand.
- Season_Winter: This might seem counterintuitive, but in some warmer US regions with mild winters, motorbike sharing could see a slight increase during winter compared to the hottest summer months. This could be due to more manageable weather, While still cooler, winter in these regions might offer more comfortable riding conditions compared to scorching summer heat and also because there is reduction in traffic.
- Month_Sept: September often marks the end of summer in the US. As the intense summer heat subsides, motorbike riding becomes more comfortable, potentially leading to an increase in demand compared to peak summer months.

- With Final Equation as
```
cnt = 0.239669 x yr + (-0.083884) x holiday + 0.487582 x temp + (-0.183457) x windspeed + (-0.054892) x season_Spring + 0.045609 x season_Summer + 0.068005 x season_Winter + (-0.033143) x mnth_Jan + (-0.053569) x mnth_Jul + 0.066688 x mnth_Sept + (-0.067414) x weathersit_Mist & Cloudy + 0.200957
```


## Technologies Used

- numpy - version 1.23.4
- pandas - version 1.5.1
- matplotlib - version 3.7.5
- seaborn - version 0.13.2
- scikit-learn - version 1.1.2
- statsmodels - version 0.14.1

## Acknowledgements
This project was inspired by UpGrad IITB Programme as a case study for the Machine Learning and Artificial Intelligence course.

## Contact

Created by [@S-KrishnaSai9] - feel free to contact me!

## License
This project is open source and available under the [... License]().