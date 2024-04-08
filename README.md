# Stock DATA API ETL Pipeline using Azure Cloud Stack
### __About Project👨‍💻__ 
The Propject deals with the development of Extract,Transform and Load (ETL) Pipeline of Pizza Sales data using Azure cloud stack.The sales data is available in on premies SQL server and as the source data and it is moved in to Azure blob storage through the copy activity of the Azure Data Factory. the self hosted integration runtime were used for the copy activity from source to sink system. 
the architecture diagram for the entire project is shown in below figure
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p1.png" /></a></p>

The sink system used in thr project is the container developed in Azure storage. The container is then mounted in to the Azure Databricks and then the Pyspark is used to perform different transformation on the data. The transformed data is aggregated and sent in to azure blob storage.
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p2.png" /></a></p>
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p3.png" /></a></p>
Finally the data is moved from the blob container in to Microsoft Power BI to get the Analytics details above the data. The dashboard is developed which gives the insights on total pizza sold,total order, Total sales,Filters on Month,day and order time. 
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p4.png" /></a></p>
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p5.png" /></a></p>
The sum of order dales and total orders with Month name, distribution of pizza size with pizza sales, distribution of pizza sales with pizza category. the details of orders with day name and sum of the total pizza sales with pizza name.
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p6.png" /></a></p>
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p7.png" /></a></p>
The project can help to make business decisions based on the insights gained from dashboard and data.
<p  align="center"><img width="80%" src="https://github.com/anandaiml19/DE_Zoomcamp_Project2/blob/main/p8.png" /></a></p>

