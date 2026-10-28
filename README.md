Sizwe Coffee — Entity-Relationship Diagram (ERD)

Project Overview

This project focuses on designing and reviewing a database structure for Sizwe Coffee using an Entity-Relationship Diagram (ERD). The diagram represents the main entities, their attributes, and the relationships required to support business operations.

Database Entities

The diagram includes the following entities:

* Customer — stores customer contact and registration information.
* Product — stores product details, prices, stock quantities, categories, and supplier information.
* Order — records order dates, statuses, and total amounts.
* Payment — records payment dates, methods, statuses, and amounts paid.
* Delivery — stores delivery dates, statuses, courier names, and tracking numbers.
* Supplier — stores supplier contact details and addresses.

Project Objectives

* Identify primary keys (PKs) and foreign keys (FKs).
* Examine relationships and cardinality between database entities.
* Identify missing attributes and possible database design errors.
* Evaluate whether the database structure supports accurate and consistent data.
* Recommend corrections to improve data integrity and reliability.

Error Identification

The diagram was reviewed for potential issues involving key assignments, missing foreign key attributes, relationship connectors, and cardinality.

Examples of areas requiring validation include the identification of primary keys, the relationship between customers and orders, and the links between orders, payments, deliveries, products, and suppliers.

These observations should be verified against the SQL schema and assignment requirements before corrections are finalised.

Tools Used

* diagrams.net (draw.io)
* SQL
* DuckDB
* GitHub

Conclusion

This project demonstrates the importance of database modelling and relationship validation. Correctly defined primary keys, foreign keys, and relationships help maintain referential integrity and support reliable business reporting.

Disclaimer

This diagram is part of a learning and portfolio project. Proposed corrections should be validated against the underlying database schema and business requirements.
