# Hotel Booking Project

Group project for CSE 434/534 (Machine Learning).

We use the hotel bookings dataset to build two kinds of models:

- **Regression:** predict `adr` (average daily rate)
- **Classification:** predict `is_canceled` (1 = canceled, 0 = not canceled)

`reservation_status` and `reservation_status_date` are excluded from the features because they reveal the final outcome.

## Files

- `Project_Starter.ipynb`: starter notebook (written to run in Google Colab)
- `data/hotels.csv`: dataset (about 119k bookings, 32 columns)

## Data

Source: [TidyTuesday 2020-02-11 data dictionary](https://github.com/rfordatascience/tidytuesday/blob/main/data/2020/2020-02-11/readme.md).

The CSV has literal `NULL`/`NA` values, so check the dictionary before treating them as missing.

## Running the notebook

Upload `data/hotels.csv` to the Colab Files panel, then run the notebook. Keep the original DataFrame (`raw_data`) unchanged and do preprocessing on a copy.
