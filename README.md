# Taxi-Trip-Data-Analysis-Project

The data set we use is Yellow and green taxi trip data from NYC’s government website.The data project would help us using data from this website and storing it in Google Cloud Storage and then we shall be using Mage for our ETL pipeline. Through Mage we’ll push our project’s data into Google Big Query. And as a final step, we’ll create our dashboard on Looker Studio to visualise the data we transformed and analysed.
![image](https://github.com/ShivaniYS/Taxi-Trip-Data-Analysis-Project/assets/87171146/0b197c89-2f57-4ec7-ba5f-85260b73d21b)
Let me start by explaining the different technologies listed above. The GCP (Google Cloud Platform) is Google’s suite of cloud computing products and services that are provided for various use cases. The GCP services that we shall use are :

1.Google Cloud Storage: Its an online file storage which is provided as a service by GCP. It helps us store, retrieve files from anywhere in the cloud with an internet connection.
2.Google Compute Engine: Its the part of the GCP suite that helps us run virtual machines to run our applications. Its easy to create, run and maintain applications on GCP’s compute engine.
3.BigQuery: Its a warehouse provided by Google which helps us store, analyse large scale data sets using a SQL type interface and query language. Its cost effective and highly scalable based on our data size and requirement.
4.Looker: Looker Studio is a BI web based tool used for visualisation and reporting purposes. It can take data from multiple sources including Google sheets, BigQuery etc to create interactive dashboards that can convert our data into great charts and enhance the readability of complex datasets.

There are various other tools and technologies that is used for this project apart from GCP services are: 
1.Google collab :This platform helps in running notebook documents via the web browser. Its a great platform to test codes before putting them in production.
2.Maze: Mage is the latest open source tool to set up your ETL pipeline. This tools helps you with focussing only your business logic using certain existing templates it provides to — ‘load’,’transform’ and ‘extract’ the data. 
3.Lucidchart: Lucidchart is a diagramming software which helps you create design diagrams, flow charts etc for your project. This visual tool is helpful when we want to explain an end to end flow of any project , module to any person who may or may not speak the tech terminology. The free version can help you create upto three diagrams — https://www.lucidchart.com/.

4. Data Modelling: Data modelling is the process of creating visual representation of the data in the entire system or parts of it to understand the connections between each data element. While creating data models its imperative to have understanding of fact and dimension tables.

FACT TABLE: This type of table contains all quantitative measures that we use for analysis. Eg: If we look at school data- number of students, total classes, total number of teachers, total number of departments etc can be stored in fact table. Simply put, its a table which has numbers for the metrics.

DIMENSION TABLE: This type of table contains details/description of the attributes of data. Eg: For students, we shall have columns like student name, date of birth, address etc in these type of tables.

5. Data Dictionary: This contains a comprehensive list of all data elements and their descriptions. In any big organisation when the tables go up higher in number the data tracking can be difficult so a data dictionary can help in consolidating all data points and their descriptions. This is highly useful when we build our data models. For this project the data dictionary can be found here — https://www.nyc.gov/assets/tlc/downloads/pdf/data_dictionary_trip_records_yellow.pdf.
6. ![image](https://github.com/ShivaniYS/Taxi-Trip-Data-Analysis-Project/assets/87171146/de1f5c48-519c-4672-9150-73633e7e89ae)
7. 




