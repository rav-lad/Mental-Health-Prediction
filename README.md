

# Mental Health Prediction – Kaggle Playground Series 

**Achieved Top 9% on the "Mental Health Prediction" competition**

##  Overview

This project tackles the \[Kaggle Playground Series – Mental Health Prediction (Nov 1 to Dec 1, 2024)] dataset. The goal: predict **depression status** from survey data. Evaluation was based on **accuracy**, and this version ranks within the **top 9%** of all participants.

##  Timeline

* **Competition open:** November 1, 2024
* **Deadline:** December 1, 2024 (11:59 PM UTC)
* **Metric:** Accuracy on the test set

##  Goals

* Explore factors associated with depression using survey features
* Build classification pipelines tuned for accuracy
* Analyze feature importance and model behavior


##  Methodology

### 1. EDA and Preprocessing

* Investigated class balance and handled missing values
* Encoded categorical variables and scaled numeric ones
* Created interaction terms and engineered meaningful features

### 2. Modeling

* Explored classifiers: Logistic Regression, Random Forests, XGBoost, LightGBM
* Used 5-fold cross-validation for robust evaluation
* Optimized hyperparameters with randomized search

### 3. Interpretation

* Output top features via feature\_importance\_plot.png
* Analyzed model behavior to understand key depression indicators

### 4. Submission

* Final model produced `submission.csv` — yielding top 9% accuracy on the leaderboard

##  Results

* **Leaderboard Performance:** Top 9% finish in the final ranking
* **Most impactful features:** include \[list 2–3 top features, e.g., “age, sleep\_hours, mental\_health\_history”]
* **Best model:** LightGBM classifier with tuned parameters



## Competiton Info

* Dataset from the **Kaggle Playground Series – Mental Health Prediction**
* Synthetic survey data used to forecast depression status
* Target submission format:

  ```
  id,Depression
  140700,0
  140701,0
  140702,1
  ...
  ```

##  Insights & Extensions

* **Feature importance** aligns with established mental health research
* **Predictive pipelines** are modular and easily extensible
* **Future directions:** incorporate feature interactions, deeper hyperparameter tuning, ensemble methods, or external data

##  Acknowledgements

Thanks to Kaggle and competition hosts. Credit to peers and mentors who contributed insights.

---


