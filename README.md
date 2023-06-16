# E-commerce_Reccomendation_Program
This program is a Python script that anaylyses cutomer transaction history and generates item recommendations based on the history.

The script reads 'history.txt' to extract information about the number of customers, items and transactions. It reads 'queries.txt.' to obtain a list of items in the current shopping cart. The program uses vectors to store items, and uses cosine to calculate average angles between items - the two products with the smallest difference in average angle are likely to be most similar and hence recommended to a consumer.

Feel free to download my Python script to give it a go, as well as the Zip file included (it has 3 different sets of data, so you can see how the program operates with varying data types, length and figures).
