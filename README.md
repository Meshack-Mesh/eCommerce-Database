# E-commerce Database Design Project

## Project Overview
This project involves the design and implementation of a relational database for an e-commerce platform. It includes the creation of an Entity-Relationship Diagram (ERD) and a fully developed SQL schema to manage product listings, variations, images, brands, categories, attributes, and stock information.

## Files Included
- ecommerce.sql: Contains all SQL statements to create the database tables and relationships.
- ecommerce_erd.png: Visual ERD showing all entities, attributes, primary keys (PK), foreign keys (FK), and relationships.

## Tables Created
1. brand - Manages brand information.
2. product_category - Categorizes products.
3. product - Stores basic product details.
4. color - Manages color options.
5. size_category - Groups size options.
6. size_option- Specific sizes available.
7. product_item - Represents purchasable product variations.
8. product_image - Stores product images.
9. attribute_category - Groups different types of attributes.
10.attribute_type - Defines attribute data types (e.g., text, number).
11.product_attribute - Custom attributes for products.
12.product_variation - Links products to size and color variations.

## Tools Used
- MySQL Workbench (for SQL execution and ERD generation)
- dbdiagram.io (for ERD creation)

## How to Set Up the Database
1. Clone the repository.
2. Open your MySQL Workbench or preferred SQL editor.
3. Run the `ecommerce.sql` script to create all tables.
4. Verify all relationships by inspecting the ERD.


