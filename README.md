# Exploratory Data Analysis (EDA) on Car Evaluation Dataset
**F.Y. BCA Semester I (Division B) — Group Project**

---

### Project Details
- **Subject:** Exploratory Data Analysis (EDA)
- **Group:** Group 6
- **Roll Numbers:** 33, 42, 35, 36, 37, 38, 103, 34
- **Dataset:** UCI Machine Learning Repository — Car Evaluation Dataset (1,728 records)

---

## About the Project

This repository contains our Python notebook and data analysis for the Car Evaluation dataset. We analyzed how different car attributes (buying price, maintenance cost, doors, passenger capacity, luggage boot, and safety rating) affect whether a car is evaluated as:
- `unacc` (Unacceptable)
- `acc` (Acceptable)
- `good` (Good)
- `vgood` (Very Good)

---

## Repository Files

```
├── car_evaluation_eda.ipynb  # Main Jupyter / Google Colab Notebook
├── data/
│   ├── car.data              # Raw dataset (1,728 records)
│   ├── car.names             # Dataset information from UCI
│   └── car.c45-names         # Attribute details
├── figures/                  # Charts generated from the analysis
│   ├── 01_target_distribution.png
│   ├── 02_feature_distributions.png
│   ├── 03_safety_vs_class.png
│   ├── 04_persons_vs_class.png
│   ├── 05_cost_vs_class.png
│   ├── 06_correlation_heatmap.png
│   └── 07_safety_persons_interaction.png
└── README.md
```

---

## Main Findings

1. **Safety is the most important factor:** Every single car with a low safety rating was rated unacceptable (`unacc`).
2. **2-seater cars are not accepted:** All 2-seater cars were rated unacceptable in general family/commuter evaluations.
3. **Very high costs limit top ratings:** Cars with very high purchase or maintenance costs did not receive `good` or `vgood` ratings.
4. **Very Good requirements:** A car needs high safety, capacity for 4 or more people, and reasonable pricing to be rated `vgood`.

---

## How to Run the Notebook

### On Google Colab
1. Open [Google Colab](https://colab.research.google.com).
2. Upload `car_evaluation_eda.ipynb` or open it directly from this GitHub repository.
3. Select **Runtime -> Run all** to execute all cells.
