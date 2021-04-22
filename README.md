# ADFExamples
Repository containing examples of common Azure Data Factory use cases

## Overview of templates

### Read_Write_Delta

Provides an example of writing and reading from/to Delta format using ADF Data Flows using the https://data.cityofnewyork.us/Transportation/2019-Yellow-Taxi-Trip-Data/2upf-qytp data set.

**Specifically:**

* Write to Delta format (converting from delimited)
* Write to Delta format using year / month / day partitioning
* Append data to Delta format
* Read from a specific version of Delta format

### Write_Partitioned_Parquet

Example of writing to partitioned parquet using the https://data.cityofnewyork.us/Transportation/2019-Yellow-Taxi-Trip-Data/2upf-qytp data set.

**Specifically:**

* Read from delimited format, create partition keys based on Year / Month / Day, ouptut to ADLS gen2.
