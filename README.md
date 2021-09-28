# An Analysis of Kickstarter Campaigns
This time we worked with a dataset consisting of more than 4,000 crowdfunding projects, with the goal of helping Louise to determine if there are specific conditions on each project or category of them, that makes a funding campaigning successfull. Since she is interested in founding a play called "Fever", with a budget over $ 10,000 USD, and of course she pretends to be successful in her path over the fundraising.

## The Big Picture

At a glance, we could see that over all the different parent categories of crowdfunding, theather has a good proportion of successfull projects, having 839 from the total of 1393, as it showns in the follow image:

![Parent Category Outcomes](https://user-images.githubusercontent.com/90433064/134116712-e0eb1093-16f5-4a2f-9a33-f5be396cb3ea.png)

### 1. Influence of the origin

So then we can take a shortcut for the next conclusion, and get focus on analyzing the places where these crowdfunding projects have more numbers of successfull theater projects, finding that from the total successfull of that category 839, 525 had their origin on US. And from the total teather crowdfunding (912) that were origined on US, 58% were successfull. So we could say that US would be a good place to set a theater crowdfunding. Let´s take a look at the next image:

![image](https://user-images.githubusercontent.com/90433064/134119210-dc10fc88-1634-4b39-9ff9-b52cf3042bbe.png)

### 2. Influence of the timing

It would be accurate to determine if there is a pattern of successful on the launch date for a crowdfunding campaign:

![Timing Success](https://user-images.githubusercontent.com/90433064/134120071-21860611-8ff2-4d55-95b4-4e98fa33313a.png)

Seems that May would be the first option to launch a crowdfunding campaign, followed by June and July. But actually for more specific details, we run as well, the graphic for visualizing only the theater projects; and the result wasn't too diferent, having the same months of best performances for the successfull campaigns. Nevertheless, we cannot take aside the probability of failing on those same months, represented by an average of 33% of failure from the total theater campaings. 

![Timing Success_Theater](https://user-images.githubusercontent.com/90433064/134121570-6ba0c135-9d7c-44ef-9019-269dba33dc64.png)

## Following the inspiration

But is this information, enough conclusion for Louise or do we need to go further to help her take the decision? At the end of all, Louise has been inspired by five plays she saw in GB, and she got interested in how they had been funded. These are the plays she got inspired by: 

  -Be Prepared
  
  -Checkpoint 22
  
  -Cutting Off Kate Bush
  
  -Jestia and Raedon
  
  -The Hitchhiker's Guide to the Family. 
  
  
### Next step, finding any possible pattern in the data related to those plays that inspired Louise. 

We found out, that all of them reached their campaing goals; but their goals didn't exceed the $4000 USD. And in addition to this conclusion, we could get back to the big picture and compaire the goal's media for successfull campaings in US, and those that failed in the same country; we could see that the ones that failed had almost twice the goal versus those that succeed. Therefore, Louise probably has to start to rethinking her budget for the play.

## Future plans

Finally, while Louise has already took her decision in creating her play in US; she's planning into do a research for a musical in GB, with a budget of 4000 GBP. 

![GB MUSICAL IQR](https://user-images.githubusercontent.com/90433064/134128316-ee14c2ba-64cd-4b91-8485-5128c29baf8d.png)

We can see that the mean of the campaigns's goal is around 4000 GBP, but that amound exceed actually the outliers of the pledged amount. But on the other side, since we noticed that the median of the goal is 2000 GBP and that number is just over the 3rd quartile for amounts pleadged, seems to be a better idea for Louise to take into consideration determine something around 2000 GBP as the budget for her next project.

# Kickstarting with Excel

## Overview of Project

A few months later, Louise came close to finally accomplishing her goal for _Fever_, actually it took her less time than she thought; so now she would like to receive some advices regarding the relation between te different campaings and their lauch dates and their founding goals as well.

In order for us to do that, we will need to visualize the outcomes of the campaigns based on the variables that Louise is interested to. 

## Analysis and Challenges

So then the first step to help Louise will be, creating a pivot table with the information that we found as successful, failed and canceled for theater campaings, distribuited on the months of the year, based on their lauch date; for the purpouse of encountering some patterns that would prevent Louise from taking bad choices on the timing to launch her next play.  

![Pivot table Lauch date](https://user-images.githubusercontent.com/90433064/135013401-d1cd462c-ac2a-48dd-9510-7403923239af.png)

As second step, we should prepare an analysis based on the data that we have from the plays that turn out successful and we will take a look deeper over the different ranges of goals established for those campaings. Therefore we will need to create a worksheet that contains the outcomes for that analysis, so we will use the formula IFSCOUNT (spanishexcelversion = CONTAR.SI.CONJUNTO) for each outcome, as it showns on the next image:

![Outcomes for S_F_C plays](https://user-images.githubusercontent.com/90433064/135014317-58b01f2d-4a0b-4898-8ce4-fb259f8bf663.png)

### Analysis of Outcomes Based on Launch Date

Once we have create the pivot table, it would be necessary, to show the results in a way that Louise would be able to see at a glance the behavior of the outcome of the campaings over each month of year. Having this next image as result of our analysis:

![Theater_Outcomes_vs_Launch](https://user-images.githubusercontent.com/90433064/135016431-c00ad725-eca3-4589-95cb-80f338fcfd00.png)

Therefore we can determine, as we have seen previously, that May seems to be the prefered month to launch a theater foundrising campaing; and probably it is this way, since the number of successful campaings goes up on that month as well, follows by June and July. So then we can state that 2 out of every 3 theater campaings launch during these three months (May, June and July), get success.   

![May_June_July to lauch a theater campaing](https://user-images.githubusercontent.com/90433064/135017940-1c07440e-4e1d-4c0d-957f-2b4701a7caa8.png)

### Analysis of Outcomes Based on Goals

In the second analysis we could see how the results behaved differently range to range of the amount of each goal. Even thought, the successful and failed campaings decreases while their correspondant range of goal increases, we have to look carefully, and see more details on each row, to have a better explanation for this behavior.  

For all that, we add some other formulas to our analysis, such as the sum of the projects related to each range of goal and the proportion of each outcome versus the total projects from the same range of goal. After this, we can see clearly, that the range that has better chances of success is the one that established less than 1000 as their goal; having into account that 76% of the total projects were successful, versus the 24% that failed. 

![Ranges of Goal](https://user-images.githubusercontent.com/90433064/135020503-da1a124e-6c32-47e1-a14f-068ce8198594.png)

### Challenges and Difficulties Encountered

Good new! This last analysis, has a manual way to verify if the result on the formula is correct, by applying filters to the Kickstarter database. Otherwise I might was about to give a wrong advice to Louise based on a wrong formula. Since, on the range that establishes "Greater than 5000" I was indeed taking out of the equation the "5000", so that gave me a different result by 4 Failed projects on this range. In this case, the difference in the result might not be enough to be considered, but it would be a wrong result for having the analysis completed. 

## Results

- What are two conclusions you can draw about the Outcomes based on Launch Date?
  
  - Louise should consider to launch her next theater campaing during the months of May, June or July, and preferably during May. 
  
  - And defenitly Louise should avoid to launch it during the months of December, October or August, in that order. Since they are the months with most probabilities to fail. 
  See next image:
  
  ![Avoid launch on_](https://user-images.githubusercontent.com/90433064/135022384-467864a0-e4a6-4c1f-97ce-e3644e7f3061.png)

- What can you conclude about the Outcomes based on Goals?
  
  - Louise should take into account that an amount around 1000 to 4999 to set as goal, would have good chances to succed. Otherwise the chances to reach the goal, would decrease as increase her goal. 
  - The range that has the worst chances to succed, it would be from 45000 to 49999

- What are some limitations of this dataset?

  - One important thing that I think we should fix before give an official advice to Louise, or at least, to give her this information as well; It's that the currency for the ranges could be different, since we are analyzing theater campaings from different parts of the world, so I suggest standardise the currency to US Dollar, since is internationally known; and it would be a best reference setting those ranges of goals, all in US Dollars, so then Louise could take better decisions about the details for her next theater fundraising campaing. 
 
- What are some other possible tables and/or graphs that we could create?
 
  - We could create a table to show the posible pattern between the outcomes and the campaing duration. 
  
  - We could assign the correspondant exchange rate to stardardise the currency and then update the worksheet for the analysis based on goal's range.  
