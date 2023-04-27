# Twitter-Data-Pipeline-with-Airflow



The project involves setting up an ETL (Extract, Transform, Load) pipeline to extract data from Twitter using Tweepy, store the data in AWS S3 storage, and then load formatted data into a Redshift data warehouse for sentimental analysis. 

To automate and run scheduled jobs, the project uses Airflow's DAG (Directed Acyclic Graph) concepts to orchestrate the pipeline. DAG is a collection of tasks arranged in a way that they can be executed automatically in a particular order. 

The overall process involves the following steps:
1. Setting up the necessary AWS infrastructure, including S3 storage and Redshift data warehouse.
2. Creating a Python script that uses Tweepy to extract 1 million tweets from Twitter.
3. Storing the extracted tweets in S3 storage, making sure the data is secure and can be accessed easily.
4. Formatting the stored data and then loading it into the Redshift data warehouse for sentimental analysis.
5. Setting up Airflow's DAGs to automate the entire process, ensuring that the tasks are executed in a specific order.

By leveraging Airflow and AWS services, the project streamlines the process of data ingestion, processing, and analysis, making it easier and faster for analysts to access and analyze Twitter data.
