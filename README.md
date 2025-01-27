# Data Science Assignment: eCommerce Transactions Dataset

## Overview:
This assignment involves analyzing an eCommerce Transactions dataset containing three files: **Customers.csv**, **Products.csv**, and **Transactions.csv**. The objective is to perform Exploratory Data Analysis (EDA), build predictive models, and derive actionable insights to demonstrate data analysis, machine learning, and business insight generation skills.

---

## Dataset Description:
The dataset comprises three files:

### 1. Customers.csv
| Column Name     | Description                                      |
|-----------------|--------------------------------------------------|
| **CustomerID**  | Unique identifier for each customer.            |
| **CustomerName**| Name of the customer.                           |
| **Region**      | Continent where the customer resides.           |
| **SignupDate**  | Date when the customer signed up.               |

**File Link:** [Download Customers.csv](https://drive.google.com/file/d/1bu_--mo79VdUG9oin4ybfFGRUSXAe-WE/view?usp=sharing)

### 2. Products.csv
| Column Name     | Description                                      |
|-----------------|--------------------------------------------------|
| **ProductID**   | Unique identifier for each product.             |
| **ProductName** | Name of the product.                            |
| **Category**    | Product category.                               |
| **Price**       | Product price in USD.                           |

**File Link:** [Download Products.csv](https://drive.google.com/file/d/1IKuDizVapw-hyktwfpoAoaGtHtTNHfd0/view?usp=sharing)

### 3. Transactions.csv
| Column Name       | Description                                   |
|-------------------|-----------------------------------------------|
| **TransactionID** | Unique identifier for each transaction.       |
| **CustomerID**    | ID of the customer who made the transaction.  |
| **ProductID**     | ID of the product sold.                       |
| **TransactionDate**| Date of the transaction.                    |
| **Quantity**      | Quantity of the product purchased.            |
| **TotalValue**    | Total value of the transaction.               |
| **Price**         | Price of the product sold.                    |

**File Link:** [Download Transactions.csv](https://drive.google.com/file/d/1saEqdbBB-vuk2hxoAf4TzDEsykdKlzbF/view?usp=sharing)

---

## Assignment Tasks:

### **Task 1: Exploratory Data Analysis (EDA) and Business Insights**
1. Perform EDA on the provided dataset.
2. Derive at least **5 business insights** from the EDA.
   - Insights should be written as short, point-wise sentences (max 100 words per insight).

**Deliverables:**
- A Jupyter Notebook/Python script containing your EDA code.
- A PDF report summarizing business insights (max 500 words).

---

### **Task 2: Lookalike Model**
Build a Lookalike Model that takes a user's information as input and recommends **3 similar customers** based on their profile and transaction history. The model should:
- Use both customer and product information.
- Assign a similarity score to each recommended customer.

**Deliverables:**
- Provide the top 3 lookalikes with their similarity scores for the first **20 customers** (CustomerID: C0001 - C0020) in **Customers.csv**.
- Form a CSV file: `Lookalike.csv` containing one map: `Map<cust_id, List<cust_id, score>>`.
- A Jupyter Notebook/Python script explaining your model development.

---

### **Task 3: Customer Segmentation / Clustering**
Perform customer segmentation using clustering techniques. Use both profile information (from **Customers.csv**) and transaction information (from **Transactions.csv**).
- Choose any clustering algorithm.
- Form between **2 and 10 clusters**.
- Calculate clustering metrics, including the **DB Index** (this will be evaluated).
- Visualize your clusters using relevant plots.

**Deliverables:**
- A report on your clustering results, including:
  - Number of clusters formed.
  - DB Index value.
  - Other relevant clustering metrics.
- A Jupyter Notebook/Python script containing your clustering code.

---

## Evaluation Criteria:
1. **EDA:**
   - Quality and depth of insights derived from the dataset.
   - Visualizations and clear representation of findings.

2. **Lookalike Model:**
   - Model accuracy and logical approach.
   - Quality of recommendations and similarity scores.

3. **Customer Segmentation:**
   - Metrics used to evaluate clustering performance.
   - Interpretability and visualization of clusters.

