# Stock Data API ETL Pipeline using Azure Cloud Stack
### __About Project👨‍💻__ 
The Propject deals with the development of Extract,Transform and Load (ETL) Pipeline of indian Stock data (BSE) API using Azure cloud stack.The stock data API available is moved in to databricks cloud platform file storage system and then Pyspark and databricks is employed for data transformation. The transformed data is moved in to Azure blob storage and then the Azure data Factory orchestration tool is used to copy the data from blob storage in to Azure SQL database. Finally the data from Azure SQL DB is accessed through POWER BI for Analytics and dashboarding.
The architecture diagram for the entire project is shown in below figure
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p1.png" /></a></p>

From the Bombay Stock Exchange (BSE) website were used to pick 50 stock list.The BSE libraray is used to fetch the API of 50 stock data obtained previously from BSE website.
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p2.png" /></a></p>
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/Databricks1.jpg" /></a></p>
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p3.png" /></a></p>
The data fetched is moved in to the file storage system of databricks clound platform, from which the data transformation is carried out with pyspark and databricks. 
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p4.png" /></a></p>
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p5.png" /></a></p>
The transformed is intially moved in to azure blob storage system, from which the Azure data factory tool is used to copy the data from the blob storage in to the Azure SQL database system.
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p6.png" /></a></p>
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p7.png" /></a></p>
The data from the Azure SQL database is fetched by power BI and then the analytical study is performed and then a dashboard is developed to generate the insights..
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p8.png" /></a></p>

