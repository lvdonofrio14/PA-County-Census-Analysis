# PA-County-Census-Analysis
- Within this project, I take in data from Google's BigQuery Public Data and extract a table called 'census_bureau_acs.county_2018_5yr'.
- From there I answer a series of questions regarding population, poverty, and age within the Counties of Pennsylvania through the use of data analysis and visualization. 

## Question 1:
#### According to this data, what is the total population of PA?  What do you observe about how population is distributed across counties in PA?  
    - The total population of PA: 12,791,181.0
    - There are three major counties that make up over 28% of the population while the majority of counties are rather small
![PA pop by county](https://user-images.githubusercontent.com/78940231/139791433-f47b3963-ae18-4646-a1c8-4186334a89fc.png)

## Question 2:
#### What is the average poverty rate in PA?  Poverty rate is the number of people in poverty over the total population.
    - The average poverty rate in PA is 12%

## Question 3:
#### How many Pennsylvanians live in counties where the poverty is higher than the state average?
    - The number of Pennsylvanian's living in counties where poverty is above the state average: 5,418,448.0
    
## Question 4:
#### Is the poverty rate in PA consistent across all counties or is there variation? Provide a visualization to explain your answer.
    - There appears to be relatively consistent poverty rates with only one major outlier that also happens to be PA's most populated county. There is a low standard deviation of .03 which suggests that most of the data is clustered around the mean and relatively consistent.
![poverty to pop](https://user-images.githubusercontent.com/78940231/139791715-148988d5-863e-4b0f-90bf-7f8238307eeb.png)
![poverty rate by county](https://user-images.githubusercontent.com/78940231/139791746-b9953490-cf31-4562-acc1-a1df12df25ad.png)
![poverty rate box plot](https://user-images.githubusercontent.com/78940231/139791757-c828f31b-5ea3-42b5-b3ca-16ab32562047.png)

## Question 5:
#### Does there seem to be any relationship between a county’s poverty rate and the percent of population that is over 65?  Include a visualization in your response.
    - I do not see a relationship between a county's population over 65 and their poverty rate.       Population over 65 and poverty rate had a weaker correlation (.0016) than that of total population and poverty rate (.0788)
![corr](https://user-images.githubusercontent.com/78940231/139792922-2a307e96-6855-4dbe-a038-56956e80734d.png)
![pop over 65 poverty rate](https://user-images.githubusercontent.com/78940231/139792744-fa56d5b9-927c-466d-b45d-293cd8715332.png)
![total pop poverty rate](https://user-images.githubusercontent.com/78940231/139791876-af91e568-73f7-4748-8c2c-960888518a51.png)

## Question 6:
#### How many households are on public assistance or food stamps in PA?
     - Number of households on public assistance/food stamps in PA: 700,759.0
     - Percent of households on public assistance/food stamps in PA: %13.67

## Question 7:
#### In looking at the county level data for poverty and for public assistance/food stamps, are there any counties where there might be a large ‘gap’, meaning that county has more people in poverty who have not enrolled in benefits, compared to other counties?  What assumptions do you need to make to answer this question?
### (NOTE: Generally people qualify for public assistance or food stamps at or below 185% of the poverty line. )
    -Assuming everyone within the 'Poverty' column qualifies for assistance this is the results. County #42027 has the lowest usage rate by far of 16.5%. From there it is a gradual upslope to the highest usage rate of 60.9% from county #42073. It is clear that some counties are not maximizing the possible assistance that is available to them.
![people in poverty vs assistance being used](https://user-images.githubusercontent.com/78940231/139792108-e2f8f9a2-e963-440d-a346-4106ae3e8872.png)
![20 lowest usage rates per county](https://user-images.githubusercontent.com/78940231/139792115-14450537-9f3b-4f19-97d8-444745191ed5.png)








