# Data Engineering Individual 3
## Purpose
The purpose of this project is to create a Databricks notebook that performs extract, transform, load (ETL) operations. Delta Lake is used for data storage and Spark SQL is used for data transformation. A visualization of data and an automated trigger are included in this project. The dataset used is a subset of the Million Song Dataset, a collection of features and metadata for contemporary music tracks.

## Steps 
1. Create a Databricks workspace on Azure
2. Create a cluster on Databricks
3. Create three notebooks that achieve the functionalities of extract, transform, and load (ETL) workflow.
   ![Screenshot 2023-11-11 at 4 12 32 PM](https://github.com/nogibjj/KatherineT.DE.Mini-Project_11/assets/143833511/8ee82802-ee99-4c66-9a34-1a4c2b21fc7a)
   
1) Load the raw data into a table to make it available for further processing. Downloads and stores the data in the Databricks FileStore.
![Screenshot 2023-11-11 at 4 07 32 PM](https://github.com/nogibjj/KatherineT.DE.Mini-Project_11/assets/143833511/8e15ad37-8cb3-4afe-baff-f9b7cac1f7f3)

2) Transform the data into a Spark dataframe to prepare it for analysis
![Screenshot 2023-11-11 at 4 09 25 PM](https://github.com/nogibjj/KatherineT.DE.Mini-Project_11/assets/143833511/01d9594e-d27f-4f89-b45f-d4ff1928d8cf)

3) Adding queries to analyze the songs data. Find the artist that releases the most songs each year
![Screenshot 2023-11-11 at 4 11 00 PM](https://github.com/nogibjj/KatherineT.DE.Mini-Project_11/assets/143833511/365d5ce6-d047-4fef-8028-17f96c6961bd)

4. Create a visualization
 
5. Create a workflow to automate running the data ingestion, processing, and analysis steps using a Databricks job. Change the filer conditions in the queries as you want and run the worflow to see the results. 

![Screenshot 2023-11-11 at 4 14 03 PM](https://github.com/nogibjj/KatherineT.DE.Mini-Project_11/assets/143833511/b52c03c7-689a-4392-a3dc-982d518132ee)

## Visualization
The 20 artisits with most songs released in 2008
![Screenshot 2023-11-11 at 7 25 20 PM](https://github.com/nogibjj/KatherineT.DE.Individual-Project_/assets/143833511/9a4d58e1-2b52-4a8a-83a9-fd8fcf4b8446)

## Video Memo
https://youtu.be/i2Z2bBNAKRg
