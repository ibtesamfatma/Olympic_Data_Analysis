# Olympic Data Analysis

Welcome to the Olympic Data Analysis project! This repository contains the code and resources for analyzing Olympic Games datasets. The project involves exploratory data analysis (EDA) using Jupyter Notebooks and interactive visualizations using `@interact` widgets. Additionally, a web application has been developed using Streamlit to enable broader interaction with the data.

## Table of Contents

- [Project Overview](#project-overview)
- [Dataset](#dataset)
- [Exploratory Data Analysis](#exploratory-data-analysis)
- [Interactive Widgets with @interact](#interactive-widgets-with-interact)
- [Streamlit Web Application](#streamlit-web-application)
- [Installation](#installation)
- [Usage](#usage)


## Project Overview

This project provides insights into the historical Olympic Games data through comprehensive exploratory data analysis (EDA) and interactive visualizations. The analysis is carried out in Jupyter Notebooks, and the project also includes a web application built with Streamlit, allowing users to explore the data dynamically.

## Dataset

The dataset used in this project includes historical data on the Olympic Games, covering various aspects such as athletes, countries, medals, sports, and events. The dataset has been preprocessed and cleaned to facilitate effective analysis.

## Exploratory Data Analysis

The EDA process involves:

- **Data Cleaning:** Handling missing values, data types, and inconsistencies.
- **Data Visualization:** Creating charts, graphs, and plots to visualize trends, distributions, and relationships in the data.
- **Statistical Analysis:** Analyzing key metrics, trends, and patterns in the dataset.

Jupyter Notebooks in this repository provide a step-by-step guide through the EDA process, using popular libraries such as `pandas`, `matplotlib`, and `seaborn`.

## Interactive Widgets with `@interact`

To make the analysis more interactive, `@interact` widgets from the `ipywidgets` library are used. These widgets allow users to:

- Filter data based on various criteria (e.g., country, year, sport).
- Dynamically update visualizations and statistical outputs.
- Explore different subsets of the data interactively.

This feature is particularly useful for non-technical users who want to explore the data without writing code.

## Streamlit Web Application

The project includes a web application developed using Streamlit. The app provides an intuitive interface for users to interact with the Olympic data. Key features include:

- **Interactive Filters:** Select data based on specific parameters.
- **Visualizations:** View dynamically generated charts and graphs.
- **Search and Exploration:** Search for specific athletes, countries, or events.

The Streamlit app can be deployed locally or on the web, allowing users to access the analysis without needing a Jupyter environment.

## Installation

To run the project locally, follow these steps:

1. **Clone the repository:**
   ```bash
   git clone https://github.com/your-username/olympic-data-analysis.git
   cd olympic-data-analysis

2. **Open the project folder inside the visual studio code**

3. **Install the below given libery in command prompt or visual studio code terminal**
   ```bash
   import streamlit as st
   import pandas as pd
   import plotly.express as px
   import matplotlib.pyplot as plt
   import seaborn as sns
   import preprocessor,helper
4. **After installing the project required python libery we return use termianl to run our project using simple command.**
   ```bash
   streamlit run app.py
   
5 .**After running  this line the streamlit create a localhost in your machine and run this web application using browser.**
   - This is the localhost that streamlit is host our web application
<img width="1440" alt="Screenshot 2024-08-19 at 8 43 00 PM" src="https://github.com/user-attachments/assets/458c1e75-4b7d-403c-ba34-cb10f5548307">

<img width="1440" alt="Screenshot 2024-08-19 at 8 43 36 PM" src="https://github.com/user-attachments/assets/76520f82-7b8c-4cbb-819b-e484c9c18282">

![image](https://github.com/user-attachments/assets/8e92cee2-9a14-48bb-86ca-c86802963f71)

<img width="1440" alt="Screenshot 2024-08-19 at 8 51 48 PM" src="https://github.com/user-attachments/assets/19d3563c-74ee-46b6-8fc7-4c13e92e25a9">







   
