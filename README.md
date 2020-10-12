## AWS Glue vs. Spark

While Amazon's Glue service can automatically create certain types of ETL transformations using its Glue DynamicFrame Spark subclass and wizard, many (like myself) might prefer to write the Glue or Spark code directly. This hands-on approach is certainly more extensible and allows for more control over pipeline flow.

AWS Glue has decent documentation, but it took some work to tease out the syntax for using PySpark correctly. This repo contains a Jupyter Notebook (Sagemaker in Amazon-speak) with several examples using a public dataset.
