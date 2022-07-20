# KMeans-Retail-RFM

Applied k-means algorithm to cluster the customers of an online retailer based on their recency, frequency, and monetary value (rfm). The dataset used for this project was stored on a local mysql database and contains purchases made for an online retail company during an eight month period.

For this project we define a customer's recency as the number of days between the date of their most recent purchase and the date of the most recent purchase of any customer in the dataset plus one day, a customer's frequency as the total number of purchases made by that customer in the eight month period, and a customer's monetary value as the total amount they spent on purchases over the eight month period.<br />

The data was cleaned with python using pandas, and then the relevant features (recency, frequency, and monetary value) were extracted with SQL.
The data was investigated further using pandas and matplotlib, and then customers were clustered based on their RFM data using sklearn's implementation of k-means.

**Python Libraries Used:**<br />
pandas, numpy, mysql, matplotlib, sklearn, configparser (to hide my login details when connecting to my database), re (regular expressions)

**Dataset:**<br />
https://www.kaggle.com/datasets/vijayuv/onlineretail <br />
Owner: Vijaykumar Ummadisetty
