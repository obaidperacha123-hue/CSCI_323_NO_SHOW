# CSCI323 – NMC Healthcare No-Show Prediction System

A machine learning system that predicts patient no-shows for NMC Healthcare outpatient appointments using Random Forest and Support Vector Machine (SVM) classifiers.

## Project Overview

Patient no-shows are a significant operational challenge in healthcare scheduling. This system analyzes historical NMC appointment data to predict whether a patient will attend their scheduled appointment, enabling proactive intervention by clinic staff.

## Models Implemented

- **Random Forest Classifier** — Primary model, trained on full dataset (169,524 records)
- **Support Vector Machine (SVM)** — Secondary model with linear kernel, trained on 15,000 sample subset

## Dataset

`Book1.xlsx` — NMC outpatient appointment records containing:
- Appointment Date and Booked Date/Time
- Patient Type (New/Revisit)
- OP Type and Admitting Department
- Gender
- No-Show outcome

## Dependencies

Install the required libraries before running:

```bash
pip install pandas numpy scikit-learn matplotlib seaborn openpyxl
```

## How to Run

1. Clone the repository
2. Ensure `Book1.xlsx` is in the same folder as the notebook
3. Open `CSCI323_Project_NMC_NoShow_Analysis.ipynb` in Jupyter Notebook or VS Code
4. Run all cells from top to bottom

## Results

Both models output a full precision and recall classification report along with confusion matrix visualizations for comparison.

## Course Information

- **Course:** CSCI323
- **Instructor:** Dr. Milan Dordevic
- **Institution:** University of Wollongong in Dubai
