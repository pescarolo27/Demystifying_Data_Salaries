# Demystifing Data Salaries (Python)

**Background:** You work for an international HR consultancy helping companies attract and retain top talent in the competitive tech industry. As part of your services, you provide clients with insights into industry salary trends to ensure they remain competitive in hiring and compensation practices. Your team wants to use a data-driven approach to analyse how various factors—such as job role, experience level, remote work, and company size—impact salaries globally. By understanding these trends, you can assist in advising clients on offering competitive packages to attract the best talent.  
In this project competition, which consists of three levels/parts, salary data from thousands of employees worldwide will be explored, mined, & visualized. Later levels of the project will involve building predictive models to uncover key salary drivers and providing insights on how to enhance future data collection.

**The Data:** Available in `salaries.csv`, the data comes from a survey hosted by the aforementioned HR consultancy. Each data point represents a single employee's salary record & other employment details for a given year. It contains over 57,000 survey responses between 2020-2024.

These projects, completed in June, 2025, were part of a three-part competition on _DataCamp_. As such, three files were completed & are included in this repository: _Demystifying Data Salaries - Level 1_, _Demystifying Data Salaries - Level 2_, & _Demystifying Data Salaries - Level 3_. Each file examines different objectives; the first two use standard analytical techniques & the last uses machine learning algorithms. Given this & the length of the analyses in each file, the summary below is relatively brief. For a greater summary of findings & recommendations, reference the full project files which contain more extensive summary sections at the beginning.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Brief Summary
These three projects analyzed over 57,000 survey responses of individuals within the tech industry regarding their employment details between 2020-2024. Through assessing particular subsets of individuals, a deeper understanding as to some recent/current trends of employees & salaries within the tech industry was uncovered. Such information can be used to assist companies within the industry in identifying & attracting the best candidates & to help drive success.  
No preprocessing was necessary.

### Part 1
The analyses compared employment information of data scientists & data engineers, then ratios & salaries of people based in the US who work full-time & fully remotely were evaluated. Recommendations as to the insights from these analyses can be referenced in the project file.

#### Analysis II - Salaries of Data Scientists, Data Engineers
Over the five years of records, the average salary of data scientists (~ $159,000) was about $10,000 more than that of data engineers (~ $149,000), the former of which is roughly equivalent to the overall average salary reported across the 57,194 responses.
On a yearly basis, both positions saw an overall increase in their average salaries over the five-year period. In particular, the annual average salary of data engineers increased incrementally each year, whereas that of data scientists decreased from 2020 to 2021 & 2023 to 2024.  
While typical salaries of both positions should be expected to continue to grow in the coming years, less growth in the last three years (2022-2024) might put salary estimates in 2030 roughly around $180,000 & $220,000 for data engineers & data scientists respectively.

#### Analysis III - Full-Time Remote Workers
Of the 57,194 survey responses, 11,125 were from employees who worked fully remote, full-time, & were US-based. Overall, the average salary of these individuals was about $155,000, slightly less than the overall average (~ $159,000).  
When evaluated on a yearly basis, the recorded average salaries of these individuals were relatively consistent as there was only a ~$1,800-overall increase from 2020 to 2024. Based on these trends, salaries in 2030 might be projected at roughly $166,000.

The proportions of US-based, full-time employees who worked fully remotely were evaluated over the five-year period to see how the rates evolved. Over the first three years, the rate of these individuals who worked entirely remotely increased--more than two people of every five worked fully remotely in 2022--but this rate declined precipitously from 2022-2024.



### Part 2
The analyses examined employment & salary information according to the top-earning positions, how much employees worked remotely, & the size of their company. Recommendations as to the insights from these analyses can be referenced in the project file.

#### Analysis I - Highest-Paying Jobs
The jobs with the highest average salaries were identified to get a basic understanding as to which positions saw the most pay. To account for less-than-representative job titles, two methods were employed to obtain these job titles.

Firstly, the five jobs with the greatest average salaries across all of the responses were identified & examined. They included (from highest to lowest): Analytics Engineering Manager, Data Science Tech Lead, Applied AI ML Lead, Head of Machine Learning, & Engineering Manager. Their average salaries ranged between $262,000-$400,000.  
Second, the five jobs with the greatest average salaries of those with at least three survey responses were retrieved & analyzed. They included (from highest to lowest): Head of Machine Learning, Engineering Manager, Head of AI, Machine Learning Model Engineer, & Director of Machine Learning. Their average salaries ranged between $242,000-$289,000.

Across both of these methods, there were some commonalities in the positions. Firstly, two of the jobs--Head of Machine Learning & Engineering Manager--directly overlapped. Additionally, of these eight positions, seven of them refer to titles that directly oversee & direct other employees such as managers, leads, heads, or directors. Moreover, three of them relate to engineering, four relate to machine learning (ML), & two relate to artificial intelligence (AI).  
As such, managerial jobs across these three fields appear to be particularly specialized & therefore command higher levels of pay within the tech industry. Such jobs are likely to be very competitive because companies will want to make sure that candidates are fully capable & worthy of positions that involve many responsibilities. As a consequence, companies should be willing to offer strong salaries to candidates whom meet their satisfaction in the hiring process.

