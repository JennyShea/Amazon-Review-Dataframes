# big-data-challenge
Amazon Product Reviews

Use furnished schema to create tables in an RDS database.


Create two separate Google Colab notebooks and extract any two datasets from the list at review dataset, one into each notebook.

![image](https://user-images.githubusercontent.com/86893003/161841764-43649351-de8e-4fb8-98aa-de8618afa101.png)



For each notebook (one dataset per notebook), complete the following:


Count the number of records (rows) in the dataset.
![image](https://user-images.githubusercontent.com/86893003/161842029-86db1c10-5717-4f8f-ac93-e8090f82509c.png)



Transform the dataset to fit in the tables in the schema file.

"customers" Table
customer_id
customer_count
![image](https://user-images.githubusercontent.com/86893003/161842616-1c40046d-50f9-430e-afec-e0e9fdcc3bf7.png)

![image](https://user-images.githubusercontent.com/86893003/161843011-22e5ae9f-de90-49d7-8dc9-44310fd07e96.png)


"products" Table
product_id
product_title
![image](https://user-images.githubusercontent.com/86893003/161843358-2127f2ef-afc0-4de8-8cc1-28c14e77cf62.png)



"review_id_table"
![image](https://user-images.githubusercontent.com/86893003/161845851-0362f986-4ee1-4a2f-9221-737423509534.png)



Load the DataFrames that correspond to tables into an RDS instance.
![image](https://user-images.githubusercontent.com/86893003/161846054-2723ed68-923d-43f8-a185-3fdb08f3fb18.png)


