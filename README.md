**Market Basket Analysis using Apriori Algorithm**

**Project Overview:**
This project performs **Market Basket Analysis** on a groceries dataset using the Apriori algorithm.
Association rule mining helps identify relationships between products that are frequently purchased together. These insights can assist retailers in making informed decisions related to product placement, promotions, and recommendations.
 Dataset:
- Name: Groceries Dataset
- File Used: `Groceries_dataset.csv`
- Attributes: `Member_number`, `Date`, `itemDescription`



**Technologies Used:**

1.Language: Python

2. Libraries:
  - `pandas`
  - `numpy`
  - `itertools`
  - `time`
  - `collections`
  - `apyori` (Apriori Algorithm package)



**Project Workflow:**

1. Load Dataset: Read and explore the groceries dataset.
2. Data Preprocessing: Handle date format and create transactions based on member and date.
3. Exploratory Data Analysis (EDA): Visualize and analyze transaction samples.
4. Apply Apriori Algorithm: Use `apyori` library to generate frequent itemsets and association rules.
5. Display Rules: Extract and display the discovered rules with support, confidence, and lift.
6. Conclusion: Summarize the business insights obtained.


**Output Example:**

Rule: {'whole milk'} --> {'other vegetables'}
Support: 0.025
Confidence: 0.42
Lift: 3.50

**Conclusion:**

1.The Apriori algorithm successfully identified meaningful associations between products.

2.These rules can enhance cross-selling opportunities and optimize product placements.

3.For larger datasets, the FP-Growth algorithm can be explored for better performance.

**How to Run This Project:**

1. Install required libraries using `pip install pandas numpy apyori`.
2. Download and place `Groceries_dataset.csv` in your project directory.
3. Run the Jupyter Notebook file `Market_Basket_Analysis_Apriori.ipynb`.
4. Analyze the generated association rules.
