Advanced GenAI Internship Hackathon Submission

Student: Mrunmai Gaikwad
Email: gaikwadmrunmai@gmail.com

Project Overview

This repository contains the Jupyter Notebook submission for the Innomatics Research Labs | Advanced GenAI Internship Hackathon.

The project focuses on analyzing a food delivery dataset to answer MCQs, numerical questions, and fill-in-the-blank questions provided in the hackathon.

Datasets Provided

orders.csv – Transactional order data

users.json – User master data

restaurants.sql / restaurants.db – Restaurant master data

Note: Only the notebook is uploaded in the repository. Datasets were used locally/Colab for analysis.


Objective

Combine the three datasets (orders, users, restaurants) into a final consolidated dataset.

Analyze:

Order trends over time

User behavior patterns

City-wise and cuisine-wise performance

Membership impact (Gold vs Regular)

Revenue distribution and seasonality

Answer all hackathon questions (MCQs, numerical answers, fill-in-the-blanks) using Python and Pandas.

Notebook Details

File: Innomatics_Hackathon_Submission.ipynb

Sections

Import Libraries

pandas, numpy, sqlite3

Load Datasets

Load CSV, JSON, and SQL datasets

Merge into a single dataframe

Data Cleaning & Preprocessing

Convert dates to datetime

Create rating_range and quarter columns

MCQ Analysis

City-wise revenue

Cuisine-wise average order value

Users with high orders

Revenue by rating range

Membership and cuisine impact

Top restaurant analysis

Quarter-wise revenue

Numerical Questions

Total Gold orders

Revenue in Hyderabad

Distinct users

Average order value for Gold members

Orders with rating ≥ 4.5

Gold orders in top city

Fill-in-the-Blank Questions

Join keys, dataset formats, column origins, merge function, etc.

Save Final Dataset

Optional CSV: final_food_delivery_dataset.csv

Usage Instructions

Open the notebook in Google Colab or Jupyter Notebook.

Run all cells in order to reproduce results.

All outputs are already included in the notebook.

Repository Structure
Advanced_GenAI_Hackathon/
│
├── final_food_delivery.ipynb            
├── README.md                           

