# Smart E-commerce Database

## Description

The Smart E-commerce Database is a relational database designed to manage the backend data for an e-commerce platform. It provides a structured way to store and retrieve information about products, brands, categories, colors, sizes, and attributes. The database is optimized for scalability and supports features like product variations, images, and custom attributes.

This database can be used as the foundation for building an e-commerce application, enabling efficient management of inventory, product details, and customer interactions.

## Entity-Relationship Diagram (ERD)

Below is the ERD for the Smart E-commerce Database. This diagram visually represents the relationships between the tables in the database:


![MY ERD](<final_database project.png>)

## How to Set Up the Database

1. Install a MySQL server on your local machine or use a cloud-based MySQL service.
2. Open your MySQL client or any database management tool (e.g., MySQL Workbench).
3. Import the `ecommerce.sql` file into your database:
   - Run the following command in your MySQL client:
     ```bash
     mysql -u [username] -p [database_name] < ecommerce.sql
     ```
     Replace `[username]` with your MySQL username and `[database_name]` with the name of the database you want to create.
4. Verify that the tables have been created successfully by running:
   ```sql
   SHOW TABLES;