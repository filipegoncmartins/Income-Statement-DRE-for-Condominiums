
# Income Statement (DRE) for Condominiums

This Power BI report provides a comprehensive analysis of the historical financial statements (DRE) for multiple shopping centers, as well as tracking other related expenses. The key features of the report include:

1) Revenue Analysis: Detailed breakdown of income streams from different sources within the shopping centers.
2) Expense Tracking: Categorization and analysis of various expenses, including operational costs, maintenance, and administrative expenses.
3) Profit and Loss Overview: Historical data showcasing the profit and loss trends over time for each shopping center.
4) Comparative Analysis: Comparative performance metrics between different shopping centers to identify high and low performers.
5) Other Expenditures: Tracking and analysis of additional expenses not directly tied to the shopping centers, providing a holistic view of the financial health. 

This report aids in making informed financial decisions, optimizing operational efficiency, and improving the overall financial health of the shopping centers and associated entities.

### Dashboard Link : https://app.powerbi.com/groups/me/reports/b9b2a131-a6b8-420d-bfdb-25267e2a2310?ctid=7dc647e5-6288-496e-9c52-70467492ebf3&pbi_source=linkShare

## Problem Statement

Managing the financial performance and expenses of multiple shopping centers presents significant challenges, such as consolidating disparate financial data, accurately tracking and categorizing expenses, and comparing the performance of different centers. These difficulties hinder the ability to identify trends, forecast future performance, and make informed strategic decisions. Additionally, a comprehensive view of all related expenditures, not just those specific to shopping centers, is necessary for a complete financial picture. 

The goal is to develop a Power BI report that addresses these issues by providing a unified platform for data consolidation, expense tracking, comparative analysis, and historical insights, ultimately improving financial management and decision-making.


### Steps followed 

1) Data Collection: Gather financial data from various sources such as accounting systems, ERP systems, and Excel spreadsheets. This data includes income statements, expense reports, and other relevant financial documents.

2) Data Import: Import the collected data into Power BI. In this particulas case was used a cvc file and several Excel's.

3) Data Transformation and Cleaning:

Data Formatting: Standardize the format of all imported data to ensure consistency. This includes formatting dates, numbers, and text fields uniformly across all datasets.

Handling Missing Values: Identify and address any missing or incomplete data by filling gaps, using averages or other imputation methods, or excluding incomplete records where necessary.

Data Validation: Ensure that the data is accurate and reliable by cross-referencing with source documents and correcting any discrepancies.

4) Data Merging:

Table Merging: Combine tables from different sources that contain related information. For example, merge income statements with corresponding expense reports to create a unified financial dataset.

File Consolidation: If multiple files within a folder contain related data (e.g., annual reports), consolidate these files into a single comprehensive dataset. This can be automated using Power BI’s “Combine Files” functionality.

5) Data Transformation in Power Query:

Normalization: Normalize data to ensure that similar information is categorized consistently across different tables.

Calculation Columns and Measures: Create calculated columns and measures to derive key financial metrics such as profit margins, growth rates, and expense ratios.

Data Enrichment: Enhance datasets with additional information, such as adding financial periods, categorizing expenses, or integrating external data like market benchmarks.

6) Data Modeling:

Relationship Mapping: Define relationships between tables to create a robust data model that accurately reflects the connections between different datasets.

Hierarchies: Create hierarchies (e.g., by time period, department, or expense category) to enable drill-down analysis.

7) Report Design:

Visualization Creation: Develop visualizations such as bar charts, line graphs, pie charts, and tables to represent financial data visually. Each visualization should be designed to provide clear insights into specific aspects of the data.

Dashboard Development: Assemble visualizations into interactive dashboards that allow users to explore the data dynamically. Ensure the dashboards are user-friendly and provide meaningful insights at a glance.

Interactivity: Implement filters, slicers, and drill-through actions to allow users to interact with the data and focus on specific areas of interest.

8) Validation and Testing:

Data Accuracy: Verify that the data displayed in the report is accurate and matches the source data.

Performance Testing: Ensure that the report performs efficiently, even with large datasets, by optimizing data models and visualizations.

9) Deployment and Sharing:

Publishing: Publish the report to the Power BI Service or an on-premises Power BI Report Server.

Access Management: Set up user roles and permissions to control access to the report and ensure data security.

User Training: Provide training to end-users on how to navigate and utilize the report effectively.


By following these steps, the Power BI report will provide a comprehensive, accurate, and insightful view of the financial performance and expenses of various shopping centers, enabling better financial management and strategic decision-making.

# Row-Level Security (RLS)

