# ACIS Insurance Risk & Profitability Analysis

This repository contains my analysis for AlphaCare Insurance Solutions focused on car insurance risk profiling and marketing optimization.

## Project Structure

- `notebooks/insurance_eda.ipynb`: Main notebook for EDA and visualization, with step-by-step explanations and plots.
- `data/` – raw datasets (including `MachineLearningRating_v3.txt`)
- `src/` – scripts for data processing and modeling
- `.github/workflows/` – CI/CD configs
- `requirements.txt`: Python dependencies for running the notebook.

## Getting Started

### 1. Clone the Repository

Clone this repository to your local machine.

### 2. Install Dependencies

Create a virtual environment and install the required packages:

```bash
python -m venv venv
venv\Scripts\activate  # On Windows
# or
source venv/bin/activate  # On Mac/Linux
pip install -r requirements.txt
```

### 3. Data Preparation

Ensure the file `MachineLearningRating_v3.txt` is present in the `data/` directory. If using DVC, run:

```bash
dvc pull data/MachineLearningRating_v3.txt.dvc
```

### 4. Run the Notebook

Open `notebooks/insurance_eda.ipynb` in VS Code or Jupyter and run the cells sequentially. Each code cell is preceded by a markdown explanation.

## Key Objectives

- Explore claim risks by region, car type, and gender
- Identify low-risk customer profiles
- Build predictive models for optimal premium pricing

## Features

- Data loading and cleaning
- Descriptive statistics
- Missing value analysis
- Distribution and correlation plots
- Loss ratio analysis by province, gender, and vehicle type
- Outlier detection
- Monthly trend analysis

## Requirements

- Python 3.8+
- pandas
- seaborn
- matplotlib
- (Optional) dvc

Install all dependencies with `pip install -r requirements.txt`.

## License

MIT License
