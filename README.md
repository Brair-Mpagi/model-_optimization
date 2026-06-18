A machine learning repository featuring Linear and Logistic Regression models built with scikit-learn. Includes hyperparameter tuning via GridSearchCV to predict income trends ($R^2 \approx 0.94$) and classify candy attributes (Accuracy $\approx 88.2\%$).

## Included Projects & Performance Metrics

### 1. Candy Classification (`logistic-candy`)
* **Objective:** Predict whether a candy brand is chocolate-based using features like sugar, price, and overall win percentages.
* **Algorithm:** Logistic Regression (optimized with `liblinear` solver).
* **Optimization:** 5-fold cross-validation grid search (`GridSearchCV`).
* **Performance:** **88.24% Accuracy** on the test dataset.

### 2. Income Prediction (`linear-inc-age`)
* **Objective:** Predict annual income based on an individual's age and years of professional experience.
* **Algorithm:** Multiple Linear Regression.
* **Optimization:** Exhaustive parameter search over interception and job threading configurations.
* **Performance:** **0.9387 $R^2$ Score** (explaining ~94% of variance on test data).
