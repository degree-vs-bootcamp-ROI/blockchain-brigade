# blockchain-brigade
Blockchain Brigade is a Data Analytics team that tracks the demand for Post Secondary education services being requested by the public.

## Overview
**Data Science Bootcamp vs Traditional Data Science Degree** <br/><br />
In today’s job market it is imperative for you to ensure your credentials are marketable and can appeal to multiple industries.  Technology is continuously evolving, and you may have noticed an increased trend in Data Science Bootcamps being offered.  <br /><br />
In this project we will develop a data analysis to determine the educational and financial benefit of obtaining data science credentials from completing a bootcamp vs getting a traditional data science degree.

## Project Team / Organization
<table>
  <th>Name</th>
  <th>Title</th>
  <tr>
    <td>Amber Martin</td>
    <td>Project Manager</td>
  </tr>
  <tr>
    <td>Karl Ramsay</td>
    <td>Repository Manager</td>
  </tr>
   <tr>
    <td>Oswaldo Moreno</td>
    <td>Scrum Master</td>
  </tr>
  <tr>
    <td>Ana Razak</td>
    <td>Programmer Analyst</td>
  </tr>
  <tr>
    <td>Anthony Brown</td>
    <td>Programmer Analyst</td>
  </tr>
</table>

## Project Overview
SCOPE: <br/>
To complete a full data analysis of API data and CSV files to determine job availability, education level and salary potential of completing a Data Science boot camp. <br/><br/>
OBJECTIVE: <br/>
- To understand the career benefit of completing Data Science boot camp
- Utilize the data results to make an educated decision on career path
- Gain an understanding of how completion of a Data Science boot camp compares to a traditional Data Science degree in today’s job market
- Project the financial benefit of salary increase potential 

## Let's Go to the Analysis
We wanted to determine the education level of people who enroll in Data Science programs.<br/> <br />
- Utilizing StockOver 2019 survey data, we imported the data file into Jupyter Notebook with a pd.read function. By creating a data frame and then cleaning the data within the frame created; with the use of functions like .replace, .groupby and .append , we were able identify the education levels within scope.  
- Based on the results of the analysis 49.6% of the survey participants who completed a Data Science Bootcamp do not have a traditional data science degree. With data science credentials trending a such a fast pace in today’s market people are choosing to complete a bootcamp in order to remain marketable.

![Edu_Level_Pie](images/edu_level_pct.png) <br />

Additionally we wanted to look at how many people with visas are working in the data science field to see how high the demand for people in the data science field is.  
- Using a VBA script, we prepped the csv file by creating two new columns called Role and Domain to filter out job titles using key word Data Science.. Then created a few groupby’s to get specific states we wanted to look at. 
- Then we wanted to look at the comparison in salaries for each job title. So made a bar graph comparing job titles to salaries and another bar graph comparing the number of H1B1 visas to job titles.  

![Edu_Level_Pie](images/ny_ds_visas_by_role.png) <br />

![Edu_Level_Pie](images/avg_salary_for_H1.png) <br />


