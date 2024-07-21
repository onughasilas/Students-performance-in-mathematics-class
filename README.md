# Students-performance-in-mathematics-class
## This project was conducted to analysis the different factors affecting performance of students in mathematics
# HERE ARE THE STEPS I USED IN ANALYSING THE STUDENTS PERFOMANCE DATA

## STEP1: Data Collection.
I was the mathematics teacher for these students , it was easy for me to collocet the data with the school managment permision for this project

## STEP2: Uploading the data to Excel
After collecting the students scores , i inputed the data in Excel sheet
## STEP3: Data cleaning. 
I cleaned the data by;
* Removing duplicate ; Data --> Remove duplicate --> All --> Ok
* Removing extra space , `=TRIM(A2:f16)`
##STEP4: Filtering empy cells
Helight all --> Filter -->select filter icon on each cell --> Check the required boxes -->ok
##STEP5: Creating new columns
I created new columns to aid my analysis sucs as;
* Weighted Average `= C3*$C$2 + D3*$D$2 + E3*$E$2 + F3*$F$2 + G3*$G$2` for each student
* Average score `=AVERAGE(C3:G3)` for each student
##STEP6: Pivot table
I created the following tables to be able to viualize my data and understand how those variables affects the performance of students in mathematics
* Gender
* Age
* Parental care/Wealth
#STEP7:I created Bar chat, line chart for claer understanding of the relationship.

