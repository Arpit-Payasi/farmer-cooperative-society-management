# Farmer Cooperative Crop Supply System (FCCSS)

## Overview

The Farmer Cooperative Crop Supply System (FCCSS) is a PostgreSQL-based database management system designed to streamline the operations of agricultural cooperative societies. The system manages the complete crop supply chain, starting from farmer registration and crop procurement to inventory management, logistics, buyer orders, and subsidy disbursement.

## Features

- Farmer registration and profile management
- Cooperative society membership management
- Crop lot registration and procurement tracking
- Quality inspection and crop grading
- Farmer payment processing
- Warehouse and inventory management
- Buyer order management
- Transportation and logistics tracking
- Crop pricing management
- Government subsidy disbursement tracking

## Database Modules

- Farmer Management
- Cooperative Society Management
- Crop Procurement
- Quality Check and Grading
- Farmer Payments
- Warehouse Management
- Inventory Tracking
- Buyer Order Processing
- Transportation and Logistics
- Crop Pricing
- Subsidy Management

## Database Design

The system consists of 15+ interconnected entities connected using primary and foreign key constraints to maintain data integrity and consistency across the agricultural supply chain.

Key entities include:

- Farmer
- Cooperative Society
- Farmer Membership
- Crop Lot
- Procurement
- Quality Check
- Farmer Payment
- Warehouse
- Inventory
- Logistics Partner
- Vehicle
- Buyer
- Order Header
- Order Item
- Transport Job
- Crop Price
- Subsidy Scheme
- Subsidy Disbursement

## Tech Stack

- PostgreSQL
- SQL
- Database Normalization
- Relational Database Design

## Repository Structure

```text
farmer-cooperative-crop-supply-system/
│
├── README.md
├── schema.sql
├── sample_data.sql
├── queries.sql
└── database_design.pdf
```

## Setup Instructions

1. Clone the repository:

```bash
git clone https://github.com/Arpit-Payasi/farmer-cooperative-crop-supply-system.git
```

2. Open PostgreSQL and create the database:

```sql
CREATE DATABASE fccss;
```

3. Run the schema script:

```bash
psql -d fccss -f schema.sql
```

4. Insert sample data:

```bash
psql -d fccss -f sample_data.sql
```

5. Execute the query file to test the database functionality:

```bash
psql -d fccss -f queries.sql
```

## Learning Outcomes

- Relational Database Design
- Database Normalization
- SQL Query Optimization
- Entity Relationship Modeling
- Constraint Management
- Supply Chain Data Modeling

## Contributors

- Arpit Payasi
