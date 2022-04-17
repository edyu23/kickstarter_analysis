# kickstarter_analysis
Analysis of Kickstarter Campaigns

## **Overview of Project**

 	The purpose of this analysis is to look at kickstarter data to get information on successful and unsucessful kickstarter campaigns. Specifically, this report will focus on outcomes based on launch dates as well as outcomes in the theater category.
  
## **Analysis and Challenges**
 
 ### Analysis of Outcomes Based on Launch Date
 
 	In this analysis I created a pivot table for all years under the theater category broken down by months and whether they were successful, failed, or canceled. I also generated a line chart found below that illustrates the number of said outcomes based on the respective launch date of each campaign.
 
 ![This is an image](https://github.com/edyu23/kickstarter_analysis/blob/19dfaf361c5e3bea30a46da521402eace838fdce/Resources/Outcomes_vs_goals.png)
 
 	I didn't run into too many challenges but I could see some issues getting the pivot table to populate properly because of a couple extra steps in the filter to visualize what we are looking for.
 
 ### Analysis of Outcomes Based on Goals
 
  	In this analysis we made a worksheet with eight columns with a focus on theater. In one column we look at goals broken down with into twelve rows of cells with a range of under $1000 to over $50,000. We use the `COUNTIFS` function to pull the number of successful, failed, and canceled projects from our kickstarter worksheet. We then we the `SUM` function to tally up the total successful, failed, and canceled projects. This information taken to see the percentage of successful, failed, and canceled campaigns. 
  We utilize the worksheet that we made and generated a line chart illustrating the percentages of outcomes based on the goal amount as seen below.
  
![this is an image](https://github.com/edyu23/kickstarter_analysis/blob/19dfaf361c5e3bea30a46da521402eace838fdce/Resources/Theater_Outcomes_vs_Launch.png)
  
  I had some trouble getting used to the `COUNTIFS` function and getting the syntax down to populate the correct data.
  
  ## **Results**
  
  ### Conclusions
    
   ###### **Outcomes Based on Launch Date**
      -May and June are popular months to launch a successful kickstarter.
      -The least amount of successful kickstarters are launched in the months of November and December.
   ###### **Outcomes Based on Goals**
      -Kickstarter goals that are less than $5000 have the highest success rate.
      -Kickstarters that are equal or greater than $45000 have the least successful percentage.
   ###### **Limitations of Dataset**
      -The sample size of projects great or equal than $15000 is very small which limits the usefulness of said range.
   ###### **Other Possible Tables or Graphs**
      -We can do the same outcomes based on launch date and outcomes based on goals for specific countries of interest to see how successful one is compared to another and the goals that they set for themselves.
      -We can make a bar chart comparing the amount of successful and failed campaigns amongst countries.
      
