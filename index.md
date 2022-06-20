## Call Center Dashboard

This dashboard is an example of a call center's performance. Below outlines the context for why a dashboard was needed, the user stories mapped to the KPIs, and the process for arriving at the dashboard. 

**PLEASE NOTE:** ALL DATA IN THIS DASHBOARD IS FAKE AND WAS CREATED BY THE AUTHOR (ANDREW SMOTHERMON). THIS IN NO WAY DESCRIBES, OR RELATES TO, ANY PAST OR CURRENT CLIENT INFORMATION

### Background

McGyver Inc. is a business-to-business hardware manufacturing company that sells widgets across the state of Nebraska. The organization is divided into 4 regions (North, South, East, West), and each region has two divisions. These divisions are resposible for two things:

* Selling widgets to company's across their territory in Nebraska
* Providing customer service when there is an issue with a widget via their **call center**

Sales have been great at McGyver Inc., however, some **complaints about customer service call center** have reached the C-Suite. Leadership realized that while they collect data on their customer service, they have not built out any reporting to understand **what could be driving poor customer service outcomes**.

Call center data is basic but **they do catalog every customer service call and ask customers to rate their service on a 1-5 likert scale**.

### User Stories and KPIs

After consultation and data exploration with Fox-Smothermon Consulting LLC., McGyver Inc. leadership has tailored a **Problem Statement** along with **User Stories** and **KPIs** that could help them better understand call center operations and what is driving poor customer service. 

#### Audience/Users of Report
Executive Leadership of McGyver Inc. 

#### Problem Statement

McGyver Inc. leadership currently has no insight into call center operations. Reporting is required to better understand what regions/divisions are receiving poor customer service survey ratings, if there is anything driving low ratings, and if customer service is improving or getting worse

#### User Stories and KPIs

**User Story:** I need to see what regions/divisions have poor customer service ratings, so I know which supervisors need to talk with staff about performance
* KPI: Avg. Survey Rating by Region 
* KPI: Avg. Survey Rating by Division

**User Story:** I need to see if there are any drivers to the low-ratings so that I can inform future customer service trainings 
* KPI: Avg. Survey Rating by Avg. Length of Call per Employee (Exploration-derived insight)
* KPI: Avg. Survey Rating by widget type

**User Story:** I need to know if customer service is improving or getting worse so I know if different interventions are working
* KPI: Avg. Survey Rating by Region/Division over Time

### McGyver Inc. System Architecture

* **Back End:** Relational Database
* **Front End:** Tableau/Tableau Server
