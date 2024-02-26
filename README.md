# Data-Cleaning
## A variety of data cleaning methods applied to real world data. 

- Database concatenation
- Dropping NaN rows
- Renaming columns
- Filtering database
- Masking sensitive data
- Rounding entire columns
- Converting hh:mm string to hours float
- Correcting data


  ![image](https://github.com/BiancaBrianne/Data-Cleaning/assets/37970225/68693615-2fd1-4098-b5f5-4a5f0b4ee467)

The data preview above describes the attendance and length of time spent by students in the Math Learning Center. The data was collected from the accudemia system as 4 separate files. Theses files were concatenated, the variable 'Student_Number' contains sensitive informdation and was replaced with a masking value using hashlib, and first/middle/last names were dropped.


  ![image](https://github.com/BiancaBrianne/Data-Cleaning/assets/37970225/fd055f08-2d2f-4110-9c5b-da1e3d29d61d)

Here several variables have been renamed, missing data was filled with appropriate entries, and all empty rows were dropped. The variables 'Course_Code' and 'Student_Visits' are changed to integers. The variable 'Course_Code' should have entries with 4 digits but some data has been altered during importing process. To fix this we apply formatting that adds 0 to any entries that have less than 4 digits. For example, course DEBA should have a course code that reads 0001 but has the entry 1. 

![image](https://github.com/BiancaBrianne/Data-Cleaning/assets/37970225/63146df6-83b2-48b3-a5fc-ba57f3a61250)




