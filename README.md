Engage2 — Click to Conversion
Goal: Predict a customer’s purchase value from multi-session behavior across digital touchpoints.

Achieved top-3% standing (Rank 60/1792) with an R² of 0.70 on the test leaderboard by modeling purchase value from multi-source clickstream signals.

Engineered time-based features from Unix timestamps (weekday, month, hour, weekend flag, period encoding) and standardized numerical signals to capture session dynamics.

Addressed heavy zero-inflation and target skew via distribution analysis, category segmentation, and robust modeling to mitigate overfitting.

Built comparative pipelines (XGBoost, Random Forest, Extra Trees) with ColumnTransformer-based preprocessing; selected ExtraTreesRegressor for best generalization.

Implemented KNN-based imputation, handled “(not set)”/“not available in demo dataset” artifacts, and dropped high-cardinality/constant/identifier features for cleaner training.

Delivered reproducible train/validation split, feature importance analysis, and Kaggle-ready submission pipeline.

