# Predicting Hotel Booking Cancellations

This project looks at whether information available about a hotel booking can be used to predict if the booking will be cancelled.

The dataset used is the Hotel Booking Demand dataset, which contains booking data from a resort hotel and a city hotel in Portugal.

## Setup

The project was completed using Python in Jupyter Notebook.

The main packages used are:

- pandas
- scikit-learn
- matplotlib
- numpy

The required Python packages are listed in `requirements.txt`.

The dataset file `hotel_bookings.csv` should be placed in the same folder as the notebooks.

## Running the Project

The project contains three notebooks:

- `01_data_audit.ipynb` – Milestone 2: Data exploration, cleaning, preprocessing and a baseline model.
- `02_M3_model_comparison.ipynb` – Milestone 3: Training and comparing Logistic Regression, Decision Tree and Random Forest models.
- `03_M4_final_analysis.ipynb` – Milestone 4: Final model evaluation, feature importance, ROC and precision-recall curves, calibration and error analysis.

Open the notebooks in Jupyter Notebook and run the cells in order from top to bottom.

All three notebooks require `hotel_bookings.csv` to be in the same folder.

## Results

Random Forest was the best-performing model, achieving the following results on the held-out test set:

- Accuracy: 88.93%
- Precision: 88.38%
- Recall: 80.77%
- F1 Score: 84.40%

The project also discusses limitations such as duplicate records, the random train-test split and the risks of using predictions to make decisions about individual guests.

## AI Assistance Declaration

I used Claude during this project to help explain machine learning concepts, plan the different stages of the work, assist with coding and debugging when i encountered problems, and interpret results. I also used it to help structure and format parts of the final report. I created the code, ran the notebooks, cecked results, wrote the report and made the 5 minutes explanation video myself.

## Repository

https://github.com/Seanmcdonaldx/hotel-booking-cancellation-ml
