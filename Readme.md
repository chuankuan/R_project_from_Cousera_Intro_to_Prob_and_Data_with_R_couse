## <font color = 'darkmagenta'>This R code is my project when taking Coursera course </font>
## <font color = 'green'> Coursera course title: <span style='text-decoration:underline'>Introduction to Probability and Data with R</span></font>

### <font color ='navy'>This R code uses dataset file <*brfss2013_truncate.Rdata*>. This file has 56 columns and 491,775 rows. This dataset was taken from the above mentioned Coursera course. Original dataset has 330 columns and 491,775 rows. Most of the columns are removed as they are not being used in my code and to reduce file size.

### <font color ='navy'> The *brfss2013* (Behavioral Risk Factor Surveillance System 2013) dataset contains health related survey collected in year 2013 from all states in USA.

### <font color ='navy'>This code has 3 parts:
## <font color ='navy'>Part 1: clean data on column X_state by removing non-state information.</font>

### <font color ='navy'>Plot a bar chart on number of asthmaic cases on each state in terms of percentage to total surveying participants for comparison. State Oregan is among the highest rate of asthmatic percentage rate and worth looking into it the reason for it. One possible guess is that in Oregan,  bush fire may be more frequent and produces more smoke particles, causes asthmaic rate.</font>
## <font color ='navy'>Part 2: Finding out if over-weight has got any correlation with heart attack.</font>
### <font color ='navy'>I took a column with body-mass index(BMI) that comes with 4 categories of labels namely underweight, normal weight, overweight and obese.</font>
### <font color ='navy'>Another column I used provide heart attack occurance for the participants. From there, I grouped them to the BMI column and calculate the rate of heart attack per BMI group. I produced a geom-point plot to prove my case of BMI and heart attack correlation.</font>

### <font color ='navy'>I took another column of participants who declared to have been exercising for past 30 days. Again, I group them using BMI category and do a geom-point for each BMI category and the correlation opposite to the BMI-to-heart attack plot is shown. This indicate exercising does help in reducing body weight and in turn reduce chances of heart attack.</font>

## <font color ='navy'>Part 3: To find if income level has any impact in buying insurance.</font>
### <font color ='navy'>I groupded the income level category against surveyors who have insurance and have no insurance. A bar plot shows majority of them have insurance. For those who have no insurance, the difference is not obvious when compare to different income levels. But still, for those with lower income group, the number without insurance is still higher than those with higher income group.</font>

### <font color ='navy'> I took another column of data for those who declared unable to see doctor because of medical cost. I did a bar plot against the income group category, I see majority are able to see doctor across all income groups. There are also a small number who cannot see doctor because of medical cost across all income groups, and the differences between one income group to another is not so significant. This could be the insurance policies are accessiable to all income levels.</font>
