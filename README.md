# Sleep Data Analysis Project
This repository has sections specific to questions we had wanted to ask in regards to the data we had found. How might ones job impact their sleep? How much does having a sleep disorder impact how long or how well someone has slept? How might the level of an individuals physical activity cause them to have better or worse sleep? How Sleep quality, duration, stress level varies among Male and Female? 
All these questions are displayed in the files saved here in this repository with analysis alongside those displays and data provided.

## Files and details of analysis
There are 3 files each has different analysis:

#### sleep1 - Analyzes how the Sleep quality, duration, stress level varies among Male and Female.

#### sleepDisorderVsSleep - Analyzes how much does having a sleep disorder impacts how long or how well someone sleeps.

#### SleepHealth - Analyzes the impact of occupation on sleep and how physical activity and other factors affect sleep quality.

##### Analysis of Occupation and Sleep:

The bar charts clearly show that Engineers have the highest average sleep duration and highest average quality of sleep.

![image](https://github.com/TestUser-2022/Project1-SleepDataAnalysis/assets/98562722/59f91d98-b159-4d94-8a01-42a2884c73c4)

![image](https://github.com/TestUser-2022/Project1-SleepDataAnalysis/assets/98562722/9a7fc167-16b6-43ed-8833-7dda479d2bed)

  According to the Bar charts, Sales Representatives, Scientist and Salesperson have lower average sleep duration and average sleep quality. But there were not enough samples for Sales Representatives and Scientist to draw any conclusion. So, moved on to the Salesperson category for more detailed analysis.

While looking at the sleep disorder distribution, it confirms that the Engineers have good sleep. The Pie-chart shows that 90.5% of the Engineers are free of sleep disorders. Only7.9% experience Insomnia and just 1.6% struggle with Sleep Apnea.      

  ![image](https://github.com/TestUser-2022/Project1-SleepDataAnalysis/assets/98562722/6ced450b-8333-452a-a285-657446689747)

  The chart shows that 90.6% of the Salespersons experience Insomnia. Only 6.2% are free of sleep disorders and 3.1% struggle with Sleep Apnea. So, according to the dataset used, Engineers have the best sleep, Salespersons have the lowest.

##### Analysis of Physical Activity Level Vs Sleep Duration and Physical Activity Level Vs Sleep Quality:

Based on Pearson's correlation coefficient (r-value) for both Physical Activity Level Vs Sleep Duration and Physical Activity Level vs Sleep Quality, there is a very week positive correlation between them (r-value of 0.21 and 0.19 respectively).

<img width="553" alt="image" src="https://github.com/TestUser-2022/Project1-SleepDataAnalysis/assets/98562722/3fdba4b6-4e0b-446d-b6a8-363c2872f0f4">


But for both the cases, the pvalue < 0.05 shows significance of Physical Activity Level on Sleep Duration and Sleep Quality respectively. Analyzed further with multiple independent variables and noticed that when Physical Activity level is combined with other factors, it has high R² value and hence high relationship with Quality of Sleep.

When Physical Activity Level, combined with Sleep Duration, Stress Level and Age is analyzed with Quality of Sleep, it has a higher relationship (R² value of 0.89) with Quality of Sleep.


### Dataset Used: Sleep Health and Lifestyle Dataset

https://www.kaggle.com/datasets/uom190346a/sleep-health-and-lifestyle-dataset
