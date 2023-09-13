# Data-Wrangling
##Introduction
***

Based on two datasets including:
- Records of product price change history in September 2018 (prices.csv):
.. list-table::
   :widths: 25 50 25 25
   :header-rows: 1

   * - Platform
     - Purpose
     - Estimated Response Time
     - Support Level
   * - `Discourse Forum`_
     - For discussions about development and questions about usage.
     - < 1 day
     - Community
   * - `GitHub Issues`_
     - For reporting bugs and filing feature requests.
     - < 2 days
     - Ray OSS Team
   * - `Slack`_
     - For collaborating with other Ray users.
     - < 2 days
     - Community
   * - `StackOverflow`_
     - For asking questions about how to use Ray.
     - 3-5 days
     - Community
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
