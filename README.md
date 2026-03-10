Question 1 : What is Power BI and why is it used in businesses?
Power BI is a Microsoft business intelligence platform that connects to various data sources to create interactive, real-time data visualizations, reports, and dashboards.
Businesses use it to analyze performance, uncover insights, and make data-driven decisions quickly without requiring advanced technical skills

 Question 2 : Name and explain the three main components of Power BI.
  Power BI’s three main components are:
1-	Power BI Desktop -for data connection, modeling, and report creation
2-	Power BI Service -a cloud-based SaaS for sharing and viewing reports
3-	Power BI Mobile -apps for accessing insights on mobile devices 

 Question 3 : Explain the Power BI workflow. 
Power BI workflow involves connecting to raw data sources, cleaning and transforming it in Power Query, modeling the data with relationships and DAX, visualizing it in reports, 
and publishing to the Power BI Service for sharing

Question 4 : List any four data cleaning tasks that can be performed in Power Query
Four common data cleaning tasks that can be performed in Power Query are :
•	Handling missing values: identify and address missing or null data by removing rows/columns that contain them.
•	Removing duplicates: Power Query allows you to easily find and eliminate duplicate rows in a dataset 
•	Changing data types: Power Query provides options to correctly assign data types .
•	Trimming and cleaning text: You can remove leading/trailing extra spaces and non-printable characters from text .

Question 5 : Write step by step instructions to load the above dataset. 
Steps are: 
1-	Open power bi
2-	Select Get Data from excel workbook option
3-	Select desired file
4-	click on transform
5-	Check from the column quality option, wheather the data is ready to use or not
6-	If yes, then click on close and apply from home tab.
7-	If no, then check whether the rows are empty, wrong data format or anything else and clean accordingly.
8-	After transformation load it from home tab.

Question 6 : Define Data View, Report View, and Model View. Explain the purpose of each view.
Data View: A tabular view of your data after it has been loaded and transformed by Power Query.
It is used to inspect and enhance the data, this view allows you to see the actual rows of data in your model. It is primarily used to create DAX calculated columns and to verify that
 data types are correct before building visuals.
Report View: The default canvas where you build your visualizations and dashboards. It is used to design the user interface. It is used to arrange layouts, apply themes, and 
configure the interactive experience for the end-user.
Model View: A diagrammatic representation of all the tables in your dataset and the connections between them.It is used to manage data architecture. It is used to create relationships 
(like One-to-Many), set up hierarchies.

 Question 7 : Discuss the different data sources that Power BI supports. 
Power BI Desktop organizes these connectors into the following searchable categories:
1-	MS Excel
2-	SQL Server
3-	CSV
4-	Google Sheets
5-	Snowflake
6-	Web
7-	Azure
8-	Json

8-	Rename Columns: Power Query will create Owner_Name.1 and Owner_Name.2. Double-click the headers to rename them to First Name and Last Name.
