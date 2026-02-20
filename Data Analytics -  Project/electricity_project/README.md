Electricity Consumption Analytics Dashboard

Project Title - Plugging into the Future: An Exploration of Electricity Consumption Patterns Using Tableau

Project Description

This project analyzes electricity consumption patterns across regions and sectors using interactive Tableau dashboards. It identifies peak demand periods, regional disparities, sector-wise usage trends, and yearly variations. The dashboards are integrated into a Flask web application and published using Tableau Public.

Tech Stack

Python (Flask) – Web integration

Tableau Desktop / Tableau Public – Data visualization

SQL Workbench / Excel – Data preprocessing

HTML, CSS, Bootstrap – Frontend design

VS Code – Development environment

Project Structure

Electricity-Consumption-Project/
│
├── app.py
├── templates/
│     └── index.html
├── static/
│     └── images/
│           └── home.png
├── README.md

Installation & Setup

Step 1: Install Python

Make sure Python (3.8 or above) is installed.

Check version: python --version

Step 2: Install Required Libraries

Open terminal in project folder and install Flask:

pip install flask

Step 3: Run the Application

Navigate to project directory and run:

python app.py

If successful, you will see:

Running on http://127.0.0.1:5000/

Step 4: Open in Browser

Open your browser and go to:

http://127.0.0.1:5000/

Your Electricity Dashboard will load with embedded Tableau visualizations.

Tableau Setup

Dashboards are published to Tableau Public

Embedded code is integrated inside index.html

Even if Tableau Desktop trial expires, the dashboards will continue working as long as:

They remain published on Tableau Public

The Tableau Public account is active

Features

Region-wise electricity consumption visualization

Sector-wise comparison (Residential, Commercial, Industrial)

Year-wise and Quarter-wise trend analysis

Interactive filtering options

Story visualization for insights

Web integration using Flask

Performance

Fast dashboard loading

Smooth filter interaction

Responsive web layout

Stable deployment via Tableau Public

Future Enhancements

Real-time electricity data integration

Machine learning-based demand forecasting

Renewable energy analysis

Role-based login system

Mobile-optimized dashboards

Developed By

Divi Manasa
Team Lead – Electricity Consumption Analytics Project