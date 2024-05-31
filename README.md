# Accenture-Data-Analytics-and-Visualization-Virtual-Internship


## Project Understanding:
**A data analyst sits between the business and the data.**

 - One of Accenture’s Managing Directors, Mae Mulligan, is the client lead for Social Buzz.
 - She has reviewed the brief provided by Social Buzz and has assembled a diverse team of Accenture experts to deliver the project.
 - Mae has scheduled a project kick off call with the internal Accenture project team for tomorrow morning.
 - About Client : [Social Buzz](https://github.com/Swam80/Accenture_Forage_Virtual_Internship/blob/main/Data_Analytics%20Client%20Brief.pdf)
 - The client has reached a massive scale within recent years and does not have the resources internally to handle it.
 - Social Buzz receives over 100000 posts per day which amounts 36,500,000 posts every year, of which this all unstructured data making it very hard to make a sense.
 - Identify the requirements that need to be delivered for this project.
 - Merging of sample data set tables.
 - An analysis of their content categories that   highlights the top 5 categories with the largest aggregate popularity


#### Task for Accenture : 

 >- Client's Problem that Accenture is tasked to address : The client has reached a massive scale within recent years and does not have the resources internally to handle it.
 >- Three requirements that Accenture is tasked to fulfill : Audit of big data practice, recommendations for IPO, analysis of popular content
 
 #### Task for Data Analyst :
Analysis of sample data sets with visualizations to understand the popularity of different content categories.

In short, the client wanted to see **“An analysis of their content categories showing the top 5 categories with the largest popularity”.** 

 - Often you won’t need all these datasets to find what you’re looking for.
 - So, the first step is to use this [data model](https://github.com/Swam80/Accenture_Forage_Virtual_Internship/blob/main/Data%20model.pdf) to identify which datasets will be required to answer your business question - which is to to figure out the top 5 categories with the largest popularity.
 - After Analysis we got data sets needed to complete analysis:
 >- Reaction Score(score is used to quantified the popularity)
 >- Content ID
 >- Reaction Types
 >- Content type
 >- Category
 
### Data Cleaning and Modelling:
- Corrected irregular datatypes and converted date column to date format.
- Removed rows with NULL Reaction Types and unnecessary columns.
- Added Time of the Day column to analyze most active time.
- Corrected Content categories that had duplicate values like “animals” and Animals to a standard format ANIMALS.
- Used DAX in Power BI to form measures where AVERAGEX(),RELATED() and SUMX() function were used.
- Initially used VLOOKUP() in Excel and Power Query Merge to combine all datasets in to the base (reactions). However, data modelling was preferred.
- ![Data Model](https://github.com/Swam80/Accenture_Forage_Virtual_Internship/assets/42047546/66759553-3693-42b7-a83f-5f93563b6309)

## Dashboard and Insights:
- Dashboard PDF [Dashboard](https://github.com/Swam80/Accenture_Forage_Virtual_Internship/blob/main/accenture_bi.pdf)
- Animals, Science & Health Rule: Focus on real-world content like animals & science, and create campaigns with health brands  to match user interest.
- Tech is Booming : With rise in technology it is no surprise to see contents related to technology right up with the top categories. It show users enjoy your technology contents. I would recommend collaborating with some of the world’s tech giants as this would definitely make user engagement skyrocket.
- Morning Star : People seem to be the most active during Morning, strategize our campaigns and marketing ideas accordingly to  gain the most user engagement,


 
