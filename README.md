# PySpark Pipeline Tutorial

## Summary

This repository consists of some tutorials and templates for basic tasks in data analytics with PySpark. This is not an introduction to the tasks, but rather a tutorial to adapt to PySpark with prior knowledge in Python and data analytics. I am also not discussing how to set up your Hadoop/Spark cluster here. However, the easiest way is to use the Hortonworks HDP virtual machine (https://www.cloudera.com/downloads/hortonworks-sandbox.html). Topics included in this repository: 

- Data processing pipeline
    - One hot encoder for categorical data
    - Imputation missing values
    - Standardization for numeric data
- Tuning classification models
    - Logistic regression
    - Decision tree
    - Random forest
    - Gradient boosting model
    - Multilayer perceptron
- Tuning regression models
    - Linear regression
    - Decision tree
    - Random forest
    - Gradient boosting model
    
## Repository structure

- Data: sample data sets. They should be loaded to a HDFS cluster.
- Jupyter notebooks: include the codes in Jupyter notebook format.
- Zeppelin notebooks: include the codes in Zeppelin notebook format which are json files. GitHub cannot render these natively.

The user parameters for pipelines are discussed in `pipeline_explained` notebook. The other three are more of set-up-and-run, so they do not have too much explanation.


```python

```
