# Assignment4
In assignment 4 the task was to use different Spark tools to count the number of flights by each carrier, which is the same task as in assignment 3 but this time with the library “pyspark”.  The tools used were a Jupyter notebooks with Docker, Google Colab, Databricks, and the Saint Peter’s Data Science Lab. At the time of writing, I wasn’t given access to the lab yet, so code and screen shots are from the three other tools listed.

The code used in Databricks and Google Colab is pretty much the same. One difference is that in Google Colab the data came from my google drive and in Databricks the data was loaded in the Databricks file system. Another small difference was that a spark session had to be called in Google Colab. 

In the Jupyter notebooks with Docker, two different ways of obtaining carrier count and loading of files were executed. The notebook with “sparkcontext” in the file name has the data loaded in as a text file. Once loaded in to the notebook the code used to obtain carrier count was similar to the code in Google Colab and Databricks. The notebook with “Sparksession” in the file name has the data loaded in by using “read.csv”. Also, calculation of the carrier count was done differently. The data took a much longer time to be loaded with “read.csv”. 

