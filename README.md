# Demystifing Data Salaries (Python)

**Background:** You work for an international HR consultancy helping companies attract and retain top talent in the competitive tech industry. As part of your services, you provide clients with insights into industry salary trends to ensure they remain competitive in hiring and compensation practices. Your team wants to use a data-driven approach to analyse how various factors—such as job role, experience level, remote work, and company size—impact salaries globally. By understanding these trends, you can assist in advising clients on offering competitive packages to attract the best talent.  
In this project competition, which consists of three levels/parts, salary data from thousands of employees worldwide will be explored, mined, & visualized. Later levels of the project will involve building predictive models to uncover key salary drivers and providing insights on how to enhance future data collection.

**The Data:** Available in `salaries.csv`, the data comes from a survey hosted by the aforementioned HR consultancy. Each data point represents a single employee's salary record & other employment details for a given year. It contains over 57,000 survey responses between 2020-2024.

These projects, completed in June, 2025, were part of a three-part competition on _DataCamp_. As such, three files were completed & are included in this repository: _Demystifying Data Salaries - Level 1_, _Demystifying Data Salaries - Level 2_, & _Demystifying Data Salaries - Level 3_. Each file examines different objectives; the first two use standard analytical techniques & the last uses machine learning algorithms. Given this & the length of the analyses in each file, the summary below is relatively brief. For a greater summary of findings & recommendations, reference the full project files which contain more extensive summary sections at the beginning.

-----------------------------------------------------------------------------------------------------------------------------------------------------------------------------

## Brief Summary
These three projects analyzed over 57,000 survey responses of individuals within the tech industry regarding their employment details between 2020-2024. Through assessing particular subsets of individuals, a deeper understanding as to some recent/current trends of employees & salaries within the tech industry was uncovered. Such information can be used to assist companies within the industry in attracting the best candidates & to help drive success.  
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
...
