# Project Name: Airplane Crash Analysis
---
# Project Objective: Problem Statement
This is a Capstone Project for the Ongoing 30DaysOfLearning - Data Analysis Track.

After looking at the dataset, here are some questions/insight I tried to answer/unrecover;
1. Yearly, how many plane crash were recorded? How many people were aboard? How many died (fatalities)? How many Survived?
2. Monthly, how many plane crash were recorded?
3. Top 4 Days with the highest Number of plane crash.
4. Top 4 Countries with the highest Number of plane crash.
5. Top 4 Cities with the highest Number of plane crash.
6. Number of Crash by Operator.
7. Number of crash by types.

Metrics:

Number of Crash recorded.
Number of fatalities recorded.
Number of passengers aboard recorded.
Number of Survivors recorded.

---

# Data Sourcing:

At the time this Dataset was created in Kaggle (2016-09-09), the original version was hosted by Open Data by Socrata at the at: https://opendata.socrata.com/Government/Airplane-Crashes-and-Fatalities-Since-1908/q2te-8cvq, but unfortunately that is not available anymore. The dataset contains data of airplane accidents involving civil, commercial and military transport worldwide from 1908-09-17 to 2009-06-08.

https://www.kaggle.com/datasets/saurograndi/airplane-crashes-since-1908

---

# Data Transformation:
The Data was cleaned, manipulated and transformed; 
* selected appropriate formats when needed.
* Extracted City and Country from the LOCATION Column (Which were concocatenated)
* Defined "Survivor" as Aboard (Passengers on board) - Fatalities: Survivor = Aboard - Fatalities

---

# Recomendation: 
It was observed that cases with higher passengers on board has more fatalities, which could be as a result of inadequate safety/emergence materials onboard. If that is the case, I'd recommend that adequate safey materials be stored in all planes should anything goes wrong. (I however understand that this is just a logical situation as the crash could be very bad and leaves tiny percent for survivors.)


---

Shunlexxi-baby-step-in-Data-Analysis
