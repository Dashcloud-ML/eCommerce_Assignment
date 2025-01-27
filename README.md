# eCommerce Data Science Assignment

This repository contains the solution for the eCommerce Transactions Dataset assignment, designed to test exploratory data analysis, predictive modeling, and clustering skills. The project is divided into three tasks: Exploratory Data Analysis (EDA), Lookalike Model, and Customer Segmentation.

---

## **Project Overview**

The eCommerce Transactions dataset consists of three files:
1. `Customers.csv`: Contains customer profiles.
2. `Products.csv`: Contains product details.
3. `Transactions.csv`: Contains transaction histories.

### **Tasks**
1. **Exploratory Data Analysis (EDA)**:
   - Analyze customer, product, and transaction data.
   - Derive actionable business insights.
   - Provide visualizations to support findings.

2. **Lookalike Model**:
   - Build a model to recommend three similar customers for the first 20 customers based on transaction history and profile information.

3. **Customer Segmentation**:
   - Perform customer segmentation using clustering techniques.
   - Evaluate clusters using the Davies-Bouldin Index and visualize the results.

---

## **Repository Structure**

```plaintext
eCommerce_Assignment/
├── EDA/
│   ├── FirstName_LastName_EDA.ipynb   # Jupyter Notebook for EDA
│   ├── FirstName_LastName_EDA.pdf     # PDF report with business insights
├── Lookalike_Model/
│   ├── FirstName_LastName_Lookalike.ipynb  # Jupyter Notebook for Lookalike Model
│   ├── FirstName_LastName_Lookalike.csv    # CSV with lookalike recommendations
├── Clustering/
│   ├── FirstName_LastName_Clustering.ipynb  # Jupyter Notebook for clustering
│   ├── FirstName_LastName_Clustering.csv    # CSV with cluster assignments
│   ├── FirstName_LastName_Clustering.pdf    # PDF report with clustering insights
└── README.md

## **How to Run the Notebooks**

Follow these steps to run the notebooks and reproduce the results:

### **Prerequisites**
1. Install Python (3.7 or above) and Jupyter Notebook.
2. Install the required Python libraries:
   ```bash
   pip install pandas numpy matplotlib seaborn scikit-learn
Steps to Run:
Clone the repository to your local system:

bash
Copy
Edit
git clone https://github.com/<YourGitHubUsername>/eCommerce_Assignment.git
cd eCommerce_Assignment
Open Jupyter Notebook:

bash
Copy
Edit
jupyter notebook
Navigate to the respective task folder:

EDA/ for Exploratory Data Analysis.
Lookalike_Model/ for the Lookalike Model.
Clustering/ for Customer Segmentation.
Open the corresponding notebook:

FirstName_LastName_EDA.ipynb
FirstName_LastName_Lookalike.ipynb
FirstName_LastName_Clustering.ipynb
Run the cells sequentially to execute the code:

Ensure the datasets (Customers.csv, Products.csv, Transactions.csv) are in the working directory.
Results will be generated as described in the notebook.
Expected Outputs
EDA Notebook:

Visualizations and insights.
Merged dataset saved as Merged_Data.csv.
Lookalike Model Notebook:

A CSV file named FirstName_LastName_Lookalike.csv containing recommendations.
Clustering Notebook:

A CSV file named FirstName_LastName_Clustering.csv with cluster assignments.
Visualizations of customer clusters.
