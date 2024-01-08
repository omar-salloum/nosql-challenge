# nosql-challenge
Module 12 Challenge

## Description
This data analysis project involved utilizing PyMongo, a python driver for MongoDB, which a NoSQL database. The goal was to examine and analyze food hygiene ratings data from the UK Food Standards Agency. The primary aim was to support the editorial team at Eat Safe, Love, in making informed decisions for their future articles and recommendations based on data insights.

## Components

### 1. Database and Jupyter Notebook Set-Up
- Used NoSQL_setup_starter.ipynb for this section.
- Imported the provided data from the establishments.json file into MongoDB.
- Named the database uk_food and the collection establishments.
- Confirmed the database and data importation by listing databases, collections, and displaying one document.
- Prepared the establishments collection for analysis.

### 2. Update the Database
- Used NoSQL_setup_starter.ipynb for this section.
- Made specific modifications to the establishments collection:
    - Manually added new establishments to the collection.
    - Found and updated empty key, value pairs with the correct information.
    - Removed unnecessary establishments from the database.
    - Converted certain number values stored as strings to numbers.

### 3. Exploratory Analysis
- Used NoSQL_analysis_starter.ipynb for this section.
- Answered specific questions to guide Eat Safe, Love in their exploration of the dataset:
    - Identified establishments with a hygiene score equal to 20.
    - Found establishments in London with a RatingValue greater than or equal to 4.
    - Determined the top 5 establishments with a RatingValue of 5 while being near a certain geolocation, data was sorted by lowest hygiene score.
    - Counted establishments in each Local Authority area with a hygiene score of 0, sorted from highest to lowest.

## Files
- **Final_Code-folder**
  - **Resources-folder**
    - establishments.json
  
  - NoSQL_setup_starter.ipynb
  - NoSQL_analysis_starter.ipynb

## Table of Contents
- [NoSQL-Challenge](#nosql-challenge)
  - [Description](#description)
  - [Components](#components)
    - [1. Database and Jupyter Notebook Set-Up](#1-database-and-jupyter-notebook-set-up)
    - [2. Update the Database](#2-update-the-database)
    - [3. Exploratory Analysis](#3-exploratory-analysis)
  - [Files](#files)
