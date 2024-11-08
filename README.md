# Cyclistic Bike-Share : Google Data Analytics Capstone Project

This repository contains Google Data Analytics Capstone - Case Study 1 project, which is the final stage of the Google Data Analytics course on coursera.

**Introduction**

This case study focuses on Cyclistic, a fictional bike-share company. The goal of the project is to explore data-driven insights that can help address key business questions. By applying the data analysis process (Ask, Prepare, Process, Analyze, Share, and Act), I will thoroughly investigate how different customer segments use Cyclistic’s services. The analysis will include examining trip patterns, usage trends, and differences between user types, such as annual members and casual riders. The findings will be used to provide actionable recommendations that can help Cyclistic optimize its services and enhance customer engagement.

**Scenario Overview: Cyclistic Marketing Analysis**

As a junior data analyst on the marketing analytics team at Cyclistic, a bike-share company based in Chicago, I have been tasked with providing insights to support a new marketing strategy. Cyclistic’s director of marketing believes that the company’s long-term success hinges on increasing the number of annual memberships. To achieve this, it is crucial to understand how casual riders and annual members use Cyclistic’s bikes differently. The goal of this analysis is to identify key usage patterns that can inform a targeted marketing approach aimed at converting casual riders into loyal, annual members. The insights and recommendations derived from this analysis will be presented to Cyclistic’s executives and must be supported by compelling data visualizations and evidence-based findings to gain approval.

**About the company**

In 2016, Cyclistic launched a successful bike-share offering. Since then, the program has grown
to a fleet of 5,824 bicycles that are geotracked and locked into a network of 692 stations
across Chicago. The bikes can be unlocked from one station and returned to any other station
in the system anytime.
Until now, Cyclistic’s marketing strategy relied on building general awareness and appealing to
broad consumer segments. One approach that helped make these things possible was the
flexibility of its pricing plans: single-ride passes, full-day passes, and annual memberships.
Customers who purchase single-ride or full-day passes are referred to as casual riders.
Customers who purchase annual memberships are Cyclistic members.
Cyclistic’s finance analysts have concluded that annual members are much more profitable
than casual riders. Although the pricing flexibility helps Cyclistic attract more customers,
Moreno believes that maximizing the number of annual members will be key to future growth.
Rather than creating a marketing campaign that targets all-new customers, Moreno believes
there is a solid opportunity to convert casual riders into members. She notes that casual riders
are already aware of the Cyclistic program and have chosen Cyclistic for their mobility needs.
Moreno has set a clear goal: Design marketing strategies aimed at converting casual riders into
annual members. In order to do that, however, the team needs to better understand how
annual members and casual riders differ, why casual riders would buy a membership, and how
digital media could affect their marketing tactics. Moreno and her team are interested in
analyzing the Cyclistic historical bike trip data to identify trends.

i downloaded the dataset from https://divvy-tripdata.s3.amazonaws.com/index.html
and i used 2019 data from January to December.

**Ask**

Three questions will guide the future marketing program:
1. How do annual members and casual riders use Cyclistic bikes differently?
2. Why would casual riders buy Cyclistic annual memberships?
3. How can Cyclistic use digital media to influence casual riders to become members?

**Business Task**

How do annual members and casual riders use Cyclistic bikes differently?

**Key Stakeholders**

1. Cyclistic
2. Lily Moreno
3. Cyclistic executive team
4. Cyclistic marketing analytics team

**Phase 2 – PREPARE**

Guiding Questions:

Que1: Where is your data located?

Ans1: i downloaded the dataset from https://divvy-tripdata.s3.amazonaws.com/index.html and i used 2019 data from January to December.

Que2: How is the data organized?

Ans2: There are many ways to organize data. I chose Python and PowerBi because i can also clean data in there. I combined data from all quarters into a single dataframe then added some colums that were necessary and removed unnecessary columns.

Que3. Are there issues with bias or credibility in this data? Does your data ROCCC?

Ans3. In this project, data largely meets the ROCCC criteria, indicating that it is a credible source for analysis. The data is reliable and original, sourced directly from Divvy’s system, and offers a comprehensive view of bike usage patterns between casual riders and annual members. It is current and properly cited, making it suitable for developing insights.

Que4. How are you addressing licensing, privacy, security, and accessibility?

Ans4. In this project, data is handled responsibly by following key guidelines. The data is publicly available and shared under an open license, meaning it can be used as long as the rules are followed. Since the data doesn't contain personal details, privacy is protected, and with proper storage, security risks are low. The data is easy to access and analyze, allowing anyone to use it for insights. Overall, the data is handled in a way that respects licensing, privacy, security, and accessibility.

Que5. How did you verify the data’s integrity?

Ans5. To ensure the data’s integrity, I checked for missing values, made sure the formats were consistent, looked for unusual or incorrect data and removed duplicates. This process helped confirm that the data is reliable and ready for analysis.

Que6. How does it help you answer your question?

Ans7. Verifying the data’s integrity ensures the information is accurate, helping me confidently analyze how annual members and casual riders use Cyclistic bikes differently. Clean data leads to better insights and stronger recommendations.

Que8. Are there any problems with the data?

Ans.8 The data had some issues like missing values, outliers , inconsistent formats that need to be fixed for accurate analysis.


**Phase 3 – PROCESS**

Guiding questions

Que1. What tools are you choosing and why?

Ans1. I chose Python and Power BI for the analysis because it offers powerful data visualization capabilities, user-friendly design, and robust integration with various data sources. PowerBi allows for interactive dashboards and detailed reporting, which are ideal for exploring and presenting insights from the Divvy trip data effectively.

Que2. Have you ensured your data’s integrity?

Ans2. Yes, I managed to ensure the integrity of the data. I added 12 months of data to a single data frame, making it ready for a year's analysis.

