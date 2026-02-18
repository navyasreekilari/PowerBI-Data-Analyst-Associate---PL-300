Data Analysis
Data Analysis focuses on the tasks of cleaning, modleing and visualizing data, the concept od data analysis and its importance to business should not be understated.
To analyze data, core components of analytics are divided into the following categories:
* Descriptive Analytics: It answers questions about "What has happend" based on historical data. By developing KPIs and using metrics like ROI. Best example is generating reports to provide a view of an organization's sales and financial data.
* Diagnostic Analytics: It answers questions about "Why events happened". KPI's ar einvestigated to discover why events improved or became worse.
* Predictive Analytics: It answers questions about 'What will happen" in the future. Techniques include a variety of statistical and machine learning techniques such as neural networks, decision trees and regression.
* Prescriptive Analytics: It answers questions about "which actions should be taken to acheive a goal or target". It relys on machine learning as one of the strategies to find patterns in large semantic models.
* Artificial Intelligence: It answers questions about "your data". It supports a wide range of applications, from natural language processing and image recognition to code generation and intelligent visualization suggestions.

Tasks of a data analyst:
* Prepare: Data preparation is the process of profiling, cleaning and transforming your data to get it ready to model and visualize. It is the process of taking raw data and turining it into information that is trusted and understandable. It also invlolves undrstanding how you're going to get and connect to the data and the performance implications of the decisions.
* Model: When the data is in a proper state, it's ready to be modeled. It is the process of determining how your tables are related to each other. It is done by defining and creating realtionships between the tables.
* Visualize: The ultimate goal of visualize task is to solve business problems. An important aspect of visualizing data is designing and creating reports for accessibility. As you build reports, it is important to think about people who will be accesing and reading the reports.
* Analyze: It is important step of understanding and interpreting the information that is dispalyed on the report. As a data analyst, one should understand the analytical capabilities of Power BI and use those capabilities to find insights, identify patterns and trends, predict outcomes and then communicate those insights in a way that everyone can understand.
* Manage: Power BI consists of many componets, including reports, dashboards, workspaces, semantic models and more. Data anlyst is responsible for the management of these PowerBI assets, overseeing the sharing and distribution of items such as reports and dashboards, and ensuring the security of Power BI assets.

They are 3 primary components to PowerBI:
> Power BI Desktop : Use to connect to data and create the report.
> Power BI Service : Then publish the report to the Power BI service and distribute to users.
> Power BI Mobile



Basic flow of Power BI:
> Connect to data with Power BI Desktop
> Transform data with Power Query Editor
> Model data with Power BI desktop
> Create Visualizations and reports with Power BI Desktop
> Publish report to Power BI service.
> Distribute and manage reports in the Power BI service.
Power BI service allows to create high-level dashboards that drill down to reports, and apps to easily group realted reports to users in simple format.

Building Blocks of Power BI
> Create a Semantic Model: A semantic model consists of all connected data, transformations, relationships and caluclations. To follow the flow of Power BI, you first connect to data, transform data and create relationships and caluclations to create a semantic model.
> Create visualizations in a report: In Power BI Desktop, when you create visual you add it to the canvas for a report page. Power BI is a low code solution, you can just 'drag and drop' data field directly onto canvas. Once you're satisfied with your report, you publish them to Power BI service.
> Create a dasboard: In the PowerBI service, you can also create dashboards after you've published a report. Dashboards consists of a single page made up of tiles. Add tiles to a dashboard by pnning a visual in a report to the dashboard.



End-to-End Analysis using microsoft fabric

Microsoft Fabric is an en-to-end analytics platform that provides a single, integrated environment for data professionals and the business to colloaborate on data projects. It provides set of integrated services that enable you to ingest, process, store and analyze data in a single environment.

It provides services like:
>Data Engineering
>Data integration
>Data warehousing
>Data Science
>Real-time intelligence
>Business Intelligence

It also integrate with Copilot, a generative AI assistant that enhances productivity across all workloads by providing intelligent code completion, natural language to SQL conversion, automated insights and contextual assisatance for data professionals and business users alike.
Fabric is a unified SaaS platform where all data is stored in a single open format in OneLake. Onelake is accessible by all analytics engines in the platform, ensuring scalability, cost-effectiveness and accessibility from anywhere with an internet connection.

OneLake: Onelake is Fabric's centralized data storage architecture that enables collaboration by eliminating the need to move or copy data between systems. It unifies data across regions and clouds into a single logical lake without moving or duplicating data.
It is built on Azure Data Lake Storage (ADLS) and supports various formats, including delta, Parquet, CSV and JSON.
Shortcuts are references to files or storage locations external to Onelake, allowing you to access exisitng cloud data without copying it. 

<img width="868" height="535" alt="image" src="https://github.com/user-attachments/assets/e95e113e-e163-4e7c-aa34-eafddb88b2e2" />

Enable and Use Microsoft Fabric:
>Fabric Admin: Fabric setting and configurations.
>Power Platform admin: Oversees Power Platform Services, including Fabric.
>Microsoft 365 admin: Manages organization-wide Microsoft services, including Fabric.

