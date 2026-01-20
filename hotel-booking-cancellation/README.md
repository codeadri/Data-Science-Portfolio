# Hotel Booking Cancellation Prediction

This project predicts whether a customer will cancel their hotel booking using historical booking data.  
The objective is to build a machine learning model that learns customer behavior patterns and predicts booking cancellation for unseen data.

---

## Problem Statement

Given customer booking details, predict whether a hotel booking will be **cancelled (1)** or **not cancelled (0)**.

This is a binary classification problem.

---

## Dataset Description

The dataset contains the following files:

- `train.csv` – Training dataset with features and target
- `test.csv` – Test dataset with target hidden
- `sample_submission.csv` – Submission format reference

### Features

| Column | Description |
|------|------------|
| id | Record identifier |
| adults | Number of adults |
| children | Number of children |
| weekends | Number of weekend days |
| weekdays | Number of weekday days |
| meal_type | Meal type selected |
| room_type | Room type selected |
| arrival | Arrival date |
| lead_time | Days between booking and arrival |
| segment | Booking segment |
| repeat | Previous booking indicator |
| price | Average room price |
| requests | Special requests count |
| booking_status | Target variable (1 = Cancelled, 0 = Not Cancelled) |

---

## Approach

1. Data Cleaning and preprocessing  
2. Date feature extraction from arrival date  
3. Handling missing values  
4. Encoding categorical features  
5. Model training using machine learning classifiers  
6. Model evaluation and prediction generation  

---

## Model Objective

To maximize classification performance while ensuring generalization on unseen customer bookings.

---

## Setup Instructions

1. Install dependencies:

```bash
pip install -r requirements.txt
