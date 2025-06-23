# task_1
What I Did: I made a Python script to load the Titanic  dataset, checked its details, filled missing values (mean for numbers, mode for text), removed duplicates, and cut outliers using IQR. I scaled numbers with MinMaxScaler, encoded text with one-hot encoding, and showed outliers with box plots.
How It Works: I used pandas to load and check data (head(), info(), describe()), filled missing values with loops, dropped duplicates with drop_duplicates(), and filtered outliers with IQR. I scaled with MinMaxScaler, encoded with pd.get_dummies, and plotted with Seaborn.
What I Learned: I learned to clean data for ML, fix missing values, remove outliers, scale numbers, encode text, and build a simple pipeline with pandas and scikit-learn.
