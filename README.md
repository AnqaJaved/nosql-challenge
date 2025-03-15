# Nosql Challenge by Anqa Javed

## Project Overview

This project involves working with the UK Food Standards Agency's data, which evaluates food establishments across the United Kingdom. The data includes food hygiene ratings, which are used to help journalists and food critics focus on establishments that require attention. 

In this project, I used MongoDB to analyze the data and performed several operations to manipulate the data as per the requirements provided by the magazine editors of Eat Safe, Love. The project also includes exploratory analysis to answer specific questions and update the database.

## Requirements

### Part 1: Database and Jupyter Notebook Setup
- Imported the `establishments.json` file into MongoDB.
- Set up the `uk_food` database and `establishments` collection.
- Used `pymongo` to interact with the MongoDB database.

### Part 2: Update the Database
- Added a new restaurant entry ("Penang Flavours") to the database.
- Queried and updated documents with necessary information such as `BusinessTypeID` and other attributes.
- Removed establishments from the "Dover" Local Authority.

### Part 3: Exploratory Analysis
- Answered key questions about the dataset using aggregation and filtering in MongoDB.
- Queries involved finding establishments with specific hygiene scores, rating values, and other attributes.
- Converted MongoDB query results into Pandas DataFrames for further analysis.

## Technologies Used:

- **Python** (Libraries: PyMongo, Pandas)
- **MongoDB** (NoSQL Database)
- **Jupyter Notebook**
- **Git & GitHub** (for version control and collaboration)

## Files:

- **NoSQL_analysis_starter.ipynb** – Jupyter notebook for performing exploratory analysis on the UK food establishments data.
- **NoSQL_setup_starter.ipynb** – Jupyter notebook for setting up the MongoDB database and loading data.
- **Resources/establishments.json** – The data file containing the UK Food Standards Agency's establishments data.

## Installation

To get started with this project locally:

1. Clone this repository:

   ```bash
   git clone https://github.com/AnqaJaved/nosql-challenge.git
