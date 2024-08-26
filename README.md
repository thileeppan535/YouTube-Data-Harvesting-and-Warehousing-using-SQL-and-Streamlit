# YouTube-Data-Harvesting-and-Warehousing-using-SQL-and-Streamlit
This project involves building a simple dashboard or user interface using Streamlit to retrieve YouTube channel data via the YouTube API. The retrieved data is stored in a SQL database (warehousing), allowing for data querying using SQL. Additionally, the project includes visualizing the data within the Streamlit interface.
### 📘 Introduction

This project focuses on developing a streamlined dashboard and user interface using Streamlit to retrieve and visualize YouTube channel data. Leveraging the YouTube API, the collected data is stored in a SQL database using XAMPP as the control panel. This setup facilitates efficient data querying and visualization within the Streamlit environment.

**Domain**: 📱 Social Media  
**Skills Takeaway**: Python scripting, Data Collection, Streamlit, API Integration, Data Management with SQL

### 📘 Overview

#### 🌾 Data Harvesting:
- Harness the power of the YouTube API to gather comprehensive data, including video details, channel statistics, playlists, and user comments.

#### 📥 Data Storage:
- Configure a local MySQL database using XAMPP.
- Create structured tables for storing the harvested YouTube data.
- Insert the collected data into the database using SQL scripts, ensuring it's organized for efficient retrieval and analysis.

#### 📊 Data Analysis and Visualization:
- Develop an interactive Streamlit application to query the SQL database.
- Visualize and analyze the stored YouTube data through intuitive charts and graphs within the Streamlit interface.

### 🛠 Technology and Tools
- **Python**: 3.12.2
- **XAMPP**
- **MySQL**
- **YouTube API**
- **Streamlit**
- **Plotly**

### 📚 Packages and Libraries
- **google-api-python-client**: `import googleapiclient.discovery`  
  `from googleapiclient.errors import HttpError`
- **mysql-connector-python**: `import mysql.connector`
- **SQLAlchemy**: `from sqlalchemy import create_engine`
- **pandas**: `import pandas as pd`
- **streamlit**: `import streamlit as st`
- **streamlit_option_menu**: `from streamlit_option_menu import option_menu`
- **plotly**: `import plotly.express as px`
- **pillow**: `from PIL import Image`

### 📘 Features

#### 📚 Data Collection:
- Retrieve various data points from YouTube using the YouTube Data API, including channel information, video details, playlists, and comments.

#### 💾 Database Storage:
- Convert the collected YouTube data into pandas dataframes.
- Create and manage a new database and corresponding tables using the XAMPP control panel.
- Use SQLAlchemy to insert the data into the respective MySQL tables, accessible through XAMPP’s MySQL environment.

#### 📋 Data Analysis:
- Utilize MySQL queries to analyze the stored YouTube data, answering specific questions about YouTube channels. The results are dynamically displayed within the Streamlit application.

#### 📊 Data Visualization:
- Present the analyzed data through visually appealing charts and graphs using Plotly. The visualizations are seamlessly integrated into the Streamlit application, offering an interactive experience.

### 📘 Usage

- Enter a YouTube channel ID or name in the input field under the "Data Collection" option in the sidebar menu.
- Click the "View Details" button to fetch and display detailed channel information.
- Click the "Upload to MySQL" button to store the channel data in the SQL database.
- Select the "Analysis and Visualization" options from the sidebar menu to explore and visualize the data through the Streamlit interface.
