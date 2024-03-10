1. Explain the relationship between the "Product" and "Product_Category" entities from the above diagram?
   
Ans: The Relationship between the "Product" and "Product_Category" entities is a many-to-one relationship, where the 'id' (primary key) of the 'Product_Category' tables servers as 'category_id' (foreign key) in 'Product' table.

3. How could you ensure that each product in the "Product" table has a valid category assigned to it?

Ans: "In the 'Product' table, foreign key constraints are defined on the columns: 'category_id', 'inventory_id', and 'discount_id'. These constraints ensure that each product has a valid category assigned to it via the 'category_id' column, valid inventory information via the 'inventory_id' column, and a valid discount (if applicable) via the 'discount_id' column."
      This statement clarifies that foreign key constraints are applied to ensure data integrity across multiple aspects of a product's information, including its category, inventory details, and associated discounts.
