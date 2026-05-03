# Analysis of Single-Use Plastics' Consumption in Myanmar and Its Contribution to Climate Change

**Author:** Ei Mon Soe | **Student ID:** PIUS 20220035  
**Institution:** Parami University — Bachelor of Data Science  
**Supervisor:** Dr. Mohamed Megheib | **Course Advisor:** Dr. Nwe Nwe Htay Win

---

## Overview

This project analyzes single-use plastic (SUP) consumption patterns across all 14 regions and states of Myanmar and estimates their contribution to climate change through CO₂-equivalent (CO₂e) emissions. Data was collected from 304 survey respondents and analyzed using Python-based exploratory data analysis (EDA) and a custom CO₂e emissions calculator.

---

## Repository Contents

| File | Description |
|------|-------------|
| `Final_Survey_Dataset.csv` | Survey dataset (304 responses, 24 variables) |
| `Final_progress.ipynb` | Jupyter notebook — data preprocessing, EDA, and visualizations |
| `app1.py` | Streamlit web application for interactive exploration |
| `requirements.txt` | Python dependencies |

---

## Key Features

- **Choropleth map** of survey responses by Myanmar region (GeoPandas)
- **11 EDA visualizations** covering consumption patterns, disposal behavior, and environmental awareness
- **CO₂e Emissions Calculator** — estimates individual weekly and annual carbon footprint from plastic use
- **Interactive web app** built with Streamlit

---

## Installation & Usage

### 1. Clone the repository
```bash
git clone https://github.com/monsoee29-lang/Senior-Capstone.git
cd Senior-Capstone
```

### 2. Install dependencies
```bash
pip install -r requirements.txt
```

### 3. Run the Jupyter Notebook
```bash
jupyter notebook Final_progress.ipynb
```

### 4. Run the Web App
```bash
streamlit run app1.py
```

---

## Libraries Used

- `pandas`, `numpy` — data manipulation
- `matplotlib`, `seaborn` — data visualization
- `geopandas` — choropleth mapping
- `streamlit` — web application

---

## Key Findings

- Over **97%** of respondents reported street food is always or sometimes packaged in plastic
- A clear **awareness-behaviour gap** exists — even highly aware respondents still use plastic at moderate-to-high levels
- **Local markets and street vendors** are the primary sources of single-use plastic
- Near-universal support (**85%+**) for reducing single-use plastics across all age groups

---

## License

This project was developed as a Senior Capstone Project at Parami University, May 2026.
