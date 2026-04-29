# StockFlow Backend Case Study

This repository contains my solution for the StockFlow backend case study.

## About the Case Study
The task was to understand and solve problems related to an inventory management system used by businesses. The system handles products, warehouses, stock levels, and suppliers.

The case study is divided into three parts:
1. Code review and debugging  
2. Database design  
3. API implementation  

---

## What I have done

### Part 1: Code Review
I identified problems in the given code such as:
- Missing input validation  
- No check for duplicate SKU  
- Improper database transaction handling  
- Incorrect design for handling multiple warehouses  

I explained the impact of these issues and suggested how to fix them using proper validation and transaction handling.

---

### Part 2: Database Design
I designed a simple database structure with the following main tables:
- Companies  
- Warehouses  
- Products  
- Inventory  
- Suppliers  

I separated inventory from products so that one product can exist in multiple warehouses. I also listed some questions to clarify missing requirements.

---

### Part 3: API Implementation
I implemented a low stock alert API using Java and Spring Boot concepts.

The API:
- Finds products with low stock  
- Checks recent sales activity  
- Includes supplier details for restocking  

I also handled basic edge cases and made a few assumptions where requirements were not clearly defined.

---

## Tech Stack (Based on My Knowledge)
- Java  
- Spring Boot  
- MySQL (If Database)

---

## Author
JYOTHISWAR YALLA
