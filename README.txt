This Database stores a list of customers and their transactions, bearing in mind that each customer has a unique id. The transaction could be a withdrawal, deposit or check balance. The customer id field in the transaction table references the id field in the customer table. This creates a relationship between between the two  tables. 

SELECT * FROM customer_table;

SELECT * FROM transactions;

INSERT INTO customer_table VALUES (NULL, 12, "Chukwurah", "Royalty", 004255520, "Anambra", "07037635071", "chukwuroyalty@yahoo.com");

SELECT first_name, last_name FROM customer_table WHERE id = 1;

DELETE FROM customer_table WHERE id = 3;