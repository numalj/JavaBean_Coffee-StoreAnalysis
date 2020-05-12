# Where to open the next JavaBean?

JavaBean is an up and coming coffee chain that is very similar to Starbucks. JavaBean is trying to decide which zip codes it should focus on to open up new shops in the near future. As a competitor of Starbucks, JavaBean has a very similar customer base.

As part of this project, I will look into current locations of Starbucks, and then use a Logistic Regression model to try and find zip codes that currently don't have a Starbucks, but have a potential customer base that would be suitable for a Starbucks/JavaBean.

## Mapping out the locations

Below I've maped out current locations of Starbucks in the dataset just to get a sense of how they are located across the US. 

![StarbucksMap](/images/starbucksMap.png)

## Starbucks Customer Demographics

Using census and demographic data, I created boxplots to help compare the differences between zip codes that have one or more Starbucks and zip codes that don't.

![StarbucksMap](/images/demographicsBefore.png)

As we can see, the results are what we might have already expected. Starbucks are found in zip codes with younger working individuals who are educated and have a higher income. 

## Building the Model (In progress)

Next I'll build a logistic regression module to get the model to predict where a starbucks should be located. Then by looking at zipcodes with highest probability to have a starbucks location but currently don't we can decide where to set up the next JavaBean.

**Currently in Progress: To be continued.....**
