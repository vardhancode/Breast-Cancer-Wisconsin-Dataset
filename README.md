# Breast-Cancer-Wisconsin-Dataset

We worked on the Breast Cancer dataset by first importing it using the sklearn.datasets module and then converting it into a pandas DataFrame for easier handling. Using libraries like pandas, NumPy, and Matplotlib, we began by inspecting the data structure, checking the shape, column names, and looking for any missing or irrelevant values. We identified and removed unnecessary columns (like 'Unnamed: 32') and confirmed that there were no null values left in the dataset.

For categorical features such as the 'diagnosis' column (which contains labels like 'M' for malignant and 'B' for benign), we applied encoding using the get_dummies() function to convert them into numeric form. We also briefly explored the data through basic visualizations using Seaborn and Matplotlib. Finally, we saved the cleaned and preprocessed dataset as a .csv file to be used in later stages, such as Exploratory Data Analysis (EDA) or building predictive models. 
