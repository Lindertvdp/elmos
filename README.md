# Sales Analysis Case
You are a data analyst from Ikea. Your manager has asked you to analyze the company's sales over the last year and provide insights on the company's top-selling products, most profitable regions, and customer behavior.


## Exercise Instructions
### Data

- **Order ID:** Unique identifier for each order
- **Date:** Date of the transaction
- **Product:** Name of the product
- **Category:** Category of the product (e.g., clothing, accessories)
- **Price:** Price of the product
- **Age**: Age of the customer
- **Provence:** Provence where the sale took place
- **Customer ID:** Unique identifier for each customer
- **Quantity:** Quantity of the product sold in the transaction

The dataset is located in the `data` folder with the name sales_data.csv


### Tasks
1. Calculate the total sales revenue for the company over the last year and visualize the trend over time. You can add extra dimensions to the visualization if you wish.
2. Identify the top-selling products and categories, as well as their sales revenue and quantity sold.
3. Analyze the sales by region and identify the most profitable regions for the company.
4. Determine customer behavior by analyzing the number of transactions and average transaction value
5. Calculate the 95th percentile of the total sales revenue per customer. This is the amount of money that 95% of the customers spend on average.

*You can solve the questions in the exercise.ipynb notebook or in a separate notebook. You can also use any other tool you prefer (e.g., Tableau, Power BI, etc.).*

## Requirements
- Python 3.6+
- Jupyter Notebook
- Libraries: pandas, numpy, matplotlib, seaborn

### GItHub Codespaces
You can use GitHub Codespaces to run the notebook in the cloud. To do so, click on the green "Code" button and select "Open with Codespaces". This will open a new tab with the notebook running in the cloud. You can then edit the notebook and run the code.

### Local Environment
If you prefer to run the notebook locally, you can clone the repository and install the required libraries using the following commands:
```bash
    git clone
    cd sales-analysis-case
    pip install -r requirements.txt
```
Then, open the notebook using Jupyter Notebook:
    
        jupyter notebook

## Submission
Please submit your solution as a link to a GitHub repository. Mailing this to the competence manager.

## Generating the dataset
The dataset is already pre-generated using the ./data/generate_product_data.py script. If you want to generate a new dataset, you can run the following command:

    python ./data/generate_product_data.py