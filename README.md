Service: Order  
Port: 8082  
Endpoints:
- /orders
    - GET: Get all orders
    - POST: Add one order
- /productId
    - GET: Get product by id

Calls remote microservice CatalogService on port 8081<br/>


```
Browser / Swagger
|
+--> Catalog Service :8081 --> temporary Product List<>
|
+--> Order Service :8082 --> temporary Order List<>
Separate GitHub repositories
Separate open pull requests
```
Lab 1: branch lab1-order-boundaries

Lab 2: branch lab2-jpa-h2  

Lab 3: branch lab3-openfeign-config

Lab 4: branch lab4-sql-fiddle-lab

## SQL and Normalisation Lab
Final db<>fiddle session: https://dbfiddle.uk/R4AouMQ7  
The fiddle contains the completed SQL queries and the written answers as SQL comments.
