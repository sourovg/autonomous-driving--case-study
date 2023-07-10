# Autonomous Driving Case-Study

## Objective
Understand and measure the performance of the Zoox test drive and how they are doing against competitors. For any autonomous test drive, the more miles you test without any notable disruptions confirms the probability of success in the real world. Having said that and given the data we have, at a first glance, it appears that the top level metrics should be:
- **Miles driven during the test drive** (more is better)
- **Number of disengagements during the test drive** (less is better)

However, these absolute metrics don't necessarily guarantee the benchmarking against competitors and don't provide meaningful insights while looking at metrics separately.
- The size of operations of the competitors' landscape is widely varied. The number of miles can just be a function of investment in the number of cars participating in the test drive.
- Individually, the number of disengagements can be just a function of miles driven even with proper solutions in place driven by newer possibilities not yet tested. 

Therefore, by looking at the objective and the context of study, we should track the following KPIs:

Primary KPI: (For Benchmarking)
- **Miles per vin :**  this indicates, given the amount of investment, we are driving sufficient miles to test all our features 
- **Miles per disengagement :** this indicates the quality of our system. The more miles we drive without disengagement, the more confident we are about the quality of performance of the system.

Secondary KPI: (For Internal Tracking)
- **Miles driven :** This is to ensure internally if we are gradually increasing collecting our test miles which are sufficuent to test of features and geogra[hies we plan to drive. If we plan for any city or couty for a given duration we can always track this against the **project miles to be driven **


## Analysis steps:
1. Exploratory data analysis (EDA)
2. Creating curated and reporting datasets from the source data
3. Building a Tableau Dashboard
4. Generate insights

### 1. Exploratory Data Analysis:

- found some inconsistencies in data and plan for data curstion
- **EDA code and results** are available in this file: EDA.ipynb

### 2. Creating curated and reporting datasets from the source data 
< write texs here>
- perform data-curation to clean up the data
- create longitudinal data from dmv_mileage source data sets to make it fit for better reporting and analysis purposes
- Append and merge mileage and disegnagement curated input data sources to
- Created a cumulative sum of key source metrics such as miles and disegnagement per month and vin
- **Code for this section** is available here: EDA.ipynb

### 3. Building a Tableau Dashboard

- Think about how to present the metrics - relevant charts. For example, cumulative presentation of the primary KPIs above makes more sense as <..... reason ...> 
- Thinking about layouts and the number of charts and dashboards makes sense. For example, we 'benchmarking analysis' and Zoox's performance metric for disengagement reasons. Analyses are kept in two different dashboard views. 
- **Tableau Report** is available here : zoox-cse-study.twbx

### 4. Generate Insights
<...write some text here ...>
1. Overall, Zoox produces more **'miles per diseggagement'** compared to the mean of competitors' but, its falls short in driving **'miles per vin'** compared to its key competitors except for 'Cruise, LLC', which is almost at the same level as Zoox:the competitors', 
   
2. Overall, zoox ranked **5th** w.r.t **'miles per vin'** in its competition. However, it did better w.r.t **'miles per disengagement'**, ranked **3rd**
   
3. However, Zoox has done well in 2022 w.r.t both the KPI and improved. As for 2021, Zoox ranked **7th** (**'miles per vin'**) and **5th** (**'miles per disengagement'**) respectively against competition
   
4. This is also evident from the cumulative trend charts below, which we see specifically from Jun'22, Zoox's performance in both the KPIs has got significant upwards traction compared to most of the competitors.
   
5. <... more insight s...>
   



