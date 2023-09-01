# Accident-Database-Analysis-Geo-Spatial-Modeling
## Description:
This project report is based on a detailed analysis of accidents within the UK in 2020. The analysis is based on 
information derived from an accident database containing records of each accident with geographic 
co-ordinates, casualties, vehicle details and a lower support output area record. The objective is to 
answer specific questions regarding accident occurrence rate, make insightful recommendations on 
best actions to improve road safety and build a classification model to help classify the severity of an 
accident.
To ensure accuracy, errors ranging from missing values, wrong entries, etc were treated and details of 
treatment method used are documented within this report.
Detailed visualization and analysis will be used to arrive at recommendations in the latter part of this 
report.

### Findings:
1. Accident significant day and time:

![q1 time plot](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/1e124c0d-dbc0-4309-9aa8-73d4a0ffcd36)

![q1 day all](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/09484ea7-ae50-4d2e-8339-9ac274dda979)

- Most accidents happened on Friday and at 17:00 hours of the day.

2. Top 5 regions with highest pedestrian accident rate:

   ![ped top 5 rgion](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/7d5e5090-e7e3-4593-95d5-827bd2ac127c)

- More pedestrian accidents occured in Birmingham compared to other areas.

3. Analysing Accidents in Humberside region of UK:

   ![Q5 1](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/cd91889a-785b-490a-b533-3aa3a1b25a60)

- More accidents occured in Kingston upon Hull compared to the other Humberside regions.

4. Geographical Clustering for Accidents in Humberside region:

   ![cluster region](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/90d76b68-e2df-4623-83d6-3336258fa7e7)

- Although accidents occurred at various locations across each region, accidents in each cluster were 
more concentrated in certain arears (Hull, Scunthorpe, Grimsby, Goole, Beverley, and Bridlington) 
compared to others within same region.

5. Critical Accident Location - Humber Bridge:

   ![humber acci](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/deec5944-3eb9-4092-98f2-f08d32bbd040)

- Four accidents, belonging to cluster 4, happened on the Humber Bridge. 
This is a critical place for any accident to occur, hence, it should be 
avoided as accidents on the bridge affects the overall structure of the bridge and poses more risk to other bridge users.

6. Predicting Accident Severity giving certain parameters:
   
    ![knn NEW](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/6d448f66-1813-481c-b2f6-5fc9e407622f)

   ![knn NEW2](https://github.com/giftomoba/Accident-Database-Analysis-Geo-Spatial-Modeling/assets/124467481/cde4045d-f3f9-4cac-83d1-acb621154904)
   
- Model predicts the severity of an accident with about 96% recall rate and precision of 89%.

## RECOMMENDATIONS:
Several age-related visual impairments could hinder a driver’s ability to see clearly. 
Hence, after license renewal, all drivers (especially above 90 years old) should be mandated to 
undergo periodical eye test to ascertain their visual impairment status.

Traffic on the Humber bridge should be critically monitored by road traffic and safety marshals, 
especially between 16:00 and 19:00 hours, as accidents occurred mainly within this period.

Road safety awareness campaign should be targeted at areas like Scunthorpe, Hull, Grimsby, and 
Bridlington with high accidence rate.

Vehicles in UK have an average lifespan of ten years. Hence, vehicles above ten 
years old should undergo frequent road worthiness test to determine their safety status. This would 
prevent old cars, with poor safety conditions, from public roads.
