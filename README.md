**Medicine Dataset Clustering and Cleaning**

This project cleans and clusters a medicine dataset based on attributes like salts, dosage, and packaging.


**Features:**

➡️Data Preprocessing:
Standardizes column names and cleans textual data (e.g., medicine names, manufacturers).
Imputes missing numerical and categorical values with median and mode, respectively.
Removes duplicates and non-alphanumeric characters.

➡️Clustering:
Applies K-Means clustering to segment the dataset based on combined feature vectors (salts, quantity, packaging form).

➡️Evaluation:
Compares predicted clusters with manually labeled clusters using clustering evaluation metrics (Adjusted Rand Index, Precision, Recall, F1 Score).


**Libraries:**
→ pandas
→ numpy
→ scikit-learn 
