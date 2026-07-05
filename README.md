# Task 2: Model Comparison — Feature Engineering & Optimization

## Overview
An enhanced house price prediction system comparing multiple ML models
with feature scaling. Built as Task 2 for my ML internship at 
Maincrafts Technology.

## Models Compared
| Model | RMSE | R² Score |
|-------|------|----------|
| Linear Regression | 0.7456 | 0.5758 |
| Ridge Regression | 0.7456 | 0.5758 |
| **Decision Tree** ✅ | **0.7242** | **0.5997** |

## Winner: Decision Tree 🏆
Lowest RMSE and highest R² — captures non-linear patterns that 
Linear and Ridge Regression cannot.

## Key Concepts Applied
- **Feature Scaling** — StandardScaler to normalize all features
- **Model Comparison** — 3 algorithms evaluated on same test set
- **Performance Metrics** — RMSE and R² for objective comparison

## Project Structure
| File | Description |
|------|-------------|
| `AI_ML_Task2_Model_Comparison.ipynb` | Main notebook |
| `model_comparison.png` | RMSE and R² bar charts |
| `best_model_pred_vs_actual.png` | Predicted vs Actual plot |
| `best_model.pkl` | Saved Decision Tree model |

## Tech Stack
Python, Pandas, NumPy, Scikit-learn, Matplotlib, Seaborn

## Improvement Ideas
- Try Random Forest or XGBoost for higher R²
- Add cross-validation for more robust evaluation
- Engineer new features (e.g. income per room)
