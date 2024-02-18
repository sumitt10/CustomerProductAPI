# CustomerProductAPI

**Description:**
CustomerProductAPI is a Spring Boot application developed for EffiGO's task. It provides a RESTful API for joining two tables and fetching details using a native query. The application is designed to handle customer and product data stored in a PostgreSQL database.

**Dependencies:**
- Spring Web: Simplifies the development of RESTful web services.
- PostgreSQL Driver: Enables connectivity to a PostgreSQL database.
- Lombok: Reduces boilerplate code by providing annotations for common tasks.
- Spring DevTools: Facilitates fast application restarts during development.

**Usage:**

1. **Database Setup:**
   - Ensure PostgreSQL is installed and running.
   - Configure the database connection in the `application.properties` or `application.yml` file.

2. **Run the Application:**
   - Start the Spring Boot application.

3. **API Endpoints:**
   - `/PlaceOrder`: To placing order for customers.
   - `/FindAllOrders`: Retrieving all orders.
   - `/GetJoinInformation`: Execute a native query to join customer and product tables and fetch details.

**Example Request (curl):**
```bash
http://localhost:8080/