Create Workspaces: Workspaces are collaborative environments where you can create and manage items like lakehouse, warehouses and reports. All data is stored in OneLake and accessed through workspaces. 
In workspace settings, you can configure:
> License type to use Fabric Features.
> OneDrive access for the workspace
> Azure Data Lake Gen2 Storage connection
> Spark workload settings for performance optimization.

You can manage workspace access through four roles: admin, contributor, member and viewer. 

Discover data with OneLake catalog:
It helps users easily find and access various data sources within their organization. Below are some considerations when using Onelake catalog:
> Narrow results by workspaces or domains
> Explore default categories to quickly locate relevant data.
> Filter by keyword or item type



Use Copilot in Power BI to prepare and model data
Prepare data in Power Query
Use Powery query editor to profile, clean and transform your data:
> Profile: Assess columm quality, distribution and profile
> Clean: Address missing values, correct out of range or inconsistent entries and remove duplicates.
> Transform: Rename columns, set correct data types and reshape tables as needed.

Confiure a semantic model: Relationships allow you to filter and summarize data in report visuals later in the development process. You can use the autodetect relationships feature to get you started, then use Copilot to summarize the initial semantic model to determine if any other relationships are needed.

Query with DAX:  In the DAX Query view, you can select Copilot in the ribbon and use natural language to describe what you want.

Create reports with Copilot in Power BI: Copilot in Power BI helps you build interactive reports faster by turning your ideas into report elements with just a prompt. You can use suggested prompts or enter your own to create new report pages, suggest content, or answer specific data questions in the Copilot pane.
<img width="507" height="540" alt="image" src="https://github.com/user-attachments/assets/ab23e4b2-f852-4155-9bcc-29359bb00c49" />

Create reports in the Power BI service: When you create reports in Power BI Desktop and publish them, both the semantic model and the report are saved in your workspace. The semantic model contains your data, relationships, and measures, while the report is the visual layer you design.

Copilot can also help create reports based on semantic models in the Power BI service. To get started, select the ellipsis (...) next to your semantic model and choose Create report.
<img width="867" height="232" alt="image" src="https://github.com/user-attachments/assets/b4e66afe-7608-4894-a5cd-d7c80ccadc06" />

Get your data ready for AI usage in Power BI
Prepare your semantic model: Once you create your semantic model and report, you can use the Prep data for AI features to further curate the business user's experience. These features provide Copilot with the context it needs to reduce ambiguity and improve relevance and accuracy. These features are available in the Prep data for AI dialog box.

Simplify the data schema: by removing unnecessary tables and columns, and using clear, descriptive names. For example, you might have objects necessary for your report that aren't relevant to business users, such as ID columns. IDs are essential for relationships, but Copilot doesn't need to use them when answering user questions.
Verfied Answers: associate common business questions with specific visuals. For example, a visual for Total Opportunities by Sales Stage can answer many different questions for different users. When you create a verified answer, you can choose from suggested questions or create your own. When users ask that question in Copilot, your verified answer is included in the response.
Prvide AI instructions: with key business context and domain-specific logic to Copilot to help tailor responses. AI instructions help clarify business terms, guide analysis approaches, and provide critical data context. Once saved, these instructions are used by Copilot to respond more intelligently to user prompts. For example, tell Copilot if your industry usually sees a spike in activity on the first Friday of each month, so Copilot understands this behavior and related terms in user chats.
<img width="852" height="298" alt="image" src="https://github.com/user-attachments/assets/86819e6e-9429-44c6-950a-4c0954e395f4" />

Test and mark the model: It's important to test your model to validate that you get expected results before marking the model as reviewed. Once you're confident that your schema is simplified, your verified answers are configured, and your AI instructions are updated, you can mark the semantic model as Prepped for AI. You can configure this property for the semantic model in the Power BI service.
<img width="845" height="407" alt="image" src="https://github.com/user-attachments/assets/3c247559-35a8-4caf-a380-9b9c4c92194c" />

Chat with your copilot: In Power BI service, users simply select Copilot to chat with the data, such as:

Ask questions: Use everyday language to query your data, such as "What were our top sales regions last quarter?"
Interpret answers: Copilot provides responses with supporting visuals and explanations of how it arrived at the answer.
Summarize findings: Quickly generate summaries to share insights with others or inform decision-making.
<img width="842" height="535" alt="image" src="https://github.com/user-attachments/assets/5623bbb2-bca6-405e-80e8-437417165121" />


Prepare data for Analysis with Power BI (Module 2)
Get data from files: You can get data form different type of files in Power BI (like JSON, Excel worksheet, SQL server, CSV, txt,...)
Get data from relational data sources: Connecting Power BI to your database will help you to monitor the progress of your business and identify trends, so you can forecast sales figures, plan budgets and set performance indicators and targets. Power BI Desktop can connect to many relational databases that are either in the cloud or on-premises.

Create dynamic reports with Parameters: Dynamic reports are reports in which the data can be changed by a developer according to user specifications. Dynamic reports are valuable because a single report can be used for multiple purposes. If you use dynamic reports, you'll have fewer individual reports to create, which will save organizational time and resources.

