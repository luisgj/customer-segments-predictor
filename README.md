# identify-customer-segments
## Unsupervised Learning

A Udacity project, which aims to apply unsupervised learning techniques on demographic and spending data for a sample of German households. You will preprocess the data, apply dimensionality reduction techniques, and implement clustering algorithms to segment customers with the goal of optimizing customer outreach for a mail order company

> **The data for this project were provided by Arvato Financial Services and are removed as they are only for use in the Unsupervised Learning and Bertelsmann Capstone projects**


### The Data
- `Udacity_AZDIAS_Subset.csv`: Demographic data for the general population of Germany; 891211 persons (rows) x 85 features (columns) **this file is removed prior to the agreement**.
- `Udacity_CUSTOMERS_Subset.csv:` Demographic data for customers of a mail-order company; 191652 persons (rows) x 85 features (columns) **this file is removed prior to the agreement**.
- `Data_Dictionary.md`: Information file about the features in the provided datasets.
- `AZDIAS_Feature_Summary.csv`: Summary of feature attributes for demographic data **this file is removed prior to the agreement**.
- `Identify_Customer_Segments.ipynb`: Jupyter Notebook divided into sections and guidelines for the project. 

### 1: Preprocessing
This step requires the assessment of missing data by using the feature summary file to map the codes provided for any missing or unknown values and converting them to NaNs, it also requires the visualization of missing data row and column wise. Then it requires to encode features based on its data types and lastly combining all the work in a single function to be reused later.

### 2: Feature Transformation
In this step data cleaning and feature scaling is conducted prior to applying dimensionality reduction. Lastly, I have interpreted the principal components.


### 3: Clustering
This step finally applies the model and trains it using Kmeans algorithm. afterwards I applied the final model to the general demographic and all the steps to the customers data. Lastly, we compare both datasets and identify the customers segments the mail order company would benefit from.Finding cluster on customer data.
