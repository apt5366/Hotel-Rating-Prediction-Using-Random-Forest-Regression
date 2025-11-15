Hotel Rating Prediction (Random Forest Regression)

This project looks at 4,599 TripAdvisor hotel reviews and builds a model to predict how customers rate hotels. The goal was to understand which factors (like pricing, location grade, views, and discounts) influence customer satisfaction the most.

Cleaned the dataset by removing invalid entries (e.g., zero views), dropping unnecessary columns, and handling missing/∞ values.

Selected key features: views, location_grade, discount_perc, price_min.

Trained a Random Forest Regressor with an 80/20 train–test split.

Used GridSearchCV to tune parameters.

Best parameters found:

n_estimators = 150

min_samples_split = 10

min_samples_leaf = 4

max_depth = None

Achieved a test MSE of 0.0829.

Ran feature-importance analysis to see which factors influence ratings the most (price_min came out highest).

Tech Used

Python, Pandas, NumPy, Scikit-learn, Matplotlib, Jupyter Notebook

Project Structure
