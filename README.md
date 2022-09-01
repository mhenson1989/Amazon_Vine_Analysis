# Amazon_Vine_Analysis

## **Overview**
The purpose of this analysis was review a database of Amazon reviews, extract, transform and load the database using Amazon RDS, as well as assess the data based on Vine Reviews. For my analysis, I looked specifically at Book Reviews. 

## **Results**
**1. How many Vine reviews and non-Vine reviews were there?**
Interestingly, when analyzing the Book Reviews dataset, I found that when refining my data set down to only reviews with twenty(20) votes or more and utilizing the criteria of 50% helpful votes, there were no Vine reviews. Therefore all reviews in the dataframe are non-Vine reviews. A snapshot of the two dataframes (Vine reviews and non-Vine reviews) is shown below. 

!["Vine Reviews"](https://github.com/mhenson1989/Amazon_Vine_Analysis/blob/main/Images/VineDF.PNG)

**2. How many Vine reviews were 5-stars? How many non-Vine reviews were 5-stars** 
Since my data analysis produced no Vine reviews, the number of 5-star reviews is. The number of non-Vine reviews was 242,889. A snapshot of the review count is shown below. 

!["Review Count"](https://github.com/mhenson1989/Amazon_Vine_Analysis/blob/main/Images/Count5Star.PNG)

**3. What Percentage of Vine reviews were 5 stars? What percentage of non-Vine reviews were 5 stars?** 
Again, within this analysis, since it yielded no Vine reviews, the percentage of Vine reviews came out to 0%, and therefore the percentage of non-Vine reviews was 100%. See the snapshot below for the calculations used. 

!["Percentage"](https://github.com/mhenson1989/Amazon_Vine_Analysis/blob/main/Images/Percent5Star.PNG)


## **Summary**

For this analysis, one can conclude with 100% certainty that the Book Reviews are unbiased, as 100% of the reviews were unpaid. As an alternative analysis, I might consider my filtered dataset to deduce if my filters were too narrow for the analysis, or consider a larger overall dataset to be able to see a contrast between Vine and Non-Vine reviews. Overall, however, it is unlikely that the book reviews show bias. 

