# AI Impact on Student Performance

An analysis project that explores relationships between students' use of artificial intelligence (AI) tools and their academic outcomes. This repository contains the dataset, an analysis Jupyter notebook, and the final project report.
## Repository contents

- `ai_impact_student_performance_dataset.csv` — cleaned dataset used for analysis.
- `Academic_Outcomes_and_Artificial_Intelligence_Dependency_An_Analytical_Study_of_Student_Learning_Behavior_.ipynb` — main Jupyter notebook with data exploration, visualizations, and modelling.
- `Sakshi_A9929724001565(el)  Project Report  copy.pdf` — final project report (PDF).
- `README.md` — this file.
## Summary

This project examines how dependency on AI tools correlates with student learning behavior and academic outcomes. The notebook performs:
- Data loading and cleaning
- Exploratory data analysis (EDA) and visualization
- Feature engineering
- Predictive modelling (baseline models such as logistic regression / decision trees)
- Evaluation and interpretation of results
## How to run

1. Create a Python 3.8+ environment (recommended). Example using venv:
```bash
python3 -m venv .venv
source .venv/bin/activate
pip install --upgrade pip
```
2. Install required packages:

```bash
pip install pandas numpy matplotlib seaborn scikit-learn jupyterlab notebook
```
3. Start Jupyter and open the notebook:

```bash
jupyter lab
# or
jupyter notebook
```
Open `Academic_Outcomes_and_Artificial_Intelligence_Dependency_An_Analytical_Study_of_Student_Learning_Behavior_.ipynb` in the browser and run the cells in order.

## Notes and assumptions

- The notebook expects `ai_impact_student_performance_dataset.csv` to be in the repository root.
- If you make heavy changes to the notebook or add models that require more dependencies, update the requirements above accordingly.

## Suggested next steps

- Add a `requirements.txt` or `environment.yml` for reproducible installs.
- Add a small script (`scripts/prepare_data.py`) to centralize data cleaning steps used by the notebook.
- Add unit tests for any data-processing functions you extract from the notebook.

