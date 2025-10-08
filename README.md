# Maji Ndogo Water Crisis: A Power BI Data Analytics Project

This repository contains a comprehensive Power BI project analyzing the water crisis in Maji Ndogo. The project is divided into four parts, each building upon the last to provide a deep dive into the data, from initial exploration to the creation of a public-facing dashboard for tracking improvement efforts.

## Project Overview

The goal of this project is to use Power BI to analyze survey data from Maji Ndogo to understand the state of water access, identify key challenges, and track the progress and financial aspects of a project aimed at improving water sources. The project addresses various aspects of the water crisis, including population distribution, water source types, queue times, water pollution, and the social impact of water collection, such as crime rates.

## Tools and Technologies

* **Power BI:** Used for all data modeling, analysis, and visualization.
* **DAX (Data Analysis Expressions):** Utilized for creating complex measures such as cumulative costs, budget tracking, and basic water access percentages.
* **Power Query (M Language):** Employed for data cleaning, transformation, and shaping the initial datasets.

## Part 1: Visualising Maji Ndogo’s Past

In the first part of the project, we focused on the initial exploration and visualization of the survey data. This phase was crucial for understanding the basic landscape of the water crisis in Maji Ndogo.

### Key Activities:

* **Data Import and Cleaning:** The initial dataset was imported from a CSV file into Power BI. Basic data cleaning and transformation were performed to ensure data quality and usability, such as verifying correct data types.
* **National-Level Analysis:** Visuals were created to represent the survey results at a national level. This included a pie chart showing the urban vs. rural population split and a bar chart illustrating the distribution of different water source types.
* **Infrastructure Mapping:** A custom map of Maji Ndogo was used to visualize the locations of broken water infrastructure across different provinces, providing a clear geographical context to the problem.
* **Queue Time Analysis:** Line and bar charts were used to analyze the average queue times for water collection, broken down by day of the week and hour of the day. This revealed patterns in water collection times and highlighted peak hours.
<table>
  <tr>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/01.%20Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201)/Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201).png/Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201)%201%20of%203.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/01.%20Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201)/Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201).png/Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201)%202%20of%203.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/01.%20Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201)/Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201).png/Visualising%20Maji%20Ndogo%E2%80%99s%20Past%20(Part%201)%203%20of%203.png" width="500" /></td>
  </tr>
</table>

*Dashboard from Part 1 showing the initial analysis of population, water sources, and queue time.*

## Part 2: Moulding Data into Visual Stories in Maji Ndogo

The second part of the project involved building a more complex data model to integrate various data sources and uncover deeper insights. This allowed for a more nuanced and compelling narrative about the water crisis.

### Key Activities:

* **Data Modeling:** A data model was created in Power BI by importing multiple tables from an Excel workbook. Relationships were established between the tables to create a multi-star schema, enabling more complex queries and analysis.
* **Enhanced Visualizations:** The visuals from Part 1 were recreated and enhanced using the new data model. This included a more detailed national-level dashboard and a more in-depth analysis of queue times.
* **Well Pollution Analysis:** The data was analyzed to understand the extent of well pollution, distinguishing between chemical and biological contamination.
* **Crime Data Integration:** Crime data was integrated into the model to explore the relationship between water collection and public safety. This analysis revealed a gender disparity in crime victims related to water collection.

<table>
  <tr>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/02.%20Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202).png/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)%201%20of%204.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/02.%20Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202).png/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)%202%20of%204.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/02.%20Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202).png/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)%203%20of%204.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/02.%20Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202).png/Moulding%20Data%20into%20Visual%20Stories%20in%20Maji%20Ndogo%20(Part%202)%204%20of%204.png" width="500" /></td>
  </tr>
</table>

*Dashboard from Part 2 focusing on the analysis of crime related to water collection.*

## Part 3: Communicating Our Findings in Maji Ndogo

The third part of the project focused on creating a report tailored to the needs of decision-makers, such as the president and provincial leaders. This involved translating the data insights into actionable information.

### Key Activities:

* **User-Centric Design:** The report was designed based on user stories to ensure that it met the specific needs of the stakeholders. This involved identifying the key questions they needed to answer and creating visuals that addressed those questions directly.
* **DAX Calculations:** Data Analysis Expressions (DAX) were used to create calculated columns and measures. These calculations were essential for determining project costs, budget allocations, and the potential impact of water source improvements on basic water access.
* **Interactive Reporting:** The report was designed to be interactive, using features like slicers and bookmarks, allowing users to drill down into the data and explore it at different levels of detail, from national to provincial.

<table>
  <tr>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/03.%20Communicating%20Our%20Findings%20in%20Maji%20Ndogo%20(Part%203)/Communicating%20Our%20Findings%20in%20Maji%20Ndogo%20(Part%203).png/Communicating%20Our%20Findings%20in%20Maji%20Ndogo%20(Part%203)%201%20of%202.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/03.%20Communicating%20Our%20Findings%20in%20Maji%20Ndogo%20(Part%203)/Communicating%20Our%20Findings%20in%20Maji%20Ndogo%20(Part%203).png/Communicating%20Our%20Findings%20in%20Maji%20Ndogo%20(Part%203)%202%20of%202.png" width="500" /></td>
  </tr>
</table>

*The stakeholder-focused report from Part 3, detailing budget needs and improvement plans.*

## Part 4: Transparency in Tracking Maji Ndogo's Water Funds

The final part of the project involved creating a public-facing dashboard to track the progress and financials of the water source improvement project. This dashboard was designed to provide transparency and accountability.

### Key Activities:

* **Dashboard Development:** A dynamic dashboard was created to monitor the project's progress. This included key performance indicators (KPIs) for project completion, budget vs. actual costs, and the number of people gaining access to basic water.
* **Data Updates:** The data model was updated with new project data, including completion dates, costs, and vendor information. This allowed for real-time tracking of the project's performance.
* **Vendor Performance Analysis:** The data was analyzed to assess the performance of different vendors involved in the project. This analysis helped identify opportunities for cost savings and process improvements.
* **Data-Driven Optimization:** The insights from the dashboard were used to make data-driven decisions to optimize the project's implementation and ensure that the resources were used effectively.

<table>
  <tr>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/04.%20Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204)/Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204).png/Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204)%201%20of%203.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/04.%20Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204)/Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204).png/Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204)%202%20of%203.png" width="500" /></td>
    <td><img src="https://github.com/Philopater-George/Maji-Ndogo-Water-Crisis-A-Power-BI-Data-Analytics-Project/blob/main/04.%20Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204)/Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204).png/Transparency%20in%20Tracking%20Maji%20Ndogo's%20Water%20Funds%20(Part%204)%203%20of%203.png" width="500" /></td>
  </tr>
</table>

*The final dashboard from Part 4, tracking the improvement project's progress and costs.*

## Conclusion

This project demonstrates the power of Power BI as a tool for data analysis and visualization. By progressing through the four parts of this project, we were able to transform raw data into a compelling narrative that not only highlights the challenges of the water crisis in Maji Ndogo but also provides a clear path forward for addressing them. The final dashboard serves as a valuable tool for monitoring the improvement efforts and ensuring that they have a lasting impact on the lives of the people of Maji Ndogo.
