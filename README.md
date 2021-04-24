# An Analysis of Kickstarter Campaigns
Performing analysis on Kickstarter data to uncover trends
# Kickstarting with Excel

## **Overview of Project**
   Louise recently came close to her fundraising goal for her play "Fever" in a short period of time.
   
### Purpose
    Louise wants to see how the different campaigns fared in relation to their launch dates and funding goals. 
    The data used for the analysis is the Kickstarter dataset given to us. 

## **Analysis and Challenges**

### Analysis of Outcomes Based on Launch Date
    The analysis based on launch dates was conducted on the monthly dataset for the parent category "Theater" across the years given in the dataset.
        
    Based on the chart above the following analysis can be drawn
    - The month of May has the highest successful outcomes; likewise the month of Dec has the least successful outcomes
    - The failed outcomes are more than the successful outcomes only in the month of Dec  
    - The likelyhood of the campaign getting cancelled as compared to being successful or failed is very low based on the outcomes
    
### Analysis of Outcomes Based on Goals
    The analysis based on goals was conducted on the dataset for subcategory "plays" of the Kickstarter datatset
    
    Based on the chart above the following analysis can be drawn
    - Percentage of number of successful plays is higher than the number of failed plays when the goal range is less than a $ 1000 to $ 14999 and between $ 35000 to $ 44999
    - There are no cancelled projects in the given dataset for the ranges specified
    - There are only two outcomes for the given dataset which either successful or failed

### Challenges and Difficulties Encountered
   
    Following challenges for the analysis of outcomes based on goals
    - The lower range of goal of less than $ 1000 is a bit misleading as in real life you need to have a minimum goal in terms of $$ in order to kickstart a fund raiser. For      example if you have a goal of zero $$ there would be no projects at all.
    - One of the ranges does not include goal of $ 50000 which in the data set has 4 failed outcomes
    - The dataset has an outcome as "live" which is not condsidered for analysis. We would have to define "live" as "successful" with logic that the play would be live only if the a certain goal is reached. The definition should be clearly set out before doing the analysis.
    - The total outcomes for "plays" are 1066 but since we have considered only 2 outcomes and excluded one of the goal ranges (equal to $50000) there are only 1043 outcomes.   
    
## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  - The two conclusion that can be drawn about the Outcomes based on Launch Dates are :-
    - May is the month which would likely have a successful outcome if the campaign is launched in the month of May. 
    - Dec is the month which would likely have a failed outcome if the campaign is launched in the month of Dec.
    - What can you conclude about the Outcomes based on Goals?
    
  - The conclusion that can be drawn about the Outcomes based on Goals are :-
    - If you wish to have a likely successful outcome, the campaign goal has to be less than $ 15000 or should be between $ 35000 to $ 44999	
  
- What are some limitations of this dataset?
   - The data considers outcomes for various countries. Naturally the currency exchange rates plays a huge role in determining the goal and the pledge figures. The numbers may or may not be comparable.
   - Louise came close to the fundraising campaign goal for her play "Fever". Play is a sub category in the given dataset. Whereas the analysis done is for the parent category "Theater" which has other sub categories.This isn't an apple to apple comparison. A better dataset for the analysis would have been for subcategory "plays" instead of parent category "theater".

- What are some other possible tables and/or graphs that we could create?
  - Instead of outcomes based on goals a similar analysis should be done on outcomes based on pledged to understand the relation between the goal amount and the pledged amount to the outcomes and see if there are some patterns to find a plausible conclusion
  - The pledged amount is likely related to the number backers. Would be interesting to see the relation between outcomes, no of backers and the pledged amounts.
