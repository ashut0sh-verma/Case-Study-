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
Ans2: There are many ways to organize data. I chose PowerBi because i can also clean data in there. I combined data from all quarters into a single dataframe then added some colums that were necessary and removed unnecessary columns.

Que3. Are there issues with bias or credibility in this data? Does your data ROCCC?
Ans3. In this project, data largely meets the ROCCC criteria, indicating that it is a credible source for analysis. The data is reliable and original, sourced directly from Divvy’s system, and offers a comprehensive view of bike usage patterns between casual riders and annual members. It is current and properly cited, making it suitable for developing insights.

Que4. How are you addressing licensing, privacy, security, and accessibility?
Ans4. In this project, data is handled responsibly by following key guidelines. The data is publicly available and shared under an open license, meaning it can be used as long as the rules are followed. Since the data doesn't contain personal details, privacy is protected, and with proper storage, security risks are low. The data is easy to access and analyze, allowing anyone to use it for insights. Overall, the data is handled in a way that respects licensing, privacy, security, and accessibility.

Que5. How did you verify the data’s integrity?
Ans5. To ensure the data’s integrity, I checked for missing values, made sure the formats were consistent, looked for unusual or incorrect data and removed duplicates. This process helped confirm that the data is reliable and ready for analysis.

Que6. How does it help you answer your question?
Ans7. Verifying the data’s integrity ensures the information is accurate, helping me confidently analyze how annual members and casual riders use Cyclistic bikes differently. Clean data leads to better insights and stronger recommendations.

Que8. Are there any problems with the data?
Ans. The data had some issues like missing values, outliers , inconsistent formats that need to be fixed for accurate analysis.


**Phase 3 – PROCESS**

