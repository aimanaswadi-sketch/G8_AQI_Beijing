# G8 AQI Beijing

This repository contains the code for Group 8 Machine Learning final project: Air Quality (AQI Beijing).

## Project Summary

This project predicts hourly PM2.5 concentration using the Beijing PM2.5 air quality dataset. The task is treated as a time-series regression problem because PM2.5 is a continuous value recorded hourly.

The project compares:
- NumPy Linear Regression
- Tuned Random Forest Regressor
- LSTM Sequence Model
- Previous-hour persistence baseline
- Train-mean dummy model

## Best Model

The best model is the Tuned Random Forest Regressor.

Main result:
- RMSE: 20.10
- R²: 0.9514

## Repository Files

- `G8_CS_DS_AQI_Beijing.ipynb` — main notebook
- `requirements.txt` — required Python libraries
- `data/` — dataset folder

## How to Run

1. Download or clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt

---

## Group Members

- Adam Harris bin Mohd Rezal (A212238)
- Mirza bin Ahmad Hafiz (A214180)
- Muhammad Aiman bin Ahmad Aswadi (A212178)

```text
docs/
├── Report.pdf
└── G8_Poster.pdf
