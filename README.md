# Data-Analysis-using-R
Analyzing the sample dataset using R. Performed various tasks like Retrieving the data, Glimpse of data, Checking for missing data  and Data Exploration.

Introduction:
Analyzing the given data set which contains attributes like Dependents, Loan amount, Self Employed, and applicant income and has rows of 614. The data set is being analyzed in Jupyter by using R.
Retrieving the Data:
![image](https://github.com/varahakrishna/Data-Analysis-using-R/assets/114026298/688ea655-d468-445d-b8ce-a8496d5afc5a)
A glimpse of Data:
![image](https://github.com/varahakrishna/Data-Analysis-using-R/assets/114026298/eb314512-188a-4efb-8132-7256d234f10d)
Data Preprocessing:
![image](https://github.com/varahakrishna/Data-Analysis-using-R/assets/114026298/d1706bd7-e7bd-444f-900e-ce40ee31b191)
Visualization:
ggplot function usage To determine the number of each kind, I mapped married to the x-axis and count to the y-axis. I have used the position function as dodge so that bar plotting is not overlapped.
![image](https://github.com/varahakrishna/Data-Analysis-using-R/assets/114026298/0d9c81c6-58a7-4e0e-b574-e07c671514de)
I used the built-in piechart function to display the pie chart with the property area, and to calculate the percentage for each component, we categorized the data and calculated the count, which we subsequently divided by the total rows in the data set.
![image](https://github.com/varahakrishna/Data-Analysis-using-R/assets/114026298/50c7d5ee-b354-46ff-935d-b251268071fd)
Insights from the data "
To get an interesting pattern, I have tried to implement the bar plot using the plot function. I have plotted a graph with (Gender, applicant income) and (Gender, and Property Area) columns.
We can clearly see that Male applicants have higher Applicant income compared to Females or NA. We also may conclude that this is one of the reasons why males are being granted more loans.
![image](https://github.com/varahakrishna/Data-Analysis-using-R/assets/114026298/baeb793e-c273-4406-b864-a5dbb024921f)
We can clearly see from the below data that males have more property area in all three categories of rural, urban, and semi-urban areas compared to females and hence we can conclude that gents have more property area.
Secondly, we can say that females in urban have more property areas compared to others i.e., NA in rural areas which is exactly opposite of others i.e. NA in rural and Urban areas.
![image](https://github.com/varahakrishna/Data-Analysis-using-R/assets/114026298/110fda8a-66bf-4787-845d-bd6e28ce5f38)

References:


https://r4stats.com/examples/graphics-ggplot2 -ggplot in R

https://www.section.io/engineering-education/data-preprocessing-in-r - Data preprocessing in R

https://www.tutorialspoint.com/r/r_data_frames.htm- Data Frames

