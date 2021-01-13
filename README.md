
# Univariate-Time-Series-Forecasting


![main_image](images/main_image.png)

Most of the time we deal with cross-sectional data. Here, the data is collected at a specific point in time. On the other hand, time series data is a collection of observations obtained through repeated measurements over time. 


## Table of Contents
1. [Introduction](#introduction)
2. [Software Requirements](#software_requirements)
3. [Folder Structure](#folder_structure)
4. [Getting Started](#getting_started)
5. [Overview of the ETL steps](#overview)
    1. [Simple_Pipeline](#simple_pipeline)
    2. [Pipeline_with_join](#pipeline_with_join)
    3. [Pipeline_with_join2](#pipeline_with_join2)
    4. [Pipeline_with_intermediate_storage](#pipeline_with_intermediate_storage)  
6. [Link to the Publications](#link_publications)    
7. [Authors](#authors)
8. [Motivation](#motivation)




<a name="introduction"></a>

## Introduction

In this repository I have deposited a Jupyter notebook which contains various neruonal networks for time series predictions. 
With this script you can quickly and easily check which type of neural network fits best to the data.

<a name="software_requirements"></a>

## Software Requirements

Required libraries:

+ Python 3.x
+ Numpy
+ Pandas
+ Matplotlib
+ Scikit-Learn
+ Tensorflow


Please run ```pip install -r requirements.txt```



<a name="folder_structure"></a>

## Folder Structure

```
C:.
│   Metro_Interstate_Traffic_Volume.csv
│   Neural Networks for Univariate Variables.ipynb
│
└───model
        bi_lstm_model_hs.h5
        bi_lstm_model_sss.h5
        cnn_model_hs.h5
        cnn_model_sss.h5
        ed_lstm_model_hs.h5
        ed_lstm_model_sss.h5
        gru_model_hs.h5
        gru_model_sss.h5
        lstm_model_hs.h5
        lstm_model_sss.h5
```

Neben dem Jupyter Notebook und dem Dataframe habe ich eine Model-Datei erstellt.
The created models are automatically saved in this directory when the script is executed.



<a name="getting_started"></a>

## Getting Started

1. Make sure Python 3 is installed.
2. Clone the repository and navigate to the respective project's root directory in the terminal
3. Use a command line of your choice and navigate to the respective project's root directory. Run the following commands:
    1. ```cd "path/to/root directory"```
    2. ```jupyter notebook"```
4. In the browser window that opens, select the Jupyter Notebook file.
5. Select the parameters of the neural network as desired.
6. Select *Cell* in the menu shown above and execute *Run All*.


<a name="overview"></a>

## Overview of the ETL steps

In the following I show the individual steps that are used in the respective ETL variants:

<a name="simple_pipeline"></a>

### Simple_Pipeline

![Overview_Simple_Pipeline](images/Overview_Simple_Pipeline.png)

--------------------------------------------------------------------------------------------------------

<a name="pipeline_with_join"></a>

### Pipeline_with_join

![Overview_Pipeline_with_join](images/Overview_Pipeline_with_join.png)

--------------------------------------------------------------------------------------------------------

<a name="pipeline_with_join2"></a>

### Pipeline_with_join2

![Overview_Pipeline_with_join2](images/Overview_Pipeline_with_join2.png)

--------------------------------------------------------------------------------------------------------

<a name="pipeline_with_intermediate_storage"></a>

### Pipeline_with_intermediate_storage

![Overview_Pipeline_with_intermediate_storage](images/Overview_Pipeline_with_intermediate_storage.png)

Corresponding legend:

![Legend](images/Legend.png)
 

<a name="link_publications"></a>

## Link to the Publications

For each of the listed ETL variants I have written a separate post. In it I have explained my approach and usage again in detail.

+ [Simple_Pipeline](https://michael-fuchs-python.netlify.app/2020/11/24/etl-simple-pipeline/)
+ [Pipeline_with_join](https://michael-fuchs-python.netlify.app/2020/11/25/etl-pipeline-with-join/)
+ [Pipeline_with_join2](https://michael-fuchs-python.netlify.app/2020/11/26/etl-pipeline-with-join2/)
+ [Pipeline_with_intermediate_storage](https://michael-fuchs-python.netlify.app/2020/11/27/etl-pipeline-with-intermediate-storage/)


<a name="authors"></a>

## Authors

+ [Michael Fuchs](https://github.com/MFuchs1989)

<a name="motivation"></a>

## Motivation: 

I've been blogging since 2018 on my homepages about all sorts of topics related to Machine Learning, Data Analytics, Data Science and much more.
You are welcome to visit them:

+ [Python Blog](https://michael-fuchs-python.netlify.app/)
+ [R Blog](https://michael-fuchs.netlify.app/)

I also publish individual interesting sections from my publications in separate repositories to make their access even easier. 
