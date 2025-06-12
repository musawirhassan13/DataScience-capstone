# SpaceX Falcon 9 First Stage Landing Prediction

This project is part of the IBM Data Science Professional Certificate capstone, focused on predicting whether the first stage of the SpaceX Falcon 9 rocket will successfully land. Successful landings allow SpaceX to reuse rockets, significantly reducing launch costs. This project includes full data collection, analysis, visualization, and machine learning modeling.

## Table of Contents
- [Project Overview](#project-overview)
- [Project Structure](#project-structure)
- [Technologies Used](#technologies-used)
- [Highlights](#highlights)
- [Screenshots](#screenshots)
- [Running the Project](#running-the-project)

## Project Overview

The goal is to build predictive models using machine learning to determine the likelihood of a successful first-stage landing of the Falcon 9 rocket. Data is gathered using the SpaceX API and web scraping, analyzed with SQL and Pandas, visualized using various tools, and finally modeled with classification algorithms.

## Project Structure

| Notebook/Script | Description |
|------------------|-------------|
| [Data Collection via API](https://github.com/musawirhassan13/DataScience-capstone/blob/main/jupyter-labs-spacex-data-collection-api.ipynb) | Extracted Falcon 9 launch data using SpaceX API |
| [Web Scraping Launch Records](https://github.com/musawirhassan13/DataScience-capstone/blob/main/jupyter-labs-webscraping.ipynb) | Scraped Wikipedia for launch site and mission info |
| [Data Wrangling](https://github.com/musawirhassan13/DataScience-capstone/blob/main/labs-jupyter-spacex-Data%20wrangling.ipynb) | Cleaned and merged data from multiple sources |
| [Exploratory Data Analysis & Visualization](https://github.com/musawirhassan13/DataScience-capstone/blob/main/edadataviz.ipynb) | Analyzed launch patterns and payload behavior |
| [EDA with SQL](https://github.com/musawirhassan13/DataScience-capstone/blob/main/jupyter-labs-eda-sql-coursera_sqllite.ipynb) | Queried mission stats using SQL on IBM DB2 |
| [Interactive Maps with Folium](https://github.com/musawirhassan13/DataScience-capstone/blob/main/lab_jupyter_launch_site_location.ipynb) | Mapped launch sites and outcomes interactively |
| [Machine Learning Prediction](https://github.com/musawirhassan13/DataScience-capstone/blob/main/SpaceX_Machine%20Learning%20Prediction_Part_5.ipynb) | Trained ML models (Logistic Regression, SVM, Decision Tree, KNN) |
| [Dashboard with Dash](https://github.com/musawirhassan13/DataScience-capstone/blob/main/spacex%20dash%20app.py) | Created a web app for launch insights using Dash |

## Technologies Used

- **Languages**: Python, SQL
- **Libraries**: Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn, Plotly, Dash, Folium, BeautifulSoup
- **Databases**: IBM DB2
- **APIs**: SpaceX REST API
- **Tools**: Jupyter Notebook, GitHub

## Highlights

- Collected and merged structured data from APIs and unstructured data via web scraping
- Performed exploratory analysis using both SQL and Python
- Built interactive visualizations using Folium and Dash
- Applied ML classification models: Logistic Regression, SVM, Decision Tree, and KNN
- Decision Tree model performed best with GridSearchCV best score of **0.889**

## Screenshots

You can add screenshots like these by uploading `.png` files to your repo and linking them here:

```markdown
![Confusion Matrix](path/to/your/image.png)
```

## Running the Project

1. Clone the repository  
```bash
git clone https://github.com/musawirhassan13/DataScience-capstone.git
```

2. Install dependencies (optional: use a virtual environment)
```bash
pip install -r requirements.txt
```

3. Open the Jupyter notebooks in your Jupyter environment  
4. Run the Dash app  
```bash
python spacex dash app.py
```