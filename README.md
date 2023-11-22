# USA-Covid-19-Vaccine-Distribution-Analysis
Covid 19 Vaccine distribution analysis in USA for Sept 2022 - Sept 2023

In this project I analyzed the Covid 19 Vaccine distribution in USA for the period Sept 2022 - Sept 2023. For this project I have used the data published by US Government for Covid – 19 Vaccine distribution for the last 1 year. The data is available at [covid - 19 vaccine distribution data](https://data.cdc.gov/Vaccinations/COVID-19-Vaccinations-in-the-United-States-Jurisdi/unsk-b7fc). This data consist of different attributes like total number of vaccines distributed, number of vaccines administered, Number of vaccines distributed for people having age > 18, age > 50 and age > 65. Through this data, we can analyze what are the current trends going on in covid-19 vaccine distribution in each US State and hence can analyze the spread of covid-19 as well.
The following concepts of the big data from the course are used throughout the project.

 - Data Ingestion and Storage
 - Virtualization
 - Cloud Computing
 - Data Lifecycle & Pipelines
 - Data Processing and Analytics
 - AI Fairness
   
During this project, I downloaded the data from CDC website and kept it in the MongoDB Atlas which acted as a storage service for the project. Then I read all the data through python inbuilt libraries. I incorporated Jetstream VM to run my python code on the data. After that, I set up the data pipeline where I transformed the data and performed the in-depth analysis and at the end published the data and code on cloud (GCP) and GitHub.

Below is the data pipeline followed to achieve the end result

![Mgmt Access Big Data Project Methodology](https://github.com/anujmahajan98/USA-Covid-19-Vaccine-Distribution-Analysis/assets/53164451/70514363-e881-45cb-902f-44551b19949a)

For the detailed analysis you can look up the report shared in this git repository. Along with that I have published some of the interesting analysis on MongoDB chart Dashboard. The dashboard is public and you can access it on the following link.

[MongoDb Dashboard](https://charts.mongodb.com/charts-management-access-big-dat-bxlve/public/dashboards/076999fb-8558-4419-a973-e71792c63407)



