# E-commerce_Reccomendation_Program
Python script that anaylyses cutomer transaction history and generates item recommendations based on the history.

Script reads 'history.txt' to extract information about the number of customers, items and transactions. It reads 'queries.txt.' to obtain a list of items in the current shopping cart. The program uses vectors to store items, and uses cosine to calculate average angles between items - the two products with the smallest difference in average angle are likely to be most similar and hence recommended to a consumer.
