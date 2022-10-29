# WeRateDogs-Udacity-Data-Wrangling-Project
This Project focuses on the data wrangling process involved in data analysis.  The purpose of the project was to wrangle and analyze data gathered from the "WeRateDogs" twitter account. The process involved three main steps which are: gathering, assessing and cleaning.
# Data Gathering
This is the very first step in data wrangling and invloves collecting or acquiring data from different sources. This data must be relevant to whatever analysis that is being done.Data can be gotten from numerous sources which are usually in different formats, the most important thing is that the data must be credible and you must be able to work with the data in its original format or convert it to a more suitable format required for the analysis.
For the purpose of this project, data was gathered from the WeRateDog twitter account. The dataset was gathered in three different formats, A csv file, A tsv file and a json file. 
# Data Assessment
Data assessment is the second step of the data wrangling process. When you have gathered your data from various sources, the next step is to examine the data for possible issues that can affect your analysis. This assessment can be carried out either **visually** and or **programmatically**.
Visual assessment involves scanning the data set for as many issues that can be spotted by merly looking through the data set. While you may be able to spot a few data issues, it is quite an ineffecient way of assessing data as there usually many more issues you may be unable to spot especially when working with larger data sets.
Programmatic assessement is however a very efficient way in assessing data. It invloves the use of programmatic languages and code is assessing data issues.
Data issues can be categorized into **Quality** and **Tidiness**.
Quality issues has to do with the content of the data while Tidiness issues has to do with the structure of the data.Below are the quality and Tidiness issues identified during the assessment step of the proeject
# Data Cleaning
This is the final step in the data wrangling process. It involves addressing issues identified in the data assessment step. 
It is advisable to create copies of the orginial data set before commencing the cleaning process, so that the original data set is not altered and can always be referred to.
The data cleaning step for this project followed a 3 step methodology:
- Define: Stating how the issues will be cleaned
- Code: Writing codes to solve the issue
- Test: Checking if the code worked
All quality and tidiness issues identified above were cleaned using pandas in python and other libraries and stored in a master csv file.
