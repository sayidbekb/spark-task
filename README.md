# Spark + Pagila PostgreSQL Analysis

This project demonstrates how to use **Apache Spark** with the **Pagila PostgreSQL database** using JDBC.

---

## Prerequisites

- Docker & Docker Compose  
- Python 3.x  
- PySpark  
- PostgreSQL JDBC driver (`postgresql-42.6.0.jar`)  
- Git  

---

## Commands to run
    docker-compose up -d
---
    docker exec -it pagila psql -U postgres -d pagila
    \l       # List databases
    \dt      # List tables