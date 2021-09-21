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
