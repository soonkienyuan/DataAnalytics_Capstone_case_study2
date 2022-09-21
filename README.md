# 'Google Data Analytics Capstone : How Can a Wellness Technology Company Play It Smart?'

This is the Googel Google Data Analytics Professional certificate Capstone project. I will  ask questions, prepare, process, analyze, visualize and act on the data from the scenario.

## Google's Data Analysis Proccess 

Google suggest  that the data analyisis proccess consist of 6 phase which are ask, prepare, process, analyze, visualize and act.

![Image](https://github.com/soonkienyuan/DataAnalytics_Capstone_case_study2/blob/main/Image/data_analysis_step.jpg?raw=true)

## Scenario

I'm a junior data analyst at women's health company Bellabeat. Bellabeat is a small, successful smart device startup. Urka Sren, Bellabeat's founder and CCO, thinks smart device fitness data could help the company grow. I'm studying smart device data for a Bellabeat product to learn how consumers use them. The insights will shape marketing strategy. I'll give Bellabeat's management my findings and recommendations.

## Abouth the company

Sren and Mur formed Bellabeat. Sren used her artistic skills to encourage women globally. Bellabeat collects data on movement, sleep, stress, and reproductive health. Bellabeat is a tech-driven women's wellness company founded in 2013. 2016 saw Bellabeat offices and products. In addition to their website, more online shops sell Bellabeat products. The company invests in radio, billboards, print, TV, and internet marketing.


## Datasets
This case study utilises FitBit Fitness Tracker Data that is publicly accessible on Kaggle. The dataset was collected based on the responses of thirty individuals who participated in a distributed survey conducted by Amazon Mechanical Turk between December 3 and December 5, 2016. 

Although there are 18 datasets, I was only able to use 5 of them for this case study.

## The report

The report is written in R markdown, with R code, markdown, visualisations, and tables contained within the document.

The report will describe the comprehensive and detailed approach to solving the issue, as well as your analysis and findings.

### A fascinating report section
### Data credibility

**ROCC** will be applied to detect if there are data credibility issues.

1.  **Reliabile**

    It is **less reliable**. The dataset is comprised of 30 Fitbit users, which is insufficient to represent the eight million active users in 2016. This would result in a margin of error of 23.56% with a confidence level of 95%, which is less reliable based on [margin error calculator](https://github.com/soonkienyuan/DataAnalytics_Capstone_case_study2/blob/main/Margin%20of%20Error%20Calculator.xlsx) .

    Central Limit Theorem (CLT) says that 30 is the smallest number of samples that can be used. The dataset is still valid based on CLT.

    However, it depends on the stakes. Larger samples are needed for reliable results.

2.  **Original:**

    It is **not original**. The data set was produced by Amazon Mechanical Turk responders to a distributed survey, which is considered as third party data. It would have been preferable if FitBit had delivered the data directly.

3.  **Comprehensive**:

    It does not cover every comprehensive aspect. The data are insufficient because they are lacking certain information (e.g., sex, age, genetic disease) that would assist in producing a more precise analysis. As a result, they cannot be considered comprehensive.

    And yet again, the information was gathered over a span of two months, which is insufficient. It is preferable to have data covering a period of at least a year.

    Last, How did they chose thirty people at random? Which strategy they implement? Does it come from a sample that was picked at random and from a place that was chosen at random as well?

4.  **Current**

    It is **not current.**The data was collected between December 3 and December 5 of 2016, which is now a total of six years ago.

5.  **Cited:**

    It is **Cited**. The datasets were generated by respondents to a distributed survey via Amazon Mechanical Turk.



## Findings and conclusion

### Revisiting Business Task

The business task will be associated with a non-Bellabeat smart devices and analyze the smart device usage data in order to gain insight into how people are already using their smart devices.Then, using the data, generate recommendations for the Bellabeat marketing strategy team to understand the trends. These recommendations and trend insights will be used to enhance the features, functionality, and service quality of the Bellabeat app. So, the business task can be summed up as follows:

1.  Analyze the non-Bellabeat smart device usage data in order to gain insight to help Bellabeat marketing strategy team to understand the trends.

2.  Utilizing the trends and insights provided by smart device usage data in order to improve the features, functionality, and overall service quality of the Bellabeat app


### Trends Identified

1. The longer a user spends on Sedentary activities, the less probable it is that they would engage in physical activity.

2. The longer a user walks, the greater the chance that they will have a caloric deficit.

3. Total time in bed seems positively related to total time asleep.

4. Average user spends 79% of a time for Sedentary,Very active and fairly active only make up 2% of the entire time. Lightly active make up of 19% of the total time. 

5. The participants averaged 25.19 BMI, which is overweight.

6. On average, participants slept less than 8 hours.


### Recommendations

####  Complete Reward System

- A system of rewards should be devised to recognise people who have done well.in an effort to entice a client

- Reward should be given to those who attain various levels depending on the number of daily steps taken.

- In order to advance to the next level, the user must maintain a certain level of activity for a certain amount of time (a month or a week). For each level, user would get a certain number of points redeemable for Bellabeat items or discounts on other Bellabeat products.

- This strategy will indirectly promote and raise sales of the other Bellabeat product line while also enhancing its reputation in the marketplace.

#### Social Media Contest

- In exchange for prizes and incentives, a social media contest encourages interaction, followers, leads, or brand exposure.

-   Reward may give to the followers for liking, commenting, and sharing Bellabeat product content (facebook page, instagram, tiktok, Youtube and so on). This increases your brand's reach and buzz.

- Like/share/comment to win a Bellabeat product

- Creative video contests or Photo contest to win a Bellabeat product


#### In-App competition and rankings

- Bellabeat could enable in-app tournaments against friends or users in the same city/state to encourage physical activities engagement.

- Make an animated and creative total steps ranking page for users in the same city or state to get them to be more active and spend less time sitting (sedentary time).

#### Notification and Sleep time

- Participants slept less than 8 hours on average, therefore Notification and Sleep Time should be a major issue.

- Total time in bed is positively correlated with total time asleep, according to our results. They could set a bedtime and receive a reminder minutes before. Breathing advice, podcasts with relaxing music, and sleep techniques can help customers sleep.

- Bellabeat should therefore create a system that includes sleep guidance, heart rate monitoring while sleeping, and a sleep reminder in order to improve the user's quality of sleep.

### Future Works

- Larger, more representative sample size (with 95% confidence and 5% margin of error).

- Random with no prejudice in selection.

- At least 1 year should be spent collecting data.

- More about the person's age, sex, height, etc.

- More recent and current information or anything from the previous year is suggested. 

- Have an original (First Party Data) data source, or verify primary/secondary data for integrity and trustworthiness.



