# Airbnb-Analysis-Using-PowerBi

## Introduction

-> Accessed and processed a JSON dataset containing Airbnb data from 2019    
-> Utilized Python for data transformation, ensuring it fit into a structured DataFrame   
-> Applied data preprocessing techniques, including cleaning and organizing, to enhance data quality and usability   
-> Leveraged the MySQL Python connector to establish a relational database   
-> Inserted the preprocessed data into appropriate tables within the database   
-> Developed an interactive dashboard using Streamlit, providing users with a platform to explore insights from the dataset   
-> Incorporated dynamic visualizations with Plotly to enrich the dashboard's with sqlalchemy for querying  

## Domain : 

Travel Industry, Property Management and Tourism

## Skills Takeaway

Python scripting, Data Preprocessing, Visualization, EDA, Streamlit and PowerBI

## Technology and Tools

Python 3.12.2
MYSQL
Streamlit
Plotly
Power BI

## Packages and Libraries

import json   
import time   
import pandas as pd   

import streamlit as st   
from streamlit_option_menu import option_menu   
import plotly.express as px   

from sqlalchemy import create_engine   
import mysql.connector

## Overview

## Data Extraction :

Data extraction involved retrieving information from the 2019 Airbnb dataset, comprising property listings with details such as descriptions, pricing, location, and reviews.

## Data Preprocessing & transform:

Utilizing Python, the Airbnb dataset from 2019 underwent transformation and preprocessing, resulting in structured DataFrames. This process involved cleaning, organizing, and preparing the data for analysis, ensuring its quality and usability for insights extraction

## Database Integration:

Mysql connector used for connection between Python and MySQL database with XAMPP, enabling data transfer. SQLAlchemy's engine facilitates efficient querying, simplifying database interactions for Python

## Data Visualization And Analysis:

With the assistance of Streamlit and Plotly, a dashboard and charts are created, offering geospatial visualizations and top insights. This setup empowers users to explore and reveal trends within the dataset, facilitating insightful analysis.

## Features

-> In the 'Home' section of our project, users can explore detailed hotel information by selecting a country.This feature provides an overview of each hotel, including price, room type, description, and ratings.

-> In the 'Discover' section, users have the opportunity to explore countries through dynamic geo-visualizations, supplemented with price insights. 

-> In the 'Insight' section, users explore two categories: 'Top Insights' and 'Filtered Insights'. 'Top Insights' offer pre-defined queries with insightful analysis, while 'Filtered Insights' allow users to select specific criteria for tailored visualizations

## Power BI

Power BI dashboard provides interactive visualizations and insights derived from the Airbnb dataset. It allows you to explore various aspects of Airbnb listings, including pricing trends, property types, and geographical distributions.  


![airbnb-powerbi](https://github.com/user-attachments/assets/297feb38-05cd-4edc-8a4d-6072c703f4e2)


## Contact

LINKEDIN: https://www.linkedin.com/in/nithesh-goutham-m-0b0514205/   
WEBSITE: https://digital-cv-using-streamlit.onrender.com/   
EMAIL : nitheshgoutham2000@gmail.com

