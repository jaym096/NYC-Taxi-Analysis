# NYC-Taxi-Analysis
- Implemented a predictive model to predict the total fare by analyzing 40 million past trips and built a stacked ensemble model using XGBoost and LGBM.
- Performed Data Cleaning & Data Preprocessing, feature engineering, data visualization to select the best features.
- Evaluated and assessed the model on the test data using Mean-Squared Error as a performance metric.

**Technology used:** Python, Pandas, NumPy, Jupyter Notebook, SQLite, SQLalchemy, XGBoost, Sckit-Learn, Seaborn, matplotlib

Major goal to do this project was to work with the data from scratch, starting from downloading it to ingesting it into a database to performing data-preprocessing. And thus, instead of using the well structed data from Kaggle, I used the raw data avaialble from the TLC website. I also got the opportuninty to work with a database for data analysis task, and learn how to use and ensemble model. I use SQLite and SQLalchemy as ORM to interact with the DB. For exploratory data analysis I preferred seaborn and matplotlib. And, used XGBoost and LGBM to train the models using GridSearchCV with cross-validation for parameter selection and at the last, I ensembled the best prediction.

The data is taken from here: https://www1.nyc.gov/site/tlc/about/tlc-trip-record-data.page \
The data from Kaggle can be downloaded from here: https://www.kaggle.com/c/new-york-city-taxi-fare-prediction/data
