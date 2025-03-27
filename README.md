# **Database Solution for Cell Technologies**

## **Project Overview**

In this project, I acted as the team lead and spearheaded the design and development of a normalized relational database for Cell Technologies, a company specializing in building custom PCs. The project aimed to solve the business problem of efficiently managing customer data, PC component specifications, and order information. The solution was designed to optimize internal operations and improve customer experiences by providing easy access to product details and streamlining the process of building custom PCs.

The database system allows both internal users (employees) and external users (customers) to interact with the data. It helps employees efficiently track customer orders, manage product specifications, and generate reports. Customers can make informed decisions by selecting appropriate PC components based on detailed product specifications, leading to a more seamless and user-friendly experience.

## **Business Problem**

Cell Technologies needed a robust database solution to catalog customer orders and maintain detailed information about each component they offer. The existing system lacked the ability to scale and support growing data needs, making it difficult to manage and analyze customer orders and product specifications efficiently.

The key challenges included:
- Storing detailed specifications for each PC component (CPU, GPU, RAM, etc.).
- Managing customer information, including contact details and order history.
- Ensuring easy access to relevant data for both internal employees and external customers.
- Streamlining the process of custom PC builds to enhance operational efficiency.

## **Objective**

The goal of this project was to design a normalized relational database that supports:
- Efficient data storage and retrieval.
- Detailed specifications for each product component (e.g., CPU brands, GPU prices, RAM sizes).
- A seamless order management system for customers and employees.
- A user-friendly interface for decision-making, allowing customers to configure their PCs based on available parts.

The database was designed to improve decision-making, support strategic business decisions, and streamline internal operations, enhancing the overall customer experience.

## **Solution Approach**

To tackle these challenges, we designed a normalized relational database using a combination of best practices in database design. The database schema was divided into several related tables to ensure data integrity and minimize redundancy. Some of the key tables in the database include:

- **Customers Table**: Stores essential customer information such as names, contact details, and order history.
- **Orders Table**: Tracks orders placed by customers, including order dates, totals, and shipping details.
- **Products Table**: Contains information on PC components (CPU, GPU, RAM, etc.) including specifications such as brand, price, and model.
- **Order Details Table**: Maps products to specific orders, allowing for a many-to-many relationship between orders and products.
- **Categories Table**: Organizes products into categories (e.g., CPUs, GPUs, RAM, Storage) for easy navigation and searchability.

The database schema was normalized to the third normal form (3NF) to reduce redundancy, improve data integrity, and ensure that the database is scalable as Cell Technologies grows.

## **Tools and Technologies Used**

- **Microsoft SQL Server**: Used as the relational database management system (RDBMS) to create and manage the database. SQL Server provided robust tools for querying, indexing, and optimizing data retrieval.
- **Docker**: Used to containerize the database environment, allowing for easier deployment and management of the database system in different environments (e.g., development, testing, production).
- **Kaggle**: Utilized datasets from Kaggle to simulate customer and product data for testing the functionality of the database.
- **Excel**: Used for data analysis and to perform preliminary data validation before importing it into the database.
- **Draw.io**: Used to create the Entity-Relationship (ER) Diagram to visually represent the relationships between entities and design the database schema.
  
## **Key Features and Deliverables**

- **Normalized Database Design**: The database was normalized to eliminate redundancy and ensure data integrity. All tables were designed according to third normal form (3NF).
- **Entity-Relationship Diagram (ERD)**: The database schema was visualized using an ERD created with Draw.io, showing the relationships between entities such as customers, orders, and products.
- **SQL Queries**: Developed SQL queries for data retrieval, insertion, and updates, ensuring that all database operations are efficient and optimized.
- **Data Import and Management**: Implemented a process for importing data from external sources (e.g., CSV files) into the database using SQL Server Integration Services (SSIS).
- **Reporting Capabilities**: The database supports the generation of various reports, such as sales reports, product availability, and customer order history.

## **Challenges Faced and Solutions**

- **Data Import and Transformation**: One of the challenges faced was importing and transforming raw data from various sources into the normalized database format. We used SQL Server Integration Services (SSIS) and data cleansing techniques to ensure the data was properly formatted.
- **Maintaining Data Integrity**: Ensuring referential integrity and avoiding data anomalies was a key concern. By enforcing foreign key constraints and using transactions, we ensured that all relationships between tables were properly maintained.
- **Optimization for Performance**: As the database grew, query performance became a concern. We optimized SQL queries using indexing and query optimization techniques to ensure fast retrieval times even with large datasets.

## **Conclusion**

The successful implementation of the normalized relational database for Cell Technologies provides a scalable solution for managing customer data, orders, and product specifications. The database streamlines the process of creating custom PCs, improves decision-making, and enhances the customer experience. The project demonstrated the power of relational databases in solving real-world business problems and highlighted the importance of effective database design and optimization.

As team lead, I coordinated efforts, oversaw the design and development processes, and ensured the successful completion of the project, which was instrumental in improving Cell Technologies' operational efficiency.
