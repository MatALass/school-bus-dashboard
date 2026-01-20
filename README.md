# Electric School Bus Dashboard

**EFREI Paris — Data Visualization Project (Streamlit)**  
Author: *Mathieu Alassoeur*  
Course: Data Visualization & Storytelling — 2025

---

## Project Overview

This project is an interactive dashboard that explores data related to **electric school buses**.  
It allows users to visualize key aspects of electric school bus adoption or operational data (e.g., usage trends, comparisons, or indicators from the provided dataset).

The application is built with **Streamlit** and uses the provided dataset (`data.xlsx`) as its main data source.

---

## Dataset

The dataset used in this project is included in the file `data.xlsx`.  
It contains data related to electric school bus metrics relevant to the project’s visualizations and analysis.

---

## Technologies Used

- Python 3  
- Pandas (for data manipulation)  
- Streamlit (for interactive dashboard)  
- Excel (dataset format)

---

## Project Structure

```

electric-school-bus-dashboard/
│
├── app.py                 # Main Streamlit application
├── data.xlsx              # Dataset for the dashboard
├── efrei_logo.png         # Logo or asset used in the app
├── requirements.txt       # Python dependencies
└── README.md              # This file

````

---

## Quick Start

Follow the steps below to run the dashboard locally.

### 1. Clone the repository

```bash
git clone https://github.com/MatALass/electric-school-bus-dashboard.git
cd electric-school-bus-dashboard
````

### 2. Create a virtual environment (recommended)

```bash
python -m venv venv
```

Activate the environment:

* **macOS / Linux**

```bash
source venv/bin/activate
```

* **Windows (PowerShell)**

```bash
venv\Scripts\Activate.ps1
```

### 3. Install dependencies

```bash
pip install -r requirements.txt
```

### 4. Run the Streamlit dashboard

```bash
streamlit run app.py
```

Once running, the dashboard will be open in your browser (typically at `http://localhost:8501`).

---

## Dashboard Content

The dashboard includes:

* Visualizations based on the `data.xlsx` dataset
* Filters and interactive components
* Graphs and tables that help interpret electric school bus data
