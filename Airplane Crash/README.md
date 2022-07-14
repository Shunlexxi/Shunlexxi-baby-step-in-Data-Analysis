![Airplane Crash - Uncleaned](https://user-images.githubusercontent.com/51166816/179035660-1de6012c-042e-4e5a-af19-2e7ff94c6f61.JPG)
# Project Name: Airplane Crash Analysis
---
# Project Objective: Problem Statement
This is a Capstone Project for the Ongoing 30DaysOfLearning - Data Analysis Track.

After looking at the dataset, here are some questions/insights I tried to answer/uncover;
1. Yearly, how many plane crashes were recorded? How many people were aboard? How many died (fatalities)? How many Survived?
2. Monthly, how many plane crashes were recorded?
3. Top 4 Days with the highest number of plane crashes.
4. Top 4 Countries with the Highest Number of plane crashes.
5. Top 4 Cities with the Highest Number of plane crashes.
6. Number of Crashes by Operator.
7. Number of crashes by type.

Metrics:

Number of Crash recorded.
The number of fatalities recorded.
The number of passengers aboard recorded.
Number of Survivors recorded.

---

# Data Sourcing:

At the time this Dataset was created in Kaggle (2016-09-09), the original version was hosted by Open Data by Socrata at the: https://opendata.socrata.com/Government/Airplane-Crashes-and-Fatalities-Since-1908/q2te-8cvq, but unfortunately that is not available anymore. The dataset contains data on airplane accidents involving civil, commercial, and military transport worldwide from 1908-09-17 to 2009-06-08.

https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908

---

# Data Transformation:
The Data was cleaned, manipulated, and transformed; 
* selected appropriate formats when needed.
* Extracted City and Country from the LOCATION Column (Which were concatenated)
* Defined "Survivor" as Aboard (Passengers on board) - Fatalities: Survivor = Aboard - Fatalities

---

# Recomendation: 
It was observed that cases with higher passengers on board have more fatalities, which could be a result of inadequate safety/emergence materials onboard. If that is the case, I'd recommend that adequate safe materials are stored in all planes should anything goes wrong. (I however understand that this is just a logical situation as the crash could be very bad and leaves a tiny percent for survivors.)


---

Shunlexxi-baby-step-in-Data-Analysis
