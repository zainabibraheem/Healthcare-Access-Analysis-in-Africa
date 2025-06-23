# Healthcare-Access-Analysis-in-Africa

Unraveling the Challenges of Healthcare Accessibility in Africa: A Case Study 

## Project Overview
 
This case study aims to analyze healthcare facility data, identify disparities in access to healthcare between rural and urban regions, and evaluate the efficiency of healthcare funding. The objective is to propose data-driven recommendations that governments and stakeholders can implement to enhance healthcare service delivery across Africa. 

## Problem Statement

Access to healthcare services across Africa remains uneven, with significant disparities between rural and urban regions. Rural populations often face challenges such as inadequate medical infrastructure, a shortage of healthcare professionals, and limited access to essential services. 

## Aims and Objectives

## Aims
This study seeks to analyze healthcare facility data to identify gaps in service delivery, assess funding efficiency, and provide evidence-based recommendations to improve healthcare accessibility and equity across rural and urban regions in Africa.

## Objectives
1. To provide insights into the distribution of healthcare facilities between urban and rural locations. The number of doctors and nurses, and patient accessibility across different regions.
   
2. To give information on the availability of doctors and nurses per facility 
and how this varies between urban and rural locations.

3. To track the efficiency of the healthcare facilities by looking into funding per patient visits, emergency response time, and patient satisfaction rate.
4. To analyse the funding received by healthcare facilities and their access to 
essential services, such as electricity and the internet. 

## Data Transformation and Data Wrangling

Prepared the dataset for analysis by performing data cleaning and transformation tasks using Power Query. The process includes handling duplicates, missing values, and ensuring that the data format is consistent across various columns.

## Data Cleaning

The dataset was checked for duplicates, and no duplicates were found.
The column quality feature was used to check the dataset for missing values, and no missing values were found.
The format of the columns was checked, and the incorrect data types were corrected. e.g., the column funding received was corrected to currency.
After the dataset was cleaned using Power Query, it was loaded into Power BI for further analysis.
A new column was created to categorize the regions into urban and rural regions using a calculated column in DAX.
A new column was created to calculate the funding per patient visits of each facility by dividing the funding received by annual patient visits  using a calculated column in DAX.


## Exploratory Data Analysis 
## Key Business Questions 
1. How does the distribution of healthcare facilities compare between rural and urban regions? 
Urban Regions have a total of 1069 healthcare facilities, and Rural regions have a total of 931 healthcare facilities.

2. Are urban healthcare facilities receiving more funding than rural ones? 
According to the dataset, Urban healthcare facilities received more funds ($114M) than Rural healthcare facilities, which received $99M in funding.

3. Are healthcare facilities with higher funding more likely to have shorter emergency response times? 
According to this dataset, Funding does not affect emergency response time. There are some healthcare facilities with low funding and their emergency response time is low. On the other hand, there are some healthcare facilities with high funding but their emergency response time is still very high.

5. Which facility types (hospitals, clinics, health centers) show the highest efficiency in terms of funding per patient visit? 
The healthcare facility type that is most efficient is the hospital because it has the lowest funding per visit. Hospital has the lowest average funding per patient visit of 16, compared to the Clinic and Health center, which both have 17 as their average funding per patient visit.

## Insights
### Actionable Insights for Stakeholders 
7. What are the critical factors preventing equal access to healthcare across different regions? 
     1. The distribution of healthcare facilities across regions prevents equal access; more facilities are in the urban region than the rural regions. 
     2. Urban regions receive more funding than rural regions. 
     3. Many facilities in the rural region lack internet and electricity, which affects the quality of services provided by healthcare facilities in the Rural area.

8. Which policy recommendations can be made to bridge the gap between urban and rural healthcare services? 
     1. The provision of internet and electricity will improve the quality of healthcare services in rural regions.
     2. Rural regions have fewer doctors(10k) and nurses(26k)  compared to urban regions that have a total of 11k doctors and 29k nurses. More healthcare workers should be  employed in the rural regions to improve the healthcare services in the rural regions.
     3. More fundings should be allocated to the healthcare facilities in the rural regions to bridge the gap between urban and rural healthcare services.

## Recommendations
10. How can governments optimize healthcare funding allocation to maximize impact in underserved regions? 
     1. To optimize healthcare funding in rural regions, governments have to increase the funding allocated to these regions.
     2. Allocated funds should be used to provide needed resources, such as beds in the healthcare facilities in rural regions.
     3. To maximize the impact of the allocated funds, governments should provide infrastructural facilities such as electricity and internet.


## Dashboard
        
![Screenshot 2025-06-23 121723](https://github.com/user-attachments/assets/b601cf9a-aaa6-4b1e-8ccb-137e605f50cd)

![Screenshot 2025-06-23 121929](https://github.com/user-attachments/assets/0108ac94-502d-4379-bf13-6d6e847fa55a)


Link to Interactive Dashboard
https://app.powerbi.com/view?r=eyJrIjoiMzViYmMzZDItOWNiZC00MDBmLWJhZGEtNWM5MjAyM2FmMDI5IiwidCI6IjA0YWFkOGUyLWU3NWUtNDc3ZC1hYzc3LWMyOWE2MGJjNzFjOCJ9






