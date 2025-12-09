# SpaceX Launch Analysis Project

This repository contains a compact, end-to-end data science project built using publicly available SpaceX launch data. It includes data collection, wrangling, exploratory analysis, folium-based geospatial mapping, basic SQL experiments, and a simple machine learning model to explore launch outcome predictions.  
All stages are implemented in Jupyter notebooks, accompanied by a lightweight Dash app for interactive exploration. A concise PDF report summarizing the workflow and results is included.

---

## 📑 Table of Contents
- [Project Overview](#project-overview)
- [Repository Structure](#repository-structure)
- [Technologies and Libraries](#technologies-and-libraries)
- [Quick Start](#quick-start)
- [Installation and Environment](#installation-and-environment)
- [Running the Notebooks](#running-the-notebooks)
- [Running the Dash App](#running-the-dash-app)
- [Data Sources and Notes](#data-sources-and-notes)
- [Machine Learning Summary](#machine-learning-summary)
- [Results and Evaluation](#results-and-evaluation)
- [Project Report](#project-report)
- [Tests (Notes)](#tests-notes)
- [Contributing](#contributing)
- [License and Contact](#license-and-contact)
- [Acknowledgements](#acknowledgements)

---
<img width="1024" height="1536" alt="spacex-rocket" src="https://github.com/user-attachments/assets/592949d9-ec27-4ea1-bfce-48821f7c3b92" />

---

## Project Overview

This project analyses SpaceX launch data and demonstrates a complete data science workflow, including:

- Collecting raw data through APIs and web scraping  
- Cleaning, wrangling, and performing feature engineering  
- Conducting exploratory data analysis (EDA) and visualizations  
- Creating folium-based geospatial maps  
- Running SQL-based experiments  
- Training a basic machine learning model to predict launch outcomes  
- Building an interactive dashboard using Dash  

A PDF report summarizing the workflow, insights, and results is included for quick reference.

---

## Repository Structure

- IBM - SpaceX Project.pdf → Final project report  
- Notebooks/ → Additional notebooks (optional)  
- README.md → Documentation (this file)  
- data_collection.ipynb → Data retrieval (API / scraping)  
- data_wrangling.ipynb → Cleaning, feature engineering  
- eda_dataviz.ipynb → Visualizations & EDA  
- folium_map.ipynb → Geospatial analysis using folium  
- machine_learning.ipynb → ML pipeline, model training & evaluation  
- sql.ipynb → SQL experiments (SQLite / pandas integration)  
- web_scrapping.ipynb → Web scraping helpers & logic  
- spacex_dash_app.py → Dash app for interactive exploration

---

## Technologies and Libraries

- **Python 3.8+**  
- **Jupyter / JupyterLab**  
- pandas, numpy  
- matplotlib, seaborn, plotly  
- folium (interactive maps)  
- scikit-learn (modeling)  
- requests, BeautifulSoup (web scraping)  
- dash (web dashboard)  
- sqlalchemy / sqlite

---

## Quick Start

Clone the repository:

```bash
git clone https://github.com/eray-yuztyurk/ibm-spacex-project.git
cd ibm-spacex-project
```

Create and activate a virtual environment:

- macOS / Linux
```bash
python3 -m venv venv
source venv/bin/activate
```

- Windows (PowerShell)
```powershell
python -m venv venv
.\venv\Scripts\Activate.ps1
```

Install dependencies:

- If a requirements.txt is present:
```bash
pip install -r requirements.txt
```

- Or install core packages manually:
```bash
pip install jupyterlab pandas numpy matplotlib seaborn plotly folium scikit-learn requests beautifulsoup4 dash sqlalchemy
```

---

## Installation and Environment

- Recommended Python version: 3.8 or newer.  
- Use a virtual environment to isolate dependencies.  
- The Dash app runs on port 8050 by default (editable in the script).

---

## Running the Notebooks

Start Jupyter:

```bash
jupyter lab
```
or
```bash
jupyter notebook
```

Notebooks included:
- data_collection.ipynb — collecting raw data  
- data_wrangling.ipynb — cleaning, transforming  
- eda_dataviz.ipynb — EDA plots and insights  
- folium_map.ipynb — geospatial maps (renders best inside notebook)  
- machine_learning.ipynb — model creation and evaluation  
- sql.ipynb — SQLite / SQL queries inside Python  
- web_scrapping.ipynb — scraping workflow details

Notes:
- Some notebooks fetch data online; ensure internet access when running for the first time.  
- Run notebooks sequentially for reproducible results.

---

## Running the Dash App

Run the Dash app:

```bash
python spacex_dash_app.py
```

Open the app in your browser at:
http://127.0.0.1:8050

Modify the script to change port or host configuration if needed.

---

## Data Sources and Notes

- Data acquisition logic lives in data_collection.ipynb and web_scrapping.ipynb.  
- Intermediate datasets (CSV / SQLite DBs) may be created during execution but are not tracked in the repo.  
- Re-run data retrieval if you want updated results.

---

## Machine Learning Summary

The machine learning pipeline explores:
- Train/test split  
- Feature encoding and preprocessing  
- Model selection (logistic regression, decision trees, random forest, etc.)  
- Evaluation using accuracy, precision, recall, confusion matrices

All model details, metrics, and visual outputs are available in machine_learning.ipynb.

---

## Results and Evaluation

- Notebook outputs contain all plots, tables, and evaluation metrics.  
- The PDF report summarizes the main findings with visuals.

Example insights:
- Which launch sites perform best  
- What conditions correlate with successful launches  
- How model predictions align with observed outcomes

---

## Project Report

IBM - SpaceX Project.pdf provides a structured summary of the overall workflow, results, and conclusions.

---

## Tests (Notes)

- No automated tests are included yet.

Possible future additions:
- pytest-based tests for helper scripts  
- Notebook validation (nbval / papermill)  
- GitHub Actions CI workflows

---

## Contributing

This project serves as a personal learning artifact, but contributions or suggestions are welcome. You can:
- Open an issue  
- Submit a pull request

Suggested enhancements:
- Add a requirements.txt / environment.yml  
- Add automated testing  
- Add a LICENSE file

---

## License and Contact

- No license is included yet. Consider adding MIT or Apache 2.0 if you plan to share or accept contributions.  
- For questions or suggestions, please open an issue in the repository.

---

## Acknowledgements

This project follows the general methodological structure of IBM’s Data Science curriculum and uses publicly available SpaceX datasets along with standard Python data science tooling.
