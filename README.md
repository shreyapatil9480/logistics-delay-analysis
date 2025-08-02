https://github.com/shreyapatil9480/logistics-delay-analysis/new/main
# Logistics Delivery Delay Analysis

This project contains a synthetic dataset and an end-to-end analysis pipeline for predicting shipping delays in a logistics operation. 

## Project Overview

Many companies rely on on‑time deliveries to satisfy customers and manage costs. Delays can lead to lost sales, increased expenses, and poor customer satisfaction. This repository provides an illustrative example of how a data analyst or business analyst might use Python to explore operational data, visualize patterns, and build predictive models to identify shipments at risk of being delayed.

**Key objectives of this project:**

1. **Explore** a logistics dataset that includes order, product, shipment, and customer details.
2. **Visualize** relationships between shipment attributes and delays.
3. **Develop** a classification model that predicts whether a shipment will arrive late based on information available at the time an order is placed.
4. **Communicate** insights and recommendations for reducing delay rates.

## Repository Contents

| File | Description |
| --- | --- |
| `logistics_delay_data.csv` | Synthetic dataset containing 1,500 shipments with features such as order date, shipping mode, weight, distance, cost, and delay information. |
| `logistics_delay_analysis.ipynb` | Jupyter notebook with step‑by‑step analysis, visualizations, model training, and business insights. |
| `requirements.txt` | List of Python packages required to run the notebook (pandas, numpy, scikit‑learn, matplotlib, seaborn). |

## Getting Started

1. **Clone or download this repository** to your local machine.
2. (Optional) Create a virtual environment and install the required packages:

   ```bash
   python3 -m venv venv
   source venv/bin/activate
   pip install -r requirements.txt
   ```

3. **Open** `logistics_delay_analysis.ipynb` in Jupyter Notebook or VS Code and run the cells to reproduce the analysis.

## Dataset Fields

| Column | Description |
| --- | --- |
| `order_id` | Unique identifier for each shipment order. |
| `order_date` | Date the order was placed. |
| `shipping_mode` | Delivery service level (Standard Class, Second Class, First Class, Same Day). |
| `product_category` | High‑level category of the product ordered. |
| `product_subcategory` | Specific subcategory of the product. |
| `weight_kg` | Weight of the package in kilograms. |
| `distance_km` | Approximate distance between warehouse and delivery destination. |
| `shipping_cost` | Cost charged for shipping the order. |
| `expected_delivery_date` | Date the shipment is expected to arrive based on mode. |
| `actual_delivery_date` | Date the shipment actually arrived. |
| `delay_days` | Number of days the shipment was late (0 if on time). |
| `is_delayed` | Binary flag indicating whether the shipment was delayed (`1`) or not (`0`). |
| `warehouse_region` | Region (North, South, East, West) from which the order was shipped. |
| `customer_segment` | Customer type (Consumer, Corporate, Home Office). |

## Business Questions Addressed

- Which shipping modes are most prone to delays?
- How do weight and distance influence the likelihood of a delay?
- Are certain product categories or warehouse regions more susceptible to late deliveries?
- What is the accuracy of models (e.g., logistic regression, random forest) in predicting late shipments?

## License

This project is released under the MIT License. You are free to use, modify, and distribute the code and dataset for educational and non‑commercial purposes.
