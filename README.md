![header](../master/header.png)

# 2018 Kaggle Machine Learning & Data Science Survey Analysis

Starting from 2017 Kaggle conducts global Data Science and Machine Learning survey among data professions, with an intention to establish a comprehensive view of the state of the field.

By taking advantage of Kaggle survey data, this analysis aims at concentrating on a particular subgroup of respondents – professionals with undergraduate major in business discipline, who changed or in the proses of changing their career into Data Science/Data Analytics and comparing them with professionals coming from other backgrounds. In context of this analysis respondents coming from Business background are simply called “switchers” and the rest “others”. 

Major research question is how different the switchers are from others. There are the following objectives:
1.	To establish a view of what is going on in the Data Scientist field.
2.	In particular, compare respondents coming from Business discipline with others 

This analysis was also made over Kaggle kernel. See link [here](https://www.kaggle.com/hasanlianar/switchers-from-business-discipline-vs-others)

### About Survey  

Kaggle launched 2018 survey in October for one week and dataset was made public in November. Consequently, it is a recent survey and its data have been available for short period of time. According to Kaggle this industry-wide survey presents a comprehensive view of the state of data science and machine learning. Survey received 23859 respondents (49% increase over 2017) from 147 countries. Country receiving less than 50 responses was grouped under “Other”. Survey touched such areas as education, learning sources, career, skills, technologies, programming languages, data types, as well as, state of Machine Learning. Respondents were primarily found from Kaggle channels, emails, forums and social media. 

There were two types of questions - multiple choice and free form (where people could submit their desired answer). To protect the respondent privacy, the answers to multiple choice questions were separated into a separate data file from the open-ended responses.

# Conslusions from analysis

The analysis performed has been very insightful and helped demonstrate current status of Data Science and Machine Learning as well as, reveal some vital differences between switchers and others. As a result of our study key findings can be summarized as following:
-	Most respondents are from US, India and China. US have the highest number of people switching from business discipline to data science/data analytics.
-	Switchers are less confident to call themselves “data scientists” than others.
-	Community is dominated by males, who are mostly younger than 30 years.
-	Both switchers and others are highly educated – more than half have secondary degree.
-	Many of respondents, including switchers, who primarily work in Accounting/Finance industry, have up to 3 year of experience.
-	Many are hesitant to share their compensation. About one fourth of respondents earn below USD 10000 yearly, half of which are students.
-	Switchers are generally busy with data analysis, using JupyterLab, RStudio and Spreadsheets as primary tools.
-	Python is dominating programming language. Switchers also use R and SQL more frequently than others.
-	About one third of respondents don’t use any hosted notebooks, preferring to work locally.
-	Compared to others switchers spend less time coding.
-	Half of respondents can explain Machine Learning model, though one third consider the models as black-boxes.
-	Matplotlib and ggplot2 are wide-spread Data Visualization libraries. Switchers prefer both libraries equally.
-	Switchers commonly use Numerical, Tabular and Time Series Data. Data Scientists are generally busy with Tabular Data, Software Engineers Text. Data, Data Analysts and Students with Numerical Data.
-	All respondents rely mainly on Coursera as a most popular online learning platform.

# Future Work

This analysis has not covered all questions asked in the survey. Respondents were also asked about such areas as:
-	Fairness and bias in ML algorithms, 
-	ML model interpretation, 
-	Cloud computing
-	Databases
-	Big-data products
-	Public datasets
-	Work reuse/reproduction

Future analysis can incorporate above-mentioned question responses to establish a broader view of the status of Data Science field and have a better observation on differences between respondents coming from business discipline against others.

Analysis could further be enriched by using 2017 survey data (or additional external datasets) to find out and explain trends in specific areas. 

Moreover, we can expand the switchers category by including not only respondents with business undergraduate major, but also professionals with other backgrounds, who can be also be considered as switchers. Traditionally people engaged in Data Science have backgrounds in Computer Science, Engineering or Mathematics/Statistics. Taking this into account, we could categorize all respondents with a background other than Computer Science and Engineering, as switchers.

Finally, since survey dataset includes various questions (features), simple machine learning models can be built to find hidden patterns (for example, who truly data scientist are, what are motivation of switchers or what determines data scientist salaries).
