# Employee Attrition and Satisfaction Insights

**Performance Dashboards **

**Job Satisfaction in Job role by <Sarang >**

![Screenshot 2025-02-17 012210](https://github.com/user-attachments/assets/3089ae06-3763-49b4-90a3-5872ce28ad54)
 
Hierarchy of Department and Job Role were added on the Columns shelf and Gender on the Rows shelf. I used CNT(Attrition) on the Rows shelf to display the count of attrition, and set the Marks type to Bar for a stacked view. I added Marital Status to the Color shelf to differentiate the data based on marital status, which highlights patterns across demographics. Additionally, filters for Attrition, Job Level, and Age were included for dynamic interaction, and I customized the tooltip for detailed viewing. 
The chart helps HR to see where and why are the employees leaving the organization. The  data is split between Job role, gender and martial status to show which group are most affected. It is designed to help HR professionals and managers gain insights into employee turnover patterns and understand which demographics are most affected. This chart helps HR to identifies High Attrition Rates area. However, HR can quickly identify which department and job roles have the highest attrition rate.  The chart also allow HR to see the gender imbalance in attrition rate within each department job role .  By analyzing attrition rates based on martial status, HR can understand if the certain group (e.g., single or divorced employees) are more prone  to leaving the organization. Also this chart provides a data-driven approach for HR to make informed decision. Rather than guessing why employees are leaving the organization, HR can use these insights to prioritize their action based on the departments and demographics that are most affected. By reviewing this chart, HR can track whether new initiatives are effectively reducing attrition rates over the period of time, helping them to adjust their strategies. By leveraging this chart, HR can make informed, strategic decisions that not only reduce turnover but also enhance overall employee experience, ensuring that the company retains its valuable talent and builds a supportive, inclusive workplace 

**Distribution of Employees by Job Level and Entry Status<Sarang>**

![Screenshot 2025-02-17 012312](https://github.com/user-attachments/assets/6a44bbf1-ca9c-47cc-884e-36aedb0f57e3)

Created a set based on the Job Level column to categorize employees as entry-level or others. Also a calculated field of COUNT[EMPLPOYEE] is created .Then, dragged the set to the Rows shelf, splitting the data into two groups: "In" (entry-level) and "Out" (non-entry-level). I used Job Level on the Angle shelf and CNT(Employee) on the Angle shelf to form the segments. Education Field and Average Training Times Last Year were added to the tooltip to provide additional insights into the distribution. 
The above chart Employee Distribution by Job Level gives comprehensive overview of employees distribution based on job levels education fields, and averages training times over time.  The purpose of the chart is to distribution of employees based on their job level, entry status whether they are entry level employees or not, education field, and average training times received in the last year. This chart will help HR to get a clear understanding of proportion of entry-level vs non entry level employees within the company helps HR to identify if there is a balanced representation across different job levels,  which is important for workforce planning and succession management. Also this chart will show the average training times per job level,  where HR can find the training programs are appropriately aligned with the employes roles. If the higher job role required more leadership programs which important for decision making . Moreover, HR can also find the Education Field Distribution this will help HR  to understand the educational background of employees indifferent roles   


**Job Satisfaction in Job role by <Sarang>**

![Screenshot 2025-02-17 012346](https://github.com/user-attachments/assets/4e54aeb4-9008-4068-beb7-bc1f9631debc)

Hierarchy of Department and Job Role were added to the Columns shelf and CNT(Job Satisfaction) to the Rows shelf, which helped build the stacked bars. Set the Marks type to Bar and added Job Satisfaction to both the Color and Label shelves to differentiate and label the satisfaction levels visually. Included filters to allow for dynamic adjustments and customized the tooltip for additional clarity. Finally, added the chart title to provide context, making it easy to understand employee satisfaction distribution across departments and roles.
The chart "Job Satisfaction in Job Role by Department" provides a comprehensive overview of employee satisfaction levels across different job roles and departments within the organization. The purpose of the chart is to illustrate how satisfied employees are based on their job role within each department, showing a breakdown of satisfaction levels (ranging from low to high). This chart will help HR gain a clear understanding of which departments and job roles have the highest and lowest levels of job satisfaction, allowing HR to identify areas where improvements are needed. By understanding these variations, HR can better plan interventions, ensuring there is a balanced and positive employee experience across different roles and departments, which is critical for workforce retention and development. Additionally, this chart serves as a tool for HR to pinpoint specific job roles that require targeted attention. If certain roles within a department show consistently low satisfaction levels, HR can implement support programs, training opportunities, or performance-based incentives to boost morale and increase satisfaction. 

**Salary Hike in % w.r.t Years in Company<Sarang>**

![Screenshot 2025-02-17 012412](https://github.com/user-attachments/assets/19fbfff0-889b-49d7-938f-44262caca596)
 
Placed Years At Company on the Columns shelf and Department and AVG(Percent Salary Hike) on the Rows shelf. Set the Marks type to Line to visualize the trends clearly over time. Each department's salary hike percentage is represented separately, showing patterns over employees' tenure. Customized the tooltip for clarity and adjusted the labels and lines for each department to highlight the variations
The chart titled "Salary Hike in % with Respect to Years in Company" provides a comprehensive overview of salary growth trends segmented by department and tenure. The purpose of the chart is to analyze the percentage increase in salary over time, correlated with the number of years employees have been with the company, across different departments. This chart helps HR understand whether compensation policies are consistent and fair across departments, and if they appropriately reward employee tenure and experience. By visualizing salary growth trends, HR can identify if salary increments stagnate after a certain tenure, which might impact employee retention. Additionally, it enables HR to compare departments such as Human Resources, Research & Development, and Sales to ensure equitable compensation strategies.

**Attrition rate by Environment satisfaction<Sarang>**

![Screenshot 2025-02-17 012430](https://github.com/user-attachments/assets/e7635d12-1861-4a1a-b8e8-520563cad16a)

 
Placed Environment Satisfaction on the Columns shelf and AVG(Attrition Rate) on the Rows shelf. The Marks type was set to Line to visualize the relationship between environment satisfaction levels and attrition rates across departments. Added Department to the Color shelf to differentiate each department, making it easy to compare how changes in environment satisfaction impact attrition rates for each. The tooltip was customized for clarity, and the labels were adjusted to display the percentage attrition rates.
The chart titled "Attrition Rate by Environment Satisfaction" provides a comprehensive view of how employee satisfaction with their work environment correlates with attrition rates across various departments, such as Human Resources, Research & Development, and Sales. The purpose of the chart is to help HR visualize the impact of environment satisfaction levels (ranging from low to high) on the likelihood of employees leaving the company, and to identify any departmental differences in these trends. By analyzing this chart, HR can determine which departments experience the highest attrition rates in response to lower levels of environment satisfaction. This chart is crucial for HR as it enables the identification of specific departments where targeted interventions could be applied to lower turnover rates. By understanding the relationship between environment satisfaction and attrition, HR can design department-specific strategies to retain employees more effectively.

Summary Tiles

1. The summary tile display the overall attrition rate for the entire company, giving a broader view before users dive into departmental details.
2. Shows the average number of years employees have been with the company.
3. It is used to summarize high-performing and highly satisfied employees
4. Average salary hike percentage for employees who have been with the company for more than 5 years. 
