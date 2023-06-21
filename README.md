# Analysis on Supply Chain

## 🔗 Project Links
- [Data Cleaning on Jupyter Notebook](Data_Cleaning_Supply_Chain_Analytics.ipynb)
- [Interactive Dashboard on Tableau]() (Work in Progress)

## 📖 Background
Test your BI skills on a real-world dataset focusing on supply chain analytics. As the main data analyst for Just In Time, you will help solve key shipment and inventory management challenges, analyze supply chain inefficiencies, and create insightful dashboards to inform business stakeholders about potential problems and propose structural business improvements.

## 💾 The data
| Group | Column name | Dataset | Definition |
|:---|:---|:---|:---|
| Customer | Customer ID | orders_and_shipments.csv | Unique customer identification |
| Customer | Customer Market | orders_and_shipments.csv | Geographic grouping of customer countries, with values such as Europe, LATAM, Pacific Asia, etc. |
| Customer | Customer Region | orders_and_shipments.csv | Geographic grouping of customer countries, with values such as Northern Europe, Western Europe, etc. |
| Customer | Customer Country | orders_and_shipments.csv | Customer's country |
| Order info | Order ID | orders_and_shipments.csv | Unique Order identification. Order groups one or multiple Order Items |
| Order info | Order Item ID | orders_and_shipments.csv | Unique Order Item identification. Order Item always belong to just one Order |
| Order info | Order Year | orders_and_shipments.csv | Year of the order |
| Order information | Order Month | orders_and_shipments.csv | Month of the order |
| Order information | Order Day | orders_and_shipments.csv | Day of the order |
| Order information | Order Time | orders_and_shipments.csv | Timestamp of the order in UTC |
| Order information | Order Quantity | orders_and_shipments.csv | The amount of items that were ordered within a given Order Item (1 record of the data) |
| Product | Product Department | orders_and_shipments.csv | Product grouping into categories such as Fitness, Golf, Pet Shop, etc. |
| Product | Product Category | orders_and_shipments.csv | Product grouping into categories such as Sporting Goods, Women's Apparel, etc. |
| Product | Product Name | orders_and_shipments.csv | The name of the purchased product |
| Sales | Gross Sales | orders_and_shipments.csv | Revenue before discounts generated by the sales of the Order Item (1 record of the data) |
| Sales | Discount % | orders_and_shipments.csv | Discount % applied on the catalog price |
| Sales | Profit | orders_and_shipments.csv | Profit generated by the sales of the Order Item (1 record of data) |
| Shipment information | Shipment Year | orders_and_shipments.csv | Year of the shipment |
| Shipment information | Shipment Month | orders_and_shipments.csv | Month of the shipment |
| Shipment information | Shipment Day | orders_and_shipments.csv | Day of the shipment |
| Shipment information | Shipment Mode | orders_and_shipments.csv | Information on how the shipment has been dispatched, with values as First Class, Same Day, Second Class, etc. |
| Shipment information | Shipment Days - Scheduled | orders_and_shipments.csv | Information on typical amount of days needed to dispatch the goods from the moment the order has been placed |
| Warehouse | Warehouse Country | orders_and_shipments.csv | Country of the warehouse that has fulfilled this order, the only two values being Puerto Rico and USA |
| Inventory & Fulfillment | Warehouse Inventory | inventory.csv | The monthly level of inventory of a product, e.g. 930 units |
| Inventory & Fulfillment | Inventory cost per unit | inventory.csv | The monthly storage cost per unit of inventory, e.g. $2.07 |
| Inventory & Fulfillment | Warehouse Order fulfillment (days) | fulfillment.csv | The average amount of days it takes to refill stock if inventory drops below zero |

## 🔍 Executive Summary

- Work in progess.
