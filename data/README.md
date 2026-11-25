# Dataset

## Source
This project uses the [Brazilian E-Commerce Public Dataset by Olist](https://www.kaggle.com/datasets/olistbr/brazilian-ecommerce), available on Kaggle.

The dataset contains anonymized e-commerce transactions from Olist's marketplace in Brazil, covering September 2016 through September 2018.

## Dataset Files
The analysis uses eight interconnected CSV files:

| File | Description |
|---|---|
| `olist_order_items_dataset.csv` | Individual products purchased within each order |
| `olist_orders_dataset.csv` | Order status and purchase and delivery timestamps |
| `olist_customers_dataset.csv` | Customer information and location |
| `olist_products_dataset.csv` | Product attributes, including category and weight |
| `olist_sellers_dataset.csv` | Seller information and location |
| `olist_order_payments_dataset.csv` | Payment methods and transaction amounts |
| `olist_order_reviews_dataset.csv` | Customer review scores and comments |
| `product_category_name_translation.csv` | Portuguese-to-English product category translations |

## Data Access
The original CSV files are not included in this repository.

To reproduce the analysis:
1. Visit the Kaggle dataset linked above.
2. Download the dataset files.
3. Extract the CSV files.
4. Place the files in this `data/` directory.

## Notes
- The dataset contains anonymized marketplace transaction records.
- The project integrates eight source files into an order-item-level analytical dataset.
- The original dataset is maintained by Olist and distributed through Kaggle.
