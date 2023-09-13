# Data-Wrangling
##Introduction
***

Based on two datasets including:
- Records of product price change history in September 2018 (prices.csv):
  |Column name|Data Type|
  |:---------|:———------|
  |product_id|integer|
  |old_price|integer|
  |new_price|integer|
  |update_at|Series|
- And records of product sales in September 2018 (sales.csv):
  |Column name|Data Type|
  |:---------|:———------|
  |product_id|integer|
  |ordered_at|Series|
  |quantity_ordered|integer|
The goal is to calculate the total revenue of each product at each price level. Expected output:
  |Column name|Data Type|
  |:---------|:———------|
  |product_id|integer|
  |price|float|
  |total|float|
