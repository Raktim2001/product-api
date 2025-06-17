# Product API (Spring Boot + H2)

This is a simple Spring Boot project that demonstrates basic **CRUD operations** (Create, Read, Update, Delete) using a RESTful API. It uses an **in-memory H2 database** for quick setup and testing.

##  Features

- `GET /products` – Retrieve all products  
- `GET /products/{id}` – Retrieve a specific product by ID  
- `POST /products` – Add a new product  
- `PUT /products/{id}` – Update an existing product  
- `DELETE /products/{id}` – Delete a product  

##  Tech Stack

- Java  
- Spring Boot  
- Spring Data JPA  
- H2 Database (in-memory)  

## ▶ Running the Project

1. Open the project in your IDE (IntelliJ, Eclipse, etc.)  
2. Run `ProductApiApplication.java`  
3. Access the API using Postman or your browser at:  
   `http://localhost:8080/products`  
4. H2 Console is available at:  
   `http://localhost:8080/h2-console`  
   - JDBC URL: `jdbc:h2:mem:productsdb`  
   - Username: `sa`  
   - Password: *(leave blank)*  

##  Example JSON for POST / PUT

```json
{
  "name": "Laptop",
  "price": 999.99
}
