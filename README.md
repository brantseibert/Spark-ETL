# Spark-ETL
Pointers on using Spark to Extract, Transform, and Load your data.

## ETL TOPICS

### Kimball

The foundation for data analytics is a four step process outlined by Richard Kimball:
1. Select the business process.
2. Declare the grain.
3. Identify the dimensions.
4. Identify the facts. 

https://www.kimballgroup.com/data-warehouse-business-intelligence-resources/kimball-techniques/dimensional-modeling-techniques/four-4-step-design-process/

We start by highlighting the similarities and differences between Spark and traditional dimensional design.

### Machine Learning (ML)

Spark shines as the data processing engine for advanced Machine Learning, on data that is both large (think Genomic) and immediate (think Streaming), because End-to-End Deep Learning with today's Neural Networks improves in accuracy as the size of data grows.

https://databricks.com/blog/2018/06/05/introducing-mlflow-an-open-source-machine-learning-platform.html

### Combining ETL, Analytics, and ML

Reducing complexity is the key to empowering organizations with Artificial Intelligence.  Spark excels at reducing complexity by providing a single framework to:
* Ingest batch and streaming data;
* Optimize data formats in memory and on disc; and
* Orchestrate end-to-end analytic and data science pipelines.

https://databricks.com/blog/2018/08/09/building-a-real-time-attribution-pipeline-with-databricks-delta.html

### Connect

* JDBC
* Cloud Blob Storage

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3937215438089361/4051336435620913/4692050933620676/latest.html

### Define Schema

* Infering vs. Defining Schemas
* Flat and Nested Schemas (e.g. JSON) 

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3937215438089361/4051336435620926/4692050933620676/latest.html

### Clean

Handling Corrupt Records
- [ ] PERMISSIVE
- [x] DROPMALFORMED
- [ ] FAILFAST

https://databricks-prod-cloudfront.cloud.databricks.com/public/4027ec902e239c93eaaa8714f173bcfc/3937215438089361/4051336435620938/4692050933620676/latest.html

### Load

* Raw
* Parquet
* Databricks ETL Jobs

### Transform

* User Defined Functions (UDF)
  - Simple UDFs
  - Multivariate UDFs

### Join

* Tables and Partitions
* Structured Streaming
* Join Batch and Streaming Data

### Writing to a Database
