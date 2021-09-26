# School_District_Analysis
School District Analysis Jupyter Notebook
Overview of the school district analysis: Explain the purpose of this analysis.

After our initial analysis we prepared for Maria, the School Board found that there was “academic dishonesty” in the csv file we produced our analysis from for their teams. In the news shared with Maria and her Supervisors, it was identified that there was specific dishonesty in the ninth grade reading and math scores for Thomas High School. It is our job to support the School Board in maintaining the testing standards of the state and we will be assisting Maria in reevaluating the testing data. We first must replace the math and reading scores for the nineth grade students at Thomas High School because it was discovered that those scores have been altered.

For our task in assisting Maria and the School Board in upholding the integrity of the state testing standards we will place NANs in the reading and math scores for the nineth grade students at Thomas High School. We will not change the rest of the scores for the schools or students in the district, we must make sure we do not incorrectly alter the scores of students with accurate test scores. After we have safely updated the dishonestly altered scores, we will repeat the school district analysis previously performed for Maria and the School Board. Our final output will be a report to describe how these changes affected the overall analysis.

_____________
# Our Task

* The district summary

* The school summary

* The top 5 performing schools, based on the overall passing rate

* The bottom 5 performing schools, based on the overall passing rate

* The average math score for each grade level from each school

* The average reading score for each grade level from each school

* The scores by school spending per student, by school size, and by school type

# Results:

# How is the district summary affected

In our Summary we will look at the difference between All Schools against our new summary that excludes the Thomas High School 9th graders.  Below you will see that when we removed the Thomas High School 9th grade scores the Average Math Score dropped which decreases the Overall Percentage Math Score as a whole. This also decreases the Percentage Overall Passing from %65 to %64.9. 


## District Summary All Schools


<img width="473" alt="District_Summary_All" src="https://user-images.githubusercontent.com/88467263/134825258-8664341c-aaf3-4345-a192-42dbd316b7c6.PNG">


## District Summary Excluding THS 9th Grade Schools

<img width="477" alt="District_Summary_without_THS9th" src="https://user-images.githubusercontent.com/88467263/134825270-59839d6f-7c0d-41f0-8ea7-976325dd1b66.PNG">

## Thomas High School Summary with 9th Graders
<img width="210" alt="THS_Summary_with9th" src="https://user-images.githubusercontent.com/88467263/134825275-5ba5f798-0dd4-4597-8845-4cd0ebe53d17.PNG">

## Thomas High School Summary without 9th Graders

<img width="164" alt="THS_Summary_without9th" src="https://user-images.githubusercontent.com/88467263/134825285-c6fbacde-d0fe-4fb0-9322-4aaa8f81ebfb.PNG">


# Replaced Scores Thomas High School’s performance relative to the other schools?

Below you see that before removing Thomas High School 9th graders dropped the Percentage Passing Math from 93.27 to 93.18. The Percentage Passing Reading for Thomas High School decreased from 97.3 to 97.0. These drops decreased the Overall Passing Percentage for Thomas High School from 90.94 to 90.63. Removing the 9th grader score also decreased Thomas High School standings among schools’ districts across the board. There is a percentage decrease in 0.085 for Thomas High School overall due to the dishonesty which is negatively impactful overall for its district. 


## District Summary with Thomas High School 9th Graders

<img width="364" alt="District_Summary_ALL_Schools" src="https://user-images.githubusercontent.com/88467263/134825295-e0e165d5-223c-4cee-8d5f-63a57297f980.PNG">



## District Summary Without Thomas High School 9th Graders

<img width="492" alt="District_Summary_without9thTHS" src="https://user-images.githubusercontent.com/88467263/134825305-75953279-e93e-4087-9f66-c08230c06a8d.PNG">



# How does replacing the ninth-grade scores affect the following:

The last portion of the School District Summary reevaluation includes reviewing the math and reading scores by grade. 

# Math and reading scores by grade


## Math Scores by Grades Below

* Left Shows Math Grades without Thomas High School 9th Graders

<img width="534" alt="Math_Scores_Grades" src="https://user-images.githubusercontent.com/88467263/134825312-fe9e3f28-4432-4e9e-8c0e-e9c286d169d0.PNG">


* Left Shows Reading Grades without Thomas High School 9th Graders

<img width="574" alt="with_without_reading" src="https://user-images.githubusercontent.com/88467263/134825326-b9fe12c6-8323-4322-a7a7-ec6f88d77233.PNG">



## Scores by school spending

* Below Bottom Screen Shot Shows Spending Without Thomas High School 9th Graders

<img width="429" alt="spenidng_with_without" src="https://user-images.githubusercontent.com/88467263/134825343-e6e4f57d-f742-4ab9-9093-040b85bb933d.PNG">


## Scores by school size

<img width="443" alt="size_with_without" src="https://user-images.githubusercontent.com/88467263/134825348-0773028e-3df5-430e-9abc-6f5752798be7.PNG">


## Scores by school type

<img width="472" alt="type_with_without" src="https://user-images.githubusercontent.com/88467263/134825353-bad67d59-f6e4-4211-9f2e-2e64a522d2d8.PNG">


Summary: My summary after making the changes and reviewing the initial data against the new data I find it difficult to make a claim that there was academic dishonesty. For Thomas High School alone the summary of their performance before and after removing the 9th graders had a small impact. I believe that because there is such a large set of data in the initial summary, removing the 9th graders from one school makes a smaller change on the larger dataset. When looking at the data after removing the 9th graders from Thomas High School scores, I see very small changes in reading and math scores and their percentages. 


