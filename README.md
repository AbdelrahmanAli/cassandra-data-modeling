# Data Modeling with Apache Cassandra

## Table of contents
- [Introduction](#introduction)
- [Project Description](#project-description)
- [Project Datasets](#project-datasets)
- [Technologies](#technologies)
- [Files](#files)
- [Setup](#setup)

## Introduction
This project is one of Udacity's Data Engineering Nano Degree projects, it is requested in the 1st course: ***Data Modeling***.

You are required to build a simple ETL pipeline that transfers data from files in local directory into a set of tables for executing some predefined queries in ***Apache Cassandra*** using Python and SQL.

## Project Description
>A startup called Sparkify wants to analyze the data they've been collecting on songs and user activity on their new music streaming app. The analysis team is particularly interested in understanding what songs users are listening to. Currently, there is no easy way to query the data to generate the results, since the data reside in a directory of CSV files on user activity on the app.

>They'd like a data engineer to create an Apache Cassandra database which can create queries on song play data to answer the questions, and wish to bring you on the project. Your role is to create a database for this analysis. You'll be able to test your database by running queries given to you by the analytics team from Sparkify to create the results.

## Project Datasets
There are one datasets residing in Local Directory:

- **Event data:** `event_data`

## Technologies
- Python 3
- Jupyter Notebook
- Apache Cassandra

## Files
 - `Project_1B_Project_Template.ipynb`: Contains Python blocks to read `event_data`, insert it into a singel file `event_datafile_new.csv`, then creates tables in Apache Cassandra and insert data into them, finally, runs some analysis queries.

## Setup
- Make sure you have `Python, Pandas, Apache Cassandra and Jupyter Notebook` installed and configured
- Open `Project_1B_ Project_Template.ipynb` and run the code blocks
