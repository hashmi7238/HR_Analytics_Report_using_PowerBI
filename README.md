# HR_Analytics_Report_using_PowerBI
OBJECTIVE:
-----------
Help an organization to improve employee performance and imrove employee retention(reduce attrition) by creating HR Analytics Dashboard.

Content:
---------

1.Import Data to Power BI
2.Data Cleaning and Processing
3.Power BI Report
   A.Creating KPIs in Power BI
   B.Creating Chart in Power BI
   C.Table in Power BI
4.Insight
5.Final Conclusion

Import Data to Power BI:
-------------------------
Import data in Power BI from 'Get Data', select CSV data source and path of CSV file and import data and transform it.

Data Cleaning and Processing:
------------------------------
Check each columns of data for null or duplicate value and remove it if it will not effect the overall analysis.
* Remove column "YearWithCurrManager" because it contain null values
* Remove duplicate from "EmpID" column.
* Select all the columns then remove the duplicate data.
* Replace 'TravelRarely' to 'Travel_Rarely' in "BusinessTravel" column.
* Sometimes Power BI didn't detect the DataType of columns for we have to do it manually.
   Steps-- * Select all columns
           * Go to transform
           * Click on 'Detect Data Type'
  
Power BI Report:
-----------------  
  A.Creating KPIs in Power BI:
  ----------------------------
  * Add KPI of "Count of Employee" by counting column EmpID
  * Add KPI of "Attrition Count" by Counting AttritionCount
  * Add KPI of "Attrition Rate" using Column AttritionRate
  * Add KPI of "Average of Age" using column Age
  * Add KPI of "Average of Salary" using column MonthlySalary
  * Add KPI of "Average year of employ work" using column 
    YearAtCompany

  B.Creating Chart in Power BI:
  ------------------------------
  1.Attrition by Education
  2.Attrition by Age
  3.Attrition by Gender
  4.Attriton by Salary
  5.Attrition by JobRole
  6.Attrition by Year at Company

  C.Table in Power BI:
  --------------------
  1.Table of "Attrition according to Deartment".
  

4.Insight:
------------
1.Out of 1470 employee, 237 employee left company with Attrition Rate of 16%.
2.Average age of employee work in company is 37 and average working period is 7 years that is good but average 
  salary is very low that might be reason why employee left.
3.Mostly employee who left belong to education background of Life Science, Medical, Marketing and Technical 
  degree which is about 94%. 
4.Mostly people who left company belong to age group  of 26-35.
5.Most of employee left company because of low salary so we need to increase the salary of employee little bit.
6.Most emplyee left from the demartment Laboratory, sales executive, Research scientist and sales representative. 7.Most of employee left job in 1st year of working. 

5.Final Conclusion:
-----------------
Mostly young(26-35) age group employee left job and obvious reason is low salary i'e less then 6k so company should think about it.
