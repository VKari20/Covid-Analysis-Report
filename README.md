# Covid-Analysis-Report

## Project Description
This project analyzes global COVID-19 trends focusing on cases, deaths, and vaccinations across selected countries (Kenya, India, United States). The data is sourced from Our World in Data and cleaned for insightful visualizations and reporting.

## Objectives
- Import and clean global COVID-19 data.
- Filter and analyze time series trends for selected countries.
- Visualize total COVID-19 cases over time.
- Provide insights through data storytelling in a Jupyter Notebook.

## Tools and Libraries Used
- Python 3.x
- pandas
- matplotlib
- seaborn
- Jupyter Notebook (run inside VS Code)
- Git & GitHub (for version control and hosting)

## How to Run/View the Project
1. Clone this repository.
2. Ensure Python 3.x and required libraries are installed. You can install dependencies via:

python -m pip install pandas matplotlib seaborn jupyter
a. Download the full COVID dataset CSV (`owid covid data.csv`) from [Our World in Data](https://ourworldindata.org/covid-cases) and place it inside the `data` folder.
b. Open the Jupyter Notebook in VS Code.
c. Run the notebook cells from top to bottom to generate the analysis and plots.
d. Alternatively, run the main Python script if provided.

## Project Structure

├── **data/**
│ ├── owid covid data.csv # Original large dataset (not included in repo due to size)
│ └── **covid_filtered.csv **# Filtered smaller dataset for selected countries
├── **covid_analysis.ipynb** # Jupyter Notebook with analysis and visualizations
├── **README.md** # Project overview and instructions


## Insights & Reflections
- Kenya, India, and the United States show distinct COVID-19 case trajectories.
- The visualization helps identify peaks and trends over time.
- Working with a filtered dataset keeps the project lightweight and manageable.
- Further exploration can include deaths, vaccinations, and geographic maps.

---

Feel free to open issues or contribute improvements!

---

Created by Vennesa — 12/5/2025
