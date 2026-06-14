# G8 AQI Beijing

This repository contains the code for Group 8 Machine Learning final project: **Air Quality (AQI Beijing)**.

## Project Summary

This project predicts hourly PM2.5 concentration using the Beijing PM2.5 air quality dataset. The task is treated as a time-series regression problem because PM2.5 is a continuous value recorded hourly.

The project compares:

* NumPy Linear Regression
* Tuned Random Forest Regressor
* LSTM Sequence Model
* Previous-hour persistence baseline
* Train-mean dummy model

## Best Model

The best model is the **Tuned Random Forest Regressor**.

Main result:

* RMSE: 20.10
* R²: 0.9514

## Repository Files

* `G8_CS_DS_AQI_Beijing.ipynb` — main notebook
* `requirements.txt` — required Python libraries
* `data/` — dataset folder
* `docs/Report.pdf` — final written report
* `docs/G8_Poster.pdf` — final poster

## How to Run

1. Download or clone this repository.
2. Install the required libraries:

```bash
pip install -r requirements.txt
```

3. Make sure the dataset is placed inside the `data/` folder.
4. Open the notebook:

```text
G8_CS_DS_AQI_Beijing.ipynb
```

5. Run all cells from top to bottom.

## Group Members

* Adam Harris bin Mohd Rezal (A212238)
* Mirza bin Ahmad Hafiz (A214180)
* Muhammad Aiman bin Ahmad Aswadi (A212178)
