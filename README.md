# SQL-Server-API-and-PowerBI-Intergration

Objective
This project involves setting up a robust data pipeline to streamline the flow of data from the Fixer API into Power BI, providing users with up-to-date insights of the Euro Dollar exchange rate to other currencies. The solution showcases expertise in SQL Server configuration, data integration, and reporting setup on a Windows Server 2019 environment.

Solution Details

SQL Server Setup: The project begins with the installation and configuration of SQL Server on a Windows Server 2019 machine. Custom SQL commands are used to design and create tables optimized to store data retrieved from the Fixer API, ensuring an efficient and organized data structure.

Data Retrieval and Storage: A Python script is developed to connect to the Fixer API, retrieve the required data, and upload it to the SQL Server. This script is designed to handle data extraction, transformation, and loading (ETL) seamlessly, converting the API data into a structured format ready for storage.

Automated Data Refresh: To keep the data up to date, a scheduling mechanism is implemented using Windows Task Scheduler. This setup automates API pulls at specified intervals, ensuring fresh data is regularly added to the SQL tables without manual intervention.

Power BI Integration: Connections are established between SQL Server and Power BI, enabling users to access and analyze the stored data in real time. This integration provides a user-friendly interface in Power BI, allowing users to create custom reports and visualizations based on the latest API data.

Outcome
This project successfully demonstrates a full-cycle data integration pipeline from an external API to a reporting tool, showcasing proficiency in SQL Server setup, API integration, automation, and data visualization. The automated data refresh reduces manual workload and ensures timely, accurate data is available for analysis in Power BI, empowering users to make data-driven decisions.