Que3. What steps have you taken to ensure that your data is clean?

Ans3. I cleaned the data by removing duplicates, handling missing values, checking for outliers, standardizing formats, and validating accuracy.

Que4. How can you verify that your data is clean and ready to analyze?

Ans4. I verify that my data is clean and ready to analyze by checking for and resolving missing values, ensuring there are no duplicates or outliers, confirming consistent formats.

Que5. Have you documented your cleaning process so you can review and share those
results?

Ans5. I combined data from all quarters into a single dataframe then added some columns that were necessary and removed unnecessary columns.

**Phase 4 – Analyze**

Guiding questions

Que1. How should you organize your data to perform analysis on it?

Ans2. First of all i combined data from quarters into a single frame in Python and then i cleaned it. After thatt to organize data for analysis, i arranged it into clear tables and make sure dates, numbers, and text are consistently formatted. I used clear headers, apply filters and sorting to focus on important parts, and added calculated columns for any needed metrics.
Here are some columns that i added
![image](https://github.com/user-attachments/assets/591f8bbf-7646-4efd-abf7-4bf5aaaefcc3)





Que2. Has your data been properly formatted?

Ans2. Yes, my data has been properly formatted. I ensured that dates, numbers, and text entries are consistently formatted, and I verified that all columns have clear headers and that the data is organized logically for analysis.

Que3. What surprises did you discover in the data?

Ans3. There were notable differences in how annual members and casual riders used the bikes, such as varying peak times or trip duration.

Que4. What trends or relationships did you find in the data?

Ans4. In the data, I found several key trends and relationships like usage patterns, popular stations, trip durations etc.

Que5. How will these insights help answer your business questions?

Ans5. These insights show how annual members and casual riders use the bikes differently, helping us understand their behavior. By knowing when and where each group rides, and how long they typically ride, we can create better marketing strategies to attract casual riders and turn them into annual members.

**Phase 5 - SHARE**

Guiding questions

Que1. Were you able to answer the question of how annual members and casual riders use Cyclistic bikes
differently?

Ans1. Yes, I was able to identify clear differences in how annual members and casual riders use the bikes, such as usage times, trip durations, and station preferences.

Que2. What story does your data tell?

Ans2. The data shows that annual members ride more frequently and typically during weekdays, while casual riders use the bikes more on weekends. It also highlights busiest start and end stations.

Que3. How do your findings relate to your original question?

Ans3. My findings directly answer the question by showing distinct usage patterns between casual riders and annual members, providing insights to help convert casual riders into members.

Que4. Who is your audience? What is the best way to communicate with them?

Ans4. My audience includes Cyclistic executives and the marketing team. The best way to communicate with them is through clear, visual data presentations with key insights.

Que5. Can data visualization help you share your findings?

Ans5. Using charts and graphs will simplify the presentation of trends and comparisons, making it easier for the audience to quickly understand the key differences between casual riders and annual members. Visualizing the data helps highlight important insights clearly and effectively.
here are some visualizations
![dashboard1](https://github.com/user-attachments/assets/e7ca6ea2-b96f-4217-b181-febe2f669988)


![dashboard2](https://github.com/user-attachments/assets/1b5921c9-692a-41df-afcc-dcf642e1fa38)


![dashboard3](https://github.com/user-attachments/assets/950f6ae7-5da9-4859-ac1a-c1e15fd5ef1a)




**Phase 6 – Act**

Guiding question

Que1.  What is your final conclusion based on your analysis?

Ans1. From the analysis, we see that annual members ride more often during weekdays and usually take longer trips. In contrast, casual riders tend to use the bikes on weekends for shorter trips. This shows clear differences in how each group uses the bike service. Most busy station is Canal St & Adams St.The most popular time for trips is during the 5 PM hour, with 418K trips. 
      The second most popular time is 4 PM, with 320K trips, followed by 8 AM with 291K trips.
      There is a clear spike in usage during peak commuting hours, such as mornings (7-9 AM) and evenings (4-6 PM), indicating that many users likely use Cyclistic bikes for commuting purposes.
      There is a significant drop-off in usage between 10 PM and 5 AM, which suggests that bike usage is minimal during late night and early morning hours.
      Subscribers show a consistent number of trips across the weekdays, peaking on Friday and maintaining high usage on Monday, Tuesday, Wednesday, and Thursday.
      Casual riders , on the other hand, show a different pattern, with fewer trips on weekdays and more trips on the weekends, especially on Saturday with a slight peak at 0.07M trips.
      This suggests that subscribers use the bikes more regularly for commuting during the week, while casual riders tend to use the bikes more for leisure on weekends.
      

Que2.  How could your team and business apply your insights?

Ans2. The marketing team can work on turning casual riders into annual members by highlighting the advantages of membership. They can focus on weekends and target the stations that casual riders use the most. promoting the membership benefits during weekends or at popular casual rider locations might encourage more casual riders to convert to annual memberships. By focusing on how each group uses the service, Cyclistic can better meet their needs and improve overall satisfaction.
      The marketing strategy to encourage casual riders to get an annual membership should focus on key topics like saving money, improving health, helping the environment, and avoiding traffic. Highlighting the benefits of cycling in these areas can be more appealing than other transportation options.

Que3. What next steps would you or your stakeholders take based on your findings?

Ans3. The next steps based on these findings could involve creating specific marketing campaigns aimed at casual riders and offering them special membership deals. Also, improving stations or services in areas that casual riders frequently use could enhance their experience.

Que4. Is there additional data you could use to expand on your findings?

Ans4. To get a better understanding of what affects rider behavior, further analysis could look at factors like weather, demographics, or local events. This could help improve the service for both casual riders and annual members.
