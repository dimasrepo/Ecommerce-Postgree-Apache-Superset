## Dataset Variables

### `product_category_name_translation`
- **`product_category_name`**: Product category name in the original language (VARCHAR).
- **`product_category_name_english`**: Product category name in English (VARCHAR).

### `olist_sellers_dataset`
- **`seller_id`**: Unique identifier for the seller (VARCHAR).
- **`seller_zip_code_prefix`**: Zip code prefix of the seller's location (INTEGER).
- **`seller_city`**: City where the seller is located (VARCHAR).
- **`seller_state`**: State where the seller is located (VARCHAR).

### `olist_products_dataset`
- **`product_id`**: Unique identifier for the product (VARCHAR).
- **`product_category_name`**: Product category name (VARCHAR).
- **`product_name_length`**: Length of the product name in characters (INTEGER).
- **`product_description_length`**: Length of the product description in characters (INTEGER).
- **`product_photos_qty`**: Number of photos available for the product (INTEGER).
- **`product_weight_g`**: Weight of the product in grams (INTEGER).
- **`product_length_cm`**: Length of the product in centimeters (INTEGER).
- **`product_height_cm`**: Height of the product in centimeters (INTEGER).
- **`product_width_cm`**: Width of the product in centimeters (INTEGER).

### `olist_orders_dataset`
- **`order_id`**: Unique identifier for the order (VARCHAR).
- **`customer_id`**: Unique identifier for the customer (VARCHAR).
- **`order_status`**: Current status of the order (e.g., delivered, canceled) (VARCHAR).
- **`order_purchase_timestamp`**: Timestamp when the order was placed (TIMESTAMP).
- **`order_approved_at`**: Timestamp when the order was approved (TIMESTAMP).
- **`order_delivered_carrier_date`**: Timestamp when the order was delivered to the carrier (TIMESTAMP).
- **`order_delivered_customer_date`**: Timestamp when the order was delivered to the customer (TIMESTAMP).
- **`order_estimated_delivery_date`**: Estimated delivery date of the order (TIMESTAMP).

### `olist_order_payments_dataset`
- **`order_id`**: Unique identifier for the order (VARCHAR).
- **`payment_sequential`**: Sequential payment number for the order (INTEGER).
- **`payment_type`**: Type of payment method used (e.g., credit card, bank transfer) (VARCHAR).
- **`payment_installments`**: Number of installments for the payment (INTEGER).
- **`payment_value`**: Payment value in currency (REAL).

### `olist_order_items_dataset`
- **`order_id`**: Unique identifier for the order (VARCHAR).
- **`order_item_id`**: Unique identifier for the order item (INTEGER).
- **`product_id`**: Unique identifier for the product (VARCHAR).
- **`seller_id`**: Unique identifier for the seller (VARCHAR).
- **`shipping_limit_date`**: Timestamp when the shipping limit for the order item was set (TIMESTAMP).
- **`price`**: Price of the order item (REAL).
- **`freight_value`**: Freight value for the order item (REAL).

### `olist_geolocation_dataset`
- **`geolocation_zip_code_prefix`**: Zip code prefix of the location (INTEGER).
- **`geolocation_lat`**: Latitude of the location (REAL).
- **`geolocation_lng`**: Longitude of the location (REAL).
- **`geolocation_city`**: City of the location (VARCHAR).
- **`geolocation_state`**: State of the location (VARCHAR).

### `olist_customers_dataset`
- **`customer_id`**: Unique identifier for the customer (VARCHAR).
- **`customer_unique_id`**: Unique customer identifier (VARCHAR).
- **`customer_zip_code_prefix`**: Zip code prefix of the customer's location (INTEGER).
- **`customer_city`**: City where the customer resides (VARCHAR).
- **`customer_state`**: State where the customer resides (VARCHAR).