Row-Level Security (RLS) is a crucial feature in Power BI that controls access to data at a granular level. By implementing RLS, organizations can restrict data visibility for users based on their roles and permissions, ensuring that individuals only see the data pertinent to their responsibilities. This enhances data security, maintains confidentiality, and complies with regulatory requirements. Additionally, RLS fosters a personalized user experience by presenting relevant data, which improves decision-making efficiency and overall operational integrity.

### Setting the access

![aaa](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/1c596c9f-3ed9-4284-b571-02cab2b7352d)

### Including the Users

![aaa](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/a4cef744-ef8d-4b25-8f07-33ab3491dbcf)


# Snapshot of Dashboard (Power BI Service)

### Front

The home page serves as the central hub for users, offering access to various tabs and features. Depending on the Row-Level Security (RLS) settings, users can see and interact with different reports, dashboards, and datasets tailored to their specific permissions. This ensures that each user only accesses the data relevant to their role, enhancing data security and personalized user experience.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/94ed5e0e-3b93-40da-965c-1715f242cf63)

### General Values

Page two of the Power BI report displays general values with a monthly chart showing the cumulative total. The tabs can be switched using the navigation at the bottom of the visual, allowing for a more efficient use of space and a clearer presentation of data. This layout enhances the user's ability to focus on the key metrics by maximizing the visual area available for detailed analysis.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/63c5bc7e-03cf-46a8-bf56-fce2e6a0f46d)

### KPI's

On the next page, the KPIs are explained over time, highlighting their trends and performance metrics. This page is designed to provide users with a comprehensive view of key performance indicators, showcasing their progress and variations throughout specific periods. This temporal analysis helps in understanding the trajectory and effectiveness of various initiatives and strategies.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/f0ec0402-7e1d-403c-99ed-1e44a092bb6d)

### Comparative Monthly

On the next page, a monthly comparison of actual versus budgeted values is displayed alongside the same month from a previous year selected by the user. To the right, the main KPIs are presented for in-depth analysis. This setup allows users to evaluate performance against targets and historical data, providing insights into trends and variances.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/833b1fb0-63ac-41c3-803a-8080e6055b05)

### Accumulated Comparison

On the next page, a comparison of the accumulated actuals up to the user-selected month is displayed against the budget for the same period and the actuals from a previous year chosen by the user. To the right, the main KPIs are presented for detailed analysis. This layout allows users to assess performance over the specified period, providing insights into how current results stack up against targets and historical performance.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/3518fdfd-518c-4a57-adf3-e471cc95bd20)


### Annual Forecast

On this page, a forecast of the actual values by the end of the annual period is shown. This predictive analysis helps users anticipate end-of-year outcomes based on current trends and performance data, enabling more informed decision-making and strategic planning.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/d687c43f-54a5-4127-8136-2783a3b31e19)

### Shopping Mall Segmentation

On this page, the revenues and expenses of all shopping centers are displayed side by side. The user has the option to view either the selected month or the accumulated values through a toggle button. This feature allows for a flexible and detailed comparison of financial performance across different periods, facilitating a better understanding of individual and overall shopping center performance.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/df6e548e-b62f-4dd0-9b76-a6177249ca28)
 
 ### Water and Electricity Consumption

 In this view, the historical consumption of water and electricity is detailed, with an annual comparison in the same graph, freely chosen by the user. Next to it, the total consumption is compared with other shopping centers. This setup provides a clear perspective on utility usage trends over time and how each shopping center's consumption stacks up against others, aiding in resource management and efficiency analysis.

![pic1](https://github.com/filipegoncmartins/Income-Statement-DRE-for-Condominiums/assets/148718210/be2be4b8-ed6d-4ccb-8dac-ce3cf53c75d8)


# Insights

The published file has been modified to exclude sensitive names and values for public viewing. However, here are the key insights obtained from the original file:

### [1] Performance Trends: 

Detailed KPIs over time highlighted significant performance trends, revealing which areas are excelling and which need improvement. The original file had the names and expenses of all suppliers so it was possible to make a quick analyse of with suppliers are the best value for money.

### [2] Budget vs. Actuals: 

Monthly and cumulative comparisons of actuals versus budgeted values helped identify variances and assess financial health. It helps the management to know where it have to save for don't overpass the budget.

### [3] Forecasting: 

End-of-year forecasts provided valuable predictions, aiding in strategic planning and resource allocation.

### [4] Utility Consumption: 

Historical data on water and electricity consumption, with annual comparisons, shed light on resource usage efficiency and potential cost-saving opportunities. This visual was very important to realise a structural problem in Mall 2 seeing the month and year where the expense growth and identify the reform that create this issue.

### [5] Shopping Center Comparisons: 

Side-by-side financial analysis of all shopping centers, both for selected months and accumulated periods, facilitated benchmarking and performance evaluation.

### [6] Sensitive Data Protection: 

Ensuring sensitive data protection while still delivering meaningful insights demonstrated a commitment to data privacy and security.

