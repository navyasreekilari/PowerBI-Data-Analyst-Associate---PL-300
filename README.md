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




















  