Storage Mode

They are 3 different types of storage modes we cna choose from:

. Import: This mode allows you to create a local Power BI copy of your semantic models from your data source. We canuse all Power BI service feature with this storage mode, including Q&A and quick insights. Data refreshes can be scheduled or on-demand. Import mode is the default for creating new Power Bi reports.

. DirectQuery: It is useful when you don't want to save local copies of your data because your data won't be cached. Using this model ensures that you're always viewing the most up-to-date data, and that all security requirements are satisfied. Additionally this mode is suited for when you have large semantic models to pull data from. Instead of slowing down performance by having to load large amounts of data into power bi, you can use DirectQuery to create a connection to the source, solving data latency issues as well.

. Dual(composite mode): In this mode you can identify some data to be directly imported and other data that must be queried. Any table that is brought in to your report is a product of both Import and DirectQuery modes. Using the dual mode allows Power BI to choose the most efficient form of data retrieval.

Fix Performance issues

Optimize performance in Power Query: The performance in Power Query depends on the performance at the data source level. The variety of data sources that Power Query offers is wide, and the performance tuning techniques for each source are equally wide.Power Query takes advantage of good performance at the data source through a technique called Query Folding.

Query Folding: Query folding is the process by which the transformations and edits that you make in Power Query Editor are simultaneously tracked as native queries, or simple Select SQL statements, while you're actively making transformations. The reason for implementing this process is to ensure that these transformations can take place in the original data source server and don't overwhelm Power BI computing resources. 
You can use Power Query to load data into Power BI. Then use Power Query Editor to transform your data, such as renaming or deleting columns, appending, parsing, filtering, or grouping your data.

Benefits of query folding: More efficiency in data refreshes and incremental refreshes, automatic compatibility with directquery and dual storage modes.

Native queries aren't possible for the following transformations:
> Adding and index column
> Meging and appending columns of different tables with two different sources.
> Changing the data type of a column

Query diagnostics: Another tool that you can use to study query performance is query diagnostics. To access query diagnostics in Power Query Editor, go to Tools in the Home ribbon. When you're ready to begin transforming your data or making other edits in Power Query Editor, select Start Diagnostics in the Session Diagnostics section. When you're finished, make sure that you select Stop Diagnostics.

Other techniques to optimize performace:
> Process as much data as possible in the original data source
> Use native SQL queires
> Seperate date and time, if bound together.

CLean, transform, and load data in Power BI

Shape the initial data:
Power Quey editor in Power BI Desktop allows you to shape your imported data. You can accomplish actions such as renaming columns or tables, changing text to numbers, removing rows, setting the first row as headers, and much more.
<img width="841" height="352" alt="image" src="https://github.com/user-attachments/assets/c69d5f49-8c5d-4778-8fea-309b658c5b10" />

Get Started with PowerQuery Editor:
> To start shaping your data, open Power Query Editor by selecting 'Transform data' optin on the Home tab of Power BU Desktop:
<img width="860" height="251" alt="image" src="https://github.com/user-attachments/assets/d6f52636-c01c-483d-9472-c846e8309a39" />

When you start working in Power Query Editor, all steps that you take to shape your data are recorded. Then, each time the query connects to the data source, it automatically applies your steps, so your data is always shaped the way that you sepcified. 

You can Pivot or Unpivot columns in PowerQuery.


Profile data in Power BI

Profiling data is about studying the nuances of the data: determining anomalies, examing and developing the underlying data structures, and querying data statistics such as row counts, value distributions, minimum and mazimum values, averages and so on. 

Examine data sturctures: Before you begin examining the data in Power Query Editor, you should first learn about the underlying data structures that data is organized in. You can view current semantic model under the "Model" tab on Power BI desktop.

Finding data anomalies and data statistics: We can find data anomalies by using the  'Colum distribution' feature. To understand data anomalies and statistics, select the 'Column distribution, column Quality and Column Profile ' options. 
<img width="1439" height="390" alt="image" src="https://github.com/user-attachments/assets/1bf40e26-d434-4c3c-addf-c63ba0cda071" />

Column distribution shows you the distribution of the data within the column and the counts of distinct and unique values, both of which can tell you details about the data counts. 
Column profile gives you a more in-depth look into the statistics within the columns for the first 1,000 rows of data. This column provides several different values, including the count of rows, which is important when verifying whether the importing of your data was successful. 

Use Advanced Editor to modify M code

Each time you shape data in Power Query, you create a step in the Power Query process. Those steps can be reordered, deleted, and modified where it makes sense. Each cleaning step that you made was likely created by using the graphical interface, but Power Query uses the M language behind the scenes. The combined steps are available to read by using the Power Query Advanced Editor. The M language is always available to be read and modified directly.  It is not required that you use M code to take advantage of Power Query. You will rarely need to write M code, but it can still prove useful. Because each step in Power Query is written in M code, even if the UI created it for you, you can use those steps to learn M code and customize it to suit your needs.
<img width="732" height="145" alt="image" src="https://github.com/user-attachments/assets/1a91cae7-88ad-48dd-815c-6a55298d23b4" />

































  
