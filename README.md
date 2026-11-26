# Netflix Data Analysis | dbt & Snowflake

An end-to-end Netflix data transformation and analytics project built using **dbt, Snowflake, and SQL**.

## Project Overview

This project focuses on transforming raw movie and rating datasets into structured analytical models using dbt and Snowflake.

## Tech Stack

- **Data Warehouse:** Snowflake
- **Transformation:** dbt
- **Query Language:** SQL
- **Version Control:** Git & GitHub

## Project Structure

```text
netflix/
├── analyses/
├── macros/
├── models/
│   ├── staging/
│   ├── dim/
│   ├── fct/
│   ├── mart/
│   ├── schema.yml
│   └── sources.yml
├── seeds/
├── snapshots/
├── tests/
├── dbt_project.yml
├── packages.yml
└── README.md
```

## Key Features

- Data staging and transformation
- Dimension and fact table modeling
- Movie and user analytics
- Movie genre and tag analysis
- Data quality testing
- Custom dbt macros
- Snapshot-based historical tracking
- Analytical SQL queries

## dbt Commands

```bash
dbt deps
dbt debug
dbt run
dbt test
dbt docs generate
dbt docs serve
```

## Project Objective

To demonstrate practical skills in SQL, data modeling, ETL/ELT workflows, data transformation, testing, and analytics engineering using dbt and Snowflake.

## Author

**Sourabh Kamble**

[GitHub](https://github.com/sourabh-k7)