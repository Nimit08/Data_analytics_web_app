# Data Analytics Web App

## 🌟 Overview

The **Data Analytics Web App** is an interactive, user-friendly tool built using **Streamlit** for exploring, cleaning, and visualizing datasets. This web application simplifies data preprocessing and analysis, making it suitable for beginners and professionals alike.

It supports multiple data formats like CSV, XLSX, TXT, and more. With robust data visualization and cleaning features, this app allows users to prepare data for machine learning and analytics workflows efficiently.

---

# Data Analytics Web App 📊

An interactive web application built using **Streamlit** that enables users to explore, analyze, and visualize their datasets effortlessly. This app supports file uploads (CSV and Excel) and offers robust tools for data exploration, statistical analysis, and visualizations.

---

## 🌟 Features

### 1. **File Upload**
- Supports `.csv` and `.xlsx` file formats.
- Displays the uploaded dataset in a tabular format.

### 2. **Data Exploration**
- Basic dataset information: number of rows, columns, and statistical summary.
- View the top and bottom rows of the dataset with adjustable row count.
- Explore column data types and names.

### 3. **Value Counts**
- Select any column to view its value counts.
- Visualize value counts using bar, line, and pie charts.

### 4. **GroupBy Operations**
- Group data by one or more columns.
- Perform aggregate operations like `sum`, `mean`, `max`, `min`, `median`, and `count`.
- Visualize grouped data with:
  - Line charts
  - Bar charts
  - Scatter plots
  - Pie charts
  - Sunburst charts

### 5. **Interactive Visualizations**
- Built using **Plotly** for a rich, interactive experience.
- Customizable axes, colors, and facets for better insights.

---



## 🚀 Getting Started

Follow the steps below to set up the project on your local machine.

### Prerequisites

Ensure you have the following installed:
- Python 3.8+  
- `pip` package manager

### Installation

1. **Clone the Repository**
   ```bash
   git clone https://github.com/Nimit08/Data_analytics_web_app.git
   cd Data_analytics_web_app
2. **Install Dependies**
    ```bash
   pip install -r requirements.txt
3.**Run the Application**
   ```bash
   streamlit run app.py
 ```

## 📂Directory Structure
```bash
Data_analytics_web_app/
│
├── app.py                 # Main application file
├── requirements.txt       # Dependencies for the project
├── README.md              # Documentation
├── assets/                # Images and additional assets (screenshots, demo GIFs)
└── data/                  # Sample datasets for testing
 ```