#### Analysis II - Remote Work & Average Salary
Reported salaries were analyzed according to how much employees worked remotely as defined by three remote ratios. Employees either worked mostly remotely, mostly in person, or more-or-less evenly between remote & non-remote work (hybrid).  
Firstly, while there large sample sizes of responses across all three remote ratios, only 271 responses correspond to hybrid employees, whereas the other two ratios each accounted for at least 12,500 responses. Such an imbalance could point to preferences among companies who hire such individuals & the tech industry in general in that hybrid work is not really offered. Alternatively, it could point to a bias in the people who were surveyed in that hybrid workers were not represented equally.

Generally, hybrid workers reported salaries (~ $80,000) that were typically about half of those of either in-person or fully remote employees (~ $160,000 & $150,000 respectively). Such an imbalance may be related to a hiring preferential of companies in that they want candidates to fully commit to one way or the other when it comes to remote work.  
Over the 2020-2024 period, average salaries of the three remote-work types were within about $30,000 of each other; however, by 2024, this difference had grown beyond $80,000. Average salaries of fully remote & in-person employees grew significantly, whereas that of hybrid employees actually decreased by about $5,000.

Given these findings, it is fairly evident that in-person work became increasingly more valuable over these five years. Fully remote work also saw an increase in value but not quite to the same extent. Hybrid work, on the other hand, saw a small decrease in value from 2020-2024.

#### Analysis III - Company Size & Salary
Reported salaries were analyzed according to the size of the company employees worked at. Companies were labeled as either small (less than 50 employees), medium (between 50-250 employees), or large (more than 250 employees).  
Of the three company sizes, only 204 correspond to small companies & 1,965 correspond to medium-size companies. Although this is slightly logical given how the groups were defined, such an imbalance could give a general indication as to the size of most companies within the tech industry. Alternatively, it could point to a bias in the people who were surveyed.

Generally, workers from small companies reported salaries (~ $88,000) that were roughly half of those from medium-size or large companies (~ $160,000 & $153,000 respectively). Such an imbalance may be related to hiring capabilities of companies, their resources, & how they chose to allocate them when it comes to the salaries of their employees.  
Over the 2020-2024 period, average salaries of the three companies were within roughly $37,000 of each other, but this disparity grew to over $70,000 in 2024. Average salaries of employees from medium-size & large companies grew considerably, whereas those of employees from small companies only increased by about $16,000.

As such, it is fairly evident that employees in smaller companies faced an increasing disadvantage in terms of salary during these five years. It could be inferred that having more resources, as larger companies tend to have, is generally more of a benefit for employees in terms of what they earn & for companies in terms of what they can offer. Consequently, it allows them to more easily attract stronger talent.



### Part 3
The analyses examined employment & salary information of three specific jobs according to their country of residence, experience level, & how much they worked remotely. Regression models were then built & tuned to predict employee salaries based on a variety of factors including their experience level, company location, ratio of remote work, company size, employment type, job title, & employee residence. These models, some of which involved hyperparameter tuning, were evaluated using metrics including R-squared scores & mean-square-error terms in order to quantify their accuracy & predictive power. Importances of feature variables were also analyzed to assess which were more influential during the modeling process.  
Recommendations as to the insights from these analyses can be referenced in the project file.

#### Analysis I - Salaries by Country, Experience Level, Remote Work
Salaries of **data analysts**, **data scientists**, & **machine learning engineers** were evaluated across their country of residence, experience level, & ratio of remote work.  
Of the 57,194 records, 20,753 correspond to these three positions. Each account for between 5,000-10,000 survey responses. Generally, data analysts, data scientists, & machine learning engineers reported average salaries of approximately $109,000, $159,000, & $197,000 respectively.

In summary:
- **Data analysts** from Mexico, the US, & Australia generally reported the highest salaries. Senior- & executive-level data analysts reported the largest salaries. Fully-remote data analysts reported the largest salaries.
- **Data scientists** from the US & Mexico generally reported the highest salaries. Executive- & senior-level data scientists reported the largest salaries. In-person data scientists data scientists reported the largest salaries.
- **Machine learning engineers** from Ukraine, the US, & Australia generally reported the highest salaries. Executive- & senior-level machine learning engineers reported the largest salaries. In-person machine learning engineers reported the largest salaries.

#### Analysis II - Predictive Modeling
Regression techniques were utilized to predict employee salaries using information pertaining to their experience level, remote ratio, & company location. Specifically, linear & random forest regression algorithms were constructed, the latter of which included some hyperparameter tuning.

Ultimately, both routes produced underwhelming results when it comes to their models & their metrics. Across both techniques, the best model had an R-squared score of about 16%. The best model, based on R-squared scores, was the random forest model that utilized hyperparameter tuning which involved a grid search cross validation technique to find the best combination of hyperparameter values. This model had a R-squared score of about 16.6%.  
Regarding feature importances of the models, there was one common finding across all three models--employees' experience level is considerably important when it comes to predicting their salaries. For the other two variables--remote ratio & company location--the two algorithms came to opposing conclusions.

#### Analysis III - More Predictive Modeling
The random forest models from **Analysis II** were expanded to include additional feature variables such as employees' experience level, remote ratio, company location, company size, employment type, job title, & employee residence.

Variables were added one at a time & models were evaluated to assess how much they contributed to predictive performance. Generally, none of the variables elevated the models except for the job titles. In particular, a random forest regression model with the features of experience level, company location, remote ratio, company size, job title, & employee residence yielded a R-squared score of about 30%.  
Regarding the feature importances of this model, employees' experience level is considerably important when predicting salaries, & remote ratios are somewhat important. Conversely, their company size, job title, country of residence, & company location are generally negligible, at least for the models produced.
