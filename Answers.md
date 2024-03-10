1."Product" table has a column named "category_id" which is a foreign key referencing the primary key "id" of the "Product_category" table.There's a one-to-many relationship between product_category  table and product table, meaning one product_category can have multiple products, but each product belongs to only one category.

2. Define a Foreign Key Constraint: In the "Product" table, add a column named 'category' which will reference the 'id' column in the "product_category" table.
   Enforce Referential Integrity: Set up a foreign key constraint on the 'category' column in the "Product" table, ensuring that it references an existing id in the "product_category" table.
