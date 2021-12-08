### CSCI2000U  Car Sales Data Analysis Report

 
 
 ## Table of Contents 

   - Identification
   - Introduction
   - Exploratory Data
   - Conclusion
   
   






##  Indentification
  - Moharaj Oritro
 

## Introduction
   
   -  Statistical data analysis plays an important role in decision making. This dataset we analyse is based on different cars and the factors that impact the value of the vehicle. The main objective is to determine which factors are the most important that play in car value. The data is collected from 135 car manufacturer companies. As the recent spike in used car values increased, this topic became interesting for us to research.

  - With this goal in mind, we found a very broad dataset called Car Sales which was published on www.kagle.com. This data set is  a list of 156 car manufacturers with various different types of models and brands.Some of the attributes we investigated were
Manufacturers: The car companies
Price: the affordability of the vehicle
Vehicle type:  Body type (coupe,sedan etc)
Horsepower: How much power the engine can produce
Fuel Efficiency: The amount of money spent on refueling the car


- Finding the key factor that affects the value of the vehicle is done by visualized data analysis and data frames. What is the most important factor when it comes to the value of the vehicle? Why do some attributes correlate more than others? Is there such a thing as a reliable bmw? These are the questions we are looking to answer in this following report.


## Exploratory Analysis
   - To figure out which factor is the most important when it comes to the value of the car. We needed to create many different graphs to find the correlation. Since there were 12 factors, we decided to create a heatmap to understand which factor was the most important. We looked for positive correlations (which were closer to 1). But to our suprise  the most important attributes were Price in thousands, Horsepower and Fuel efficiency.

![Screenshot 2021-12-07 202617](https://user-images.githubusercontent.com/90271165/145131884-123cca39-9c06-4778-8181-8aaae268dd34.png)
- This was not expected because one would think that resell value would have more impact than the others. However the resell value only has a correlation of 0.24 which seems very strange. 

- Moving forward, I wanted to know  how much the value of a vehicle would exponentially grow as the horpower increased and the results were very interesting.

![image_2021-12-07_204007](https://user-images.githubusercontent.com/90271165/145133115-fd1c4ebf-99d1-492e-93f1-237ca20a7d20.png)
- We see that as the horsepower increases so does the  price.However around 300-350 horsepower the price is as high as 80,000 but trends downwards. This is very interesting becuase our hypothesis was that the higher the horsepower, the more expensive. This graph demonstrates that, it is simply not just the horsepower.Other factors such as torque,suspension, infotainment systems are reasons why the value of a vehicle could increase. However those factors are not in the dataset which limitates some of our research. For example a 2020 Lexus es 350 has 300 horsepower but has a price value of 49,0000 while a 2008 infiniti g35 has the same horsepower but costs way less (8000-15000).

-We can create a box plot to show our hypothesis. Take chrysler and audi for example. The range of horsepower is very similiar yet the price of an audi is significantly more expensive than a chrysler becuase of other factors such as suspension,fuel economy, body style, etc. 
 ![image_2021-12-07_214909](https://user-images.githubusercontent.com/90271165/145139645-cc4364d0-327e-4785-8e7a-004d63ca82a2.png)



## Conclusion

- In conclusion, conducting research on this topic was very challenging but very rewarding as I learned a lot of things. The original goal was to predict which factor was the most important and we can conclude that it is not just one simple factor that rules over the rest. A car is one of humanities greatest inventions and there are so many important components that can create one good vehicle. The research was very broad and we should have narrowed down to a specific market. It is very hard to compare a sport luxury sedan vs a comfortable daily driver when they have different markets and buyers. However we did learn that fuel effieciency is one of the more important facts that can increase the sales of a vehicle.Regardless of which marketplace the three most important factors horsepower, fuel efficiency and price of the vehicle.This dataset has potential for further data science research. We can use methods such as linear regression to predict the future costs and values of vehicles based on the information we are provided. Using predicitive data science techniques such  data modeling, machine learning, AI, deep learning algorithms will help to form and create a trend and predict the future costs of vehicles.Overall this dataset was very useful and has potential to used in differetn wasy of data analysis.


