# Covid19 Impact on K-12 Education
By Megan Nalani Chun  
Last modified December 2020

## Abstract
The children of today will be the decision makers of tomorrow and their education will help determine what those decisions will be. Unfortunately, Covid19 has negatively affected learning and education for students around the world. This analysis leverages Covid19 school policy data by school district and the number of confirmed Covid19 cases by county to investigate the extent of Covid19's impact to K-12 public education in the US. Additionally, this analysis focuses on the role of demographics. The research questions addressed are: What is the impact of Covid19 on school closures and teaching methods for K-12 students across the US? How does this differ for students based on race, income, and computer/internet access? The methodologies used include exploration, data visualization, correlation, and logistic regression. 

The main findings were that student learning was widely and negatively affected by the pandemic where almost 7 million students missed at least some school and 16 million students experienced their education moving completely online. The students experiencing the most school closures and transitions to online learning were those in school districts with higher percentages of minority students such as Black/African American, Native American, Asian American, and other races in addition to higher percentages of students from low income households. Covid19 has dramatically increased educational inequity and unfortunately the same policies are likely to continue through the rest of the 2020-2021 school year. In order to help curb the negative effects in the coming semester, school districts with more minorities and low income students need additional support.

An additional finding is the moderate positive correlation between school policies and the number of Covid19 cases. If school districts implemented policies such as requiring masks, social distancing, reducing sports participation, and having return from illness protocols earlier in the pandemic, the districts may have helped reduce the need for online learning, school closures, and the number of Covid19 cases in the long run. Therefore, in future pandemics schools in areas with larger populations should implement safe prevention policies early to minimize negative impacts on K-12 education and slow the spread of the disease/virus.

Overall, the analysis shows that school districts were not prepared to deal with education during a pandemic. Going forward insights, findings, and learnings need to be used to create a better plan for K-12 education that is more inclusive of minorities and students from low income households because society will see the most progress when made up of diverse, educated people.

## Data Sources
- Covid19 K-12 Education Data by MCH Strategic Data. Compiled from public federal, state, and local school districts information and media updates. Go to the [Main page](https://www.mchdata.com/covid19/schoolclosings), scroll down, make a free account, and press the "download list of districts" button. Select subscribe and sign up for free subscription to download the dataset. No credit card information is needed. [covid-data.csv](https://github.com/NalaniKai/data-512-final/tree/main/Data/Covid19_K-12_Education)

- Education Demographic and Geographic Estimates. National Center for Education Statistics. Institute of Education Sciences.   
    - [Dataset: ACS 2014-2018 Profile](https://nces.ed.gov/programs/edge/TableViewer/acsProfile/2018)
    - Geography: All Districts 
    - Population: Relevant Children
    - Tables:        
        - CDP02.2 SCHOOL ENROLLMENT [CDP02.2_102_USSchoolDistrictAll_111231815433.txt](https://github.com/NalaniKai/data-512-final/blob/main/Data/Demographics/CDP02.2_102_USSchoolDistrictAll_111231815433.txt)
        - CDP02.11 COMPUTERS AND INTERNET USE [CDP02.11_102_USSchoolDistrictAll_111233642475.txt](https://github.com/NalaniKai/data-512-final/blob/main/Data/Demographics/CDP02.11_102_USSchoolDistrictAll_111233642475.txt)
        - CDP03.2 INCOME AND BENEFITS (IN 2018 INFLATION-ADJUSTED DOLLARS) [CDP03.2_102_USSchoolDistrictAll_111234614792.txt](https://github.com/NalaniKai/data-512-final/blob/main/Data/Demographics/CDP03.2_102_USSchoolDistrictAll_111234614792.txt)
        - CDP05.2 RACE [CDP05.2_102_USSchoolDistrictAll_11123448541.txt](https://github.com/NalaniKai/data-512-final/blob/main/Data/Demographics/CDP05.2_102_USSchoolDistrictAll_11123448541.txt)


- United States Census Bureau [School Districts and Associated Counties](https://www.census.gov/programs-surveys/saipe/guidance-geographies/districts-counties.html). [sdlist-19.xls](https://github.com/NalaniKai/data-512-final/tree/main/Data/County_SchoolDistrict_Intermediary)

- COVID-19 Data Repository by the Center for Systems Science and Engineering (CSSE) at Johns Hopkins University. [csse_covid_19_time_series](https://github.com/CSSEGISandData/COVID-19/blob/master/csse_covid_19_data/csse_covid_19_time_series/). [time_series_covid19_deaths_US.csv](https://github.com/NalaniKai/data-512-final/tree/main/Data/Covid19_CasesByCounty)

  
## Data Licensing
- Covid19 K-12 Education Data by MCH Strategic Data. Compiled from public federal, state, and local school districts information and media updates. [MCH 2019 Standard Licensing Stipulations and Conditions Agreement](https://www.mchdata.com/about/terms-conditions)
  
- Education Demographic and Geographic Estimates. National Center for Education Statistics. Institute of Education Sciences. [Open Data Policy](https://digital.gov/open-data-policy-m-13-13/)    

- United States Census Bureau. [Public Domain U.S. Government](https://www.usa.gov/government-works)

- Johns Hopkins University Center for Systems Science and Engineering. [Creative Commons Attribution 4.0 International (CC BY 4.0)](https://creativecommons.org/licenses/by/4.0/deed.ast)

## Project Licensing
[MIT License](https://github.com/NalaniKai/data-512-final/blob/main/LICENSE)
