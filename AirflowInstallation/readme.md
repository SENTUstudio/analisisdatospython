<p align="center"><img src="img/AirflowLogo.png" alt="CloudFormation"  height="200" /></p>

<h4 align="center"> Apache Airflow </h1>
<p align="center">
  <a href="https://www.sentu.studio/videos/404/watch?v=t4h4vsULwFE&t">El Corsario</a>
</p>

## Airflow Overview

Apache Airflow is an open-source workflow management platform for data engineering pipelines.

## Airflow Docker Image 
In this tutorial, we demonstrate how to create a custom docker image.  
In this video, we will cover how to install Apache Airflow on Docker. During this tutorial, we will build a custom Docker image of Airflow with
additional libraries such as SQL Server provider since we have covered SQL Server as a source in the previous Airflow videos. 
I have covered the Airflow and Airflow Dag in this video here if you like to check it out. 

## Commands

'''bash
docker build -t airflow-sqlserver -f Dockerfile . --no-cache
'''
