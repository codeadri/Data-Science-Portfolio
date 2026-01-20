# Movie Sentiment Analysis

## Problem Statement

The objective of this project is to predict the **sentiment of a movie review** based on its textual content and associated features.

This is a **multi-class classification problem**, where the sentiment of a review is classified into one of the following categories:

- `0` → Negative  
- `1` → Neutral  
- `2` → Positive  

---

## Dataset Description

The dataset consists of the following files:

- `train.csv` – Training dataset containing features and target labels  
- `test.csv` – Test dataset with sentiment labels hidden  
- `sample_submission.csv` – Sample submission file specifying the correct output format  

---

## Features

| Column | Description |
|------|------------|
| id | Record identifier |
| phrase | Textual movie review |
| feature_1 | Additional numerical feature |
| feature_2 | Additional numerical feature |
| feature_3 | Additional numerical feature |
| sentiment | Target variable (0 = Negative, 1 = Neutral, 2 = Positive) |

---

## Approach

1. Text preprocessing of movie reviews  
2. Feature extraction from review text  
3. Handling numerical features  
4. Encoding target labels  
5. Training multi-class classification models  
6. Evaluation and prediction generation  

---

## Objective

To build a model that effectively captures sentiment patterns in movie reviews and generalizes well to unseen data.

---

## Setup Instructions

1. Install dependencies:

```bash
pip install -r requirements.txt
