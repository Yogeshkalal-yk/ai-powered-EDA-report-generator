ai-powered-EDA-report-generator
https://ai-powered-eda-report-generator-fzsarv8hlhj5qb2cldxctu.streamlit.app/

# AI Powered EDA Report Generator

An AI-powered Exploratory Data Analysis (EDA) application built with Python and Streamlit. It allows users to upload a dataset, generate EDA insights, and create a summary report using Google Gemini AI.

## Overview

This project helps users understand datasets quickly by:
- loading CSV or Excel files
- analyzing missing values, duplicates, and summary statistics
- detecting outliers and correlations
- generating visual insights
- producing an AI-generated narrative report from the analysis results

## Features

- Upload CSV, XLSX, or XLS datasets
- Use the default Titanic dataset
- Explore dataset overview and preview
- Detect missing values and duplicate rows
- Compute summary statistics
- Identify outliers
- Visualize correlations
- Generate structured JSON summaries
- Use Gemini AI to generate readable insights and report summaries
- Save generated report output

## Tech Stack

- Python
- Streamlit
- Pandas
- NumPy
- Matplotlib
- Seaborn
- Google Generative AI (Gemini)

## Project Structure

```text
ai-powered-eda-report-generator/
├── ai_report.py
├── config.py
├── eda.py
├── streamlit_app.py
├── requirements.txt
├── data/
│   └── titanic.csv
├── output/
├── .gitignore
└── myvenv/   (optional local virtual environment)

Installation

Clone the repository
Create a virtual environment
Install dependencies

Create virtual environment
python -m venv myvenv

Activate virtual environment
On Windows:
myvenv\Scripts\activate

Install dependencies
pip install -r requirements.txt

Configuration
Before running the app, update the Gemini API key in the application configuration.

Open config.py and set:
GEMINI_API_KEY = "your_api_key_here"
You can also change the default model if needed.

Run the Application
streamlit run streamlit_app.py

Then open the local URL shown in the terminal in your browser.

How It Works

Upload or select a dataset
Run the EDA analysis
View the dataset overview, missing values, statistics, and correlations
Generate AI-based insights using Gemini
Save or review the final report


Example Use Cases

Business data analysis
Student project analysis
Research dataset exploration
Quick data storytelling for presentations
AI-assisted exploratory analysis

Notes
The project is designed for tabular data in CSV/Excel formats.
Large datasets may require more memory and longer processing time.
API usage depends on the Gemini model and key configuration.
License
This project is for educational and project-based learning purposes.

Author
yogesh


