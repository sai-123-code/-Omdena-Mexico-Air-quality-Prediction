# Omdena-Mexico-Air-quality-Prediction :
This project is part of omdena Local chapter named "Air Quality Prediction and Personalized Health Recommendations for Mexico City" and this repository contains all related resources used by me for this project.  Website: https://www.omdena.com/chapter-challenges/air-quality-prediction-and-personalized-health-recommendations-for-mexico-city

# Challenge Background :
Mexico City, one of the world's largest metropolitan areas, has long struggled with air pollution due to its geography, high population density, and industrial activities. The city's air quality significantly impacts the health and quality of life of its over 21 million residents.

# The Problem Statement:
Despite improvements in recent years, Mexico City still experiences frequent poor air quality episodes. Current systems provide general air quality information but lack personalized recommendations, especially for vulnerable populations.

# Dashboard code summary:

The code in repository implements a dynamic Air Quality Index (AQI) monitoring and visualization system for Mexico, using libraries like Streamlit, Folium, and Pandas. 
Here's an overview of the purpose and functionality of the major components:

## Main Features

### Main Dasboard (Main_landing_page_custom.py):

This Python script, built using Streamlit, serves as the foundation for creating an interactive and customizable dashboard interface. 
It is the central component of the application, providing the structural backbone for user navigation, 
sidebar functionality, filters, and more. 
The file establishes a modular base to incorporate additional pages or features seamlessly.

### AQI Overview (Page_1.py):

Provides a summary of AQI and pollutant levels for a selected station or all stations.
Displays AQI status (e.g., Good, Moderate, Hazardous) with a color-coded banner.
Shows pollutant levels like PM2.5, PM10, NO2, SO2, CO, and O3 using Streamlit metrics.
Displays a table summarizing AQI data and traffic congestion indices for stations.

### Interactive Map (Page_2.py):

Embeds the heatmap in the Streamlit app using Streamlit-Folium.
Uses Folium to generate an AQI heatmap with data from various monitoring stations.
Displays AQI data as:
A heatmap overlay where color intensity corresponds to AQI levels.
Custom markers for each station, with color-coded icons based on AQI levels.
Offers a "Refresh Map" button to reload real-time AQI data.

### Data Handling (data_handlers.py):

Manages loading AQI data from an Excel file.
Retrieves real-time AQI data for the current hour.
Provides utility functions to fetch station coordinates and names.

### Multilingual Support (language_utils.py):

Translates static text and station names into English and Spanish based on user preferences.

# Code Structure

<img width="662" alt="image" src="https://github.com/user-attachments/assets/747cd34e-eec5-400a-b051-5d543a6c26a1">



# My Contributions to this Omdenna Project :
As a core member of the Data Collection and Deployment team, my contributions were focused on both data preparation and the development of interactive tools for dynamic air quality monitoring. Below is a detailed breakdown of my contributions:

## Data Collection Team ( Contributor) :

Developed a Python script to generate a CSV dataset for Mexico City that flags whether a particular date is a public holiday, based on publicly available open-source data.
This holiday dataset was designed to integrate seamlessly with air pollution data, enabling deeper insights into seasonal trends and the impact of holidays on air quality.

## Deployment Team ( Co- Lead ) :

As a co-lead of the Deployment team, I led efforts to create an intuitive and visually engaging UI interface using Canvas.
Designed and developed a Streamlit dashboard for real-time Air Quality Index (AQI) monitoring and visualization for Mexico City. Key features of the dashboard include:
Dynamic Visualization: Real-time AQI data visualizations leveraging Streamlit, Folium, and Pandas.
Dual-Language Support: Fully supports both English and Spanish, enhancing accessibility for diverse users.
Interactive Maps: Integration of interactive maps for geospatial analysis of air quality trends.

Throughout the process, I conducted weekly meetings to track progress, address challenges, and ensure smooth deployment, fostering collaboration and efficient problem-solving across teams.
