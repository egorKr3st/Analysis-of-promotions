# Analysis of the results of promotions in the store

There are three datasets: customers.csv, purchases.csv and shops.csv. They are stored in data folder.

customers.csv contains information about each customer registered in loyalty program.

shops.csv contains information about shops and special offers they organized. One shap can organize several offers and therefore there are usually several rows that correspond to the same shops. However, some shops do not organize special offers at all, but they are presented in this table nevertheless.

purchases.csv is a purchase log. It contains information for all customers, either registered in a loyalty program (in this case we know the corresponding customer id) or not registered. One purchase can be a collection of several items, but we see only the total price of everything bought.

**Project goal: Analyze the results of promotions in stores**
