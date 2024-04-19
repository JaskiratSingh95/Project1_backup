# Project1_backup
Backup repositry

Link to the original repo - https://github.com/prez212/Project1-Team6
We had too complicated problems with this repo so we decided to just create a new repo.

# link to pptx. https://docs.google.com/presentation/d/18RPDXQ212UUuZEEoMY39Cp6D9cDfUH2y/edit?usp=drive_link&ouid=108355929733190566863&rtpof=true&sd=true

Team members - Suad Godax, Lucas Perez, Harshh Patel, Jaskirat Singh, Halima Saleh

Approx. size of data>340K
Shape of data - csv
# link to csv file https://drive.google.com/file/d/1I_EWm3oJVCJHiKPN06X1PA1AfMaMIrHj/view?usp=drive_link

Problem Statement:  What are the associatedd risk factors of Heart disease?

Sub Questions:

1) Does age, gender play a role?

2) Does race play a role?

3) Does lifestyle (smoking/drinking) play a factor?

4) Does general/mental/physical health and status play a role?

5) Does sleep time play a role?

6) Does any co-morbidity (asthma, kidney disease, skin cancer, and diabities) play a role?

Conduct a corelational and regression analysis.


# link from kaggle https://www.kaggle.com/datasets/kamilpytlak/personal-key-indicators-of-heart-disease
# link to CDC data descriptor https://www.cdc.gov/brfss/annual_data/2020/pdf/overview-2020-508.pdf


Lucas' role was to tackle: Does age and gender play a role in heart disease?
Data sorted and grouped
Created charts -
https://stackoverflow.com/questions/61130168/stacked-bar-chart-in-matplotlib-how-to-code-with-lots-and-lots-of-categories
https://pandas.pydata.org/pandas-docs/stable/reference/api/pandas.DataFrame.unstack.html
Created summary description
Put together the presentation. https://create.microsoft.com/en-us/template/futuristic-pitch-deck-82ab8cf7-ff25-4ec2-9c52-78be3d98c6ec
Controlled board.


Halima's Role in this project was to find out :
Does Race, General Health, Physical health play role for heart disease?

the data was located in Resources folder heart_2020_cleaned.csv

1, as the data was already cleaned, just planed to use the following columns
•	HeartDisease
•	Race
•	PhysicalHealth
•	GenHealth

2, Tried to calculate
•	Race vs HeartDisease
•	physicalHealth vs HeartDisease
•	GenHealth vs Heart disease

Link for coding from the original CDC data form for Physical Health variable and General Health
https://www.cdc.gov/brfss/annual_data/2020/pdf/codebook20_llcp-v2-508.pdf

3, The result was showing bias because some populations were under represented inoverall sample.  the data was not collected equally 
	So for each total race , physicalHealth, GenHealth tried to calculate the average of each Heartdisease=yes / Total

4, for each (Race , PhysicalHealth, GenHealth) created suitable chart 

5, for each (Race , PhysicalHealth, GenHealth) calculated summary stastics
	That means (Total cases, mean, Median, std)
    
At the end declared my analysis and coming back to the main question:

DOES RACE , PHYSICAL HEALTH, GENERAL HEALTH PLAYS ROLE FOR HAVING HEART DISEASE:

The answer is:
		According to the data group of races we can conclude American Indian/Alaskan Native sample has 10% heart diseases which is the highest.
		(but the population sample is not large enough to verify)

		and Asians 3.3% of the group has heart disease which is the lowest %.

for physical Health analysis we can definitly say that heart disease can be affected by physical health, 
the more you are fit the less you will be affected by heart disease
also general health plays role on heart disease.

	

Harshh's main role in the project - To answer the sub-question: Does sleep time plays a role?

First checked the documentation on the CDC website to understand how the sleep time data was collected.
##REFERENCE: https://www.cdc.gov/brfss/annual_data/2020/pdf/codebook20_llcp-v2-508.pdf (page 23)
Began by checking the distribution of the sleep time data. Plotted a bar chart for this purpose. Based on the chart, decided to get rid of sleep times data which had less than 1% of the total data. The cut-offs are represented with a vline.

Next, calculated the total no. of people, no. of people having heart disease and not having heart disease. Further, I calculated the percentage of the later 2 categories.

Then, plotted a bar chart to visualize the analysis and finally, infered conclusions:
- yes, the duration of sleep does play a role in increasing/decreasing the risk of heart disease.
- as we move from 3hours/day sleep to 7hours/day sleep, the percentage of people having heart disease decreases gradually but as we go from 7hours/day to 12 hours/day, the trend reverses.

- The optimal sleep duration according to this data is about 7hours/day.

- And both insufficient sleep and excessive sleep can result in increase of risk of heart disease. This is backed by many other reports found on the internet. A few links of such reports are mentioned below:
##REFERENCE:
- https://pubmed.ncbi.nlm.nih.gov/27647451/
- https://www.bhf.org.uk/informationsupport/heart-matters-magazine/news/behind-the-headlines/sleep-and-heart-disease



Suad's part of the Project1- team 6 was to find out if lifetyles play a factor in heart disease :
Question: Does Smoking, and Drinking alcohol play in heart disease?
The data was located in Resources folder heart_2020_cleaned.csv
https://www.kaggle.com/code/christophergd/introduction-to-seaborn-heart-attack-data/input?
select=heart.csv
1. as the data was already cleaned, Suad used the following columns to analyze Smoking and 
Alcohol drinking
• HeartDisease
• Smoking
• Dringking alcohol
# Smoking and Heart Disease
2. Suad calculated The total smoker with heart disease
• Smoking vs HeartDisease
• Dringking alcohol
3. The result was showing bias because the majority of the population didn't suffer heart disease 
in the overall sample.
4. Suad Plotted a pie chart for Smokers who had heart disease, Smokers who had no heart 
disease, non smokers who had heart disease, non smokers who had heart disease
# Alcohol Drinking and Heart Disease
5. The result was showing bias because alcohol consumption population was under represented 
in the overall sample.
Thus, Suad calculated total number of Alcohol Drinking and non Alcohol Drinking
6. Plotted a pie chart for Alcohol drinkers who had heart disease, Alcohol drinkers  who had no 
heart disease, Alcohol drinkers  who had heart disease, Alcohol drinkers  who had heart disease
# Conclusion
Smoking Alcohol Drinking contribute immensely to heart disease, from the data, smokers and 
alcohol drinkers who had heart disease were double that of smokers and alcohol drinkers who 
didn't smoke and didn't drink but had heart disease.
It is important to maintain a healthy lifestyle to decrease the chances of suffering from heart 
disease. It is equally as important for people with heart disease reduce their smoking and 
drinking.