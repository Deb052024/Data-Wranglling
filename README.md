# Data-Wranglling
 There are 3 different data sets 

 These data sets need to be acquired 

1. Data Set 1 and 2 need to be merged and the merged set need to be concatenated with Data Set 3

On these Data Set , there exists lot of ambiguity

 2. Post removing such ambiguity, meaningful insights to be derived from the data set – Bike Ride business study 
Data acquisition

Different Methods of Data Wrangling

1. Merge Data Set
2. Identify unique value
3. Drop unnecessary columns
4. Check Dimension of Data Set
5. Check the Data type of Data Set
6. Check the data type summary
7. Treat Missing values
8. Validate the correctness of the data at the primary level if applicable
9. Different scenario building pre and post removal of outliers as well as concatenation 

Data Acquisition and Wrangling
1. Data set 1,2 &3 have been acquired and assigned to Data Frame1,2&3 respectively 

 2. Data Frame 1(Df1) and (DF2) each has 610 rows and they have 10 and 7 columns respectively
 
3. No duplicate values on data Frame 1

4. “Unnamed” attribute has been dropped from Df2

 5. Df1 and2 were merged using inner join and assigned to Bike Count
 
6. There were 11 null values found on Bike Count and were replaced using “Mean”

7. Data Types of each of the attributes were found
 
8.“Holiday”, “dteday” attributes were of bool and datetime, rest attributes were either integer or float

Maximum Registered users on Non Holiday utilizes the service as per pivot Table

Concatenation Approaches

1. Vertical concatenation leads to 610 rows and 32 columns 
 
2. Horizontal concatenation leads to 1000 rows and 16 columns 

 Vertical concatenation with huge null values and duplicate columns, 
 
Horizontal concatenation leads to no null  and duplicates, hence horizontal approach selected

Scenario Interpretation and Conclusion 

  1. Post concatenation and outlier treatment, the upper and lower caps have been defined for each of the attributes 
  
2. Maximum hrs spent by casual users can be converted to Registered

3. Less hrs(less than median hrs 12hr) spent by Registered users need to be approached and motivated for spending more hrs in ride

4. More than 12 hrs spent registered users need to be approached for testimonials and their utility under different conditions need to be understood

5. Under the median temperature range between 0.16 to .24 maximum registered users go for a ride











