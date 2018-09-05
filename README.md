# Spark-ETL
Pointers on using Spark to Extract, Transform, and Load your data.

## ETL TOPICS

### Kimball

The foundation for data analytics is a four step process outlined by Richard Kimball:
1. Select the business process.
2. Declare the grain.
3. Identify the dimensions.
4. Identify the facts. 

We start by highlighting the similarities and differences between Spark and traditional dimensional design.

### Machine Learning (ML)

Spark shines as the data processing engine for advanced Machine Learning, on data that is both large (think Genomic) and immediate (think Streaming), because End-to-End Deep Learning with today's Neural Networks improves in accuracy as the size of data grows.  Spark cost-effectively orchestrates the memory and CPUs required for distributed computation.

### Combining ETL, Analytics, and ML

Reducing complexity is the key to empowering organizations with Artificial Intelligence.  Spark excels at reducing complexity by providing a single framework to:
* Ingest batch and streaming data;
* Optimize data formats in memory and on disc; and
* Orchestrate end-to-end analytic and data science pipelines.

### Connecting

* JDBC
* Cloud Blob Storage

### Schemas

* Infering vs. Defining Schemas
* Flat and Nested Schemas (e.g. JSON) 

### Corrupt Records

- [ ] PERMISSIVE
- [ ] DROPMALFORMED
- [ ] FAILFAST

### Load

* Raw
* Parquet (columnar)
* Databricks ETL Jobs

### Transform

* User Defined Functions (UDF)
  - Simple UDFs
  - Multivariate UDFs

### Joins

* Predicate Pushdown
* Tables and Partitions

### Writing to a Database
