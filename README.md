![Dashboard](https://github.com/user-attachments/assets/e3afcc39-0888-4647-b3f8-d619e243563d)

# Introduction:
This project focuses on creating a dynamic healthcare analytics dashboard using Power BI to analyze hospital emergency room data, including patient wait times, satisfaction scores, and visit patterns, aiming to uncover insights that can improve healthcare efficiency and patient experience.

# Project Files:
- **Dashboard File:** The Power BI dashboard file is available here: [Dashboard File](https://github.com/MadhurShekharBand/PowerBI_Project_-_Healthcare_Analytics_Dashboard/blob/f75fdb529bd1391cc3566e79388197985eb5790c/Dashboard%20-%20PowerBI%20File.pbix)
- **Data File:** The data file in Microsoft Excel Comma Separated Values File (.csv) format is available here: [Data File](https://github.com/MadhurShekharBand/PowerBI_Project_-_Healthcare_Analytics_Dashboard/tree/f75fdb529bd1391cc3566e79388197985eb5790c/Data)
- **Dashboard Images:** The images used in the dashboard are available here: [Dashboard Images](https://github.com/MadhurShekharBand/PowerBI_Project_-_Healthcare_Analytics_Dashboard/tree/f75fdb529bd1391cc3566e79388197985eb5790c/Dashboard%20Images)
- **Dashboard Canvas Background:** I created the dashboard’s canvas background in Microsoft Office PowerPoint and then saved the final product as an JPEG image. Both the files are available here: [Dashboard Canvas Background](https://github.com/MadhurShekharBand/PowerBI_Project_-_Healthcare_Analytics_Dashboard/tree/d60c688daa1a49f080437ef723a7fe4b6cdfffd4/Dashboard%20Canvas%20Background)

# Background:
### The questions I wanted to answer through my SQL queries were:
- **What is the average wait time for patients before their appointments?** <br>
I am trying to find out the typical duration patients wait before seeing a healthcare provider. This helps assess the efficiency of our healthcare system and identify areas where improvements could be made.

- **What is the average patient satisfaction score?** <br>
I am trying to find out how satisfied patients are with their healthcare experience, which will help identify areas for improvement in the quality of care and patient service.

- **What is the total number of patients visits each month?** <br>
I am trying to determine the overall volume of patient visits to gauge the demand for healthcare services and anticipate resource needs. I am also trying to track fluctuations in patient visits over time to identify trends, such as seasonal peaks or growth in demand, which can inform planning and staffing decisions.

- **What is the breakdown between administrative and non-administrative appointments?** <br>
I am trying to understand the distribution of appointments that involve administrative tasks versus those that are strictly medical. This will help assess the workload and identify ways to streamline processes.

- **What is the proportion of referred patients versus walk-in patients?** <br>
I am trying to find out how many patients are referred by other healthcare providers compared to those who walk in without prior appointments. This will help us understand patient flow and plan for resource allocation.

- **What is the distribution of patient visits across different age groups and genders?** <br>
I am trying to analyse how patient visits vary by age group and gender, which will provide insights into the healthcare needs of different age populations and genders and inform age-specific and gender-specific care strategies.

- **How do age and race influence healthcare needs and preferences?** <br>
I am trying to understand how different age groups and races have varying healthcare needs, preferences, and expectations, so we can tailor our services to be more inclusive and responsive to diverse patient populations.

### About the Dataset:
The dataset used for this project is a hospital emergency room (ER) dataset which includes information on patients' visits, capturing key details such as patient demographics (age, gender, race), satisfaction scores, administrative flags, wait times, and departmental referrals. The data spans multiple dates in 2019 and 2020 and reflects a mix of emergency visits with varying patient backgrounds. It reveals patterns such as the diversity of patients by age and race, wait times for different categories of visits, and whether administrative processes were involved. Referrals to specific departments, like Orthopaedics or General Practice, are also recorded, providing insights into the types of care sought by patients.

### Tools I Used:
For my deep dive into the hospital emergency room (ER) dataset, I harnessed the power of two key tools:
- **Power Query:** Power Query is used for cleaning, shaping, and transforming the data before loading it into Power BI for analysis and visualization.
- **Power BI:** The preferred BI tool used to visualize the dataset and create the final dashboard.

# Overview of the Dashboard:
The dashboard has 11 Key Performance Indicators (KPIs) which answers all the questions mentioned in the “Background” section.
<br>
<br>
The dashboard is fully dynamic and has two filters to allow the users to focus on a specific part of the dashboard based on their context. The main filter on the top-right side of the dashboard allows the user to filter the KPIs by “AM” or “PM”. The second filter allows the user to switch between “Avg. Satisfaction” and “Avg. Wait Time” for different age groups and patient races.

# Insights:
- The average wait time is 35.26 minutes, indicating moderate efficiency in the ER process. This suggests that there might be opportunities to improve wait times to enhance patient satisfaction and operational efficiency.
- A average patient satisfaction score of 5.47 suggests that patients are not highly satisfied with their experience at the ER. This highlights the need for the hospital to focus on improving patient satisfaction, particularly around factors like wait times, service quality, and communication.
- The hospital experiences varying patient visits each month, with the highest visits in May (999) and August (1024), and the lowest in February (431) and November (464). Patient visits peak during May to August, indicating that there is higher demand during the summer months. The lowest visit numbers occur in January and November, suggesting possible seasonal declines in patient visits during those months.
- About 50.04% of appointments involve administrative tasks, while 49.96% are medical appointments. The distribution indicates a near-equal split between administrative and medical appointments. This suggests that almost half of the ER's workload is spent on administrative processes, which may need to be streamlined to improve patient flow and care efficiency.
- 58.59% of the patients are walk-ins, while 41.41% are referred by other healthcare providers. The majority of ER patients are walk-ins. This suggests that the ER needs to manage a high volume of unscheduled patients, which could impact wait times and resource allocation. The hospital might consider improving processes to manage walk-in demand effectively.
- The majority of visits come from adults, but there is a notable representation from younger age groups as well. Gender distribution is fairly balanced, with slightly more females. This information can guide the hospital in tailoring services to the most frequent age groups and ensuring that gender-specific healthcare needs are addressed effectively.

# Conclusion:
### What I Learned:
Through this project, I gained hands-on experience in using Power BI and Power Query for data cleaning, shaping, and visualizing. I also enhanced my ability to analyze healthcare data, draw meaningful insights, and create interactive dashboards that support data-driven decision-making.

### Closing Thoughts:
This project allowed me to develop a deeper understanding of hospital operations and patient needs, while honing my skills in data analysis and visualization to help improve healthcare services.
