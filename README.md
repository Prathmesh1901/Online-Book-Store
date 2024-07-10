
# Online Bookstore

## About

A user-friendly Online Bookstore project in which users can log in or register, view the available books, select books along with their quantity, and buy them. Users can also get payment receipts after successful payment. The project can also be used by the administrator, who can add new books, remove books, increase and decrease the quantity of books, change the price of the books, as well as maintain the selling history of books.

## Purpose

This website is built for the following purposes:
- Selling books online.
- Maintaining books selling history.
- Adding and managing books.
- User-friendly interface.
- Implementation of HTTP Servlets in Java.

This is a mini-project developed using Java, JDBC, and Servlets.

## Admin Features

Admins have the following access:
- Add new books.
- View available books.
- Remove books.
- Increase the quantity of books.

## User Features

Users have the following access:
- Create a new account or register.
- Log in.
- View available books.
- Select books to buy.
- Select book quantities.
- Buy books.
- Get payment receipts.

## Technologies Used

### Front-End Development
- HTML
- CSS
- JavaScript
- Bootstrap

### Back-End Development
- Java [JDK 8+]
- JDBC
- Servlet

### Database
- MySQL

## Installation

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/online-bookstore.git
   cd online-bookstore
   ```

2. **Set up the database:**
   - Install MySQL and create a database named `bookstore`.
   - Import the `schema.sql` file to set up the necessary tables.

3. **Configure application properties:**
   - Update the `src/main/resources/application.properties` file with your MySQL database credentials.
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/bookstore
     spring.datasource.username=root
     spring.datasource.password=yourpassword
     ```

4. **Build the project:**
   ```bash
   mvn clean install
   ```

5. **Run the application:**
   ```bash
   mvn spring-boot:run
   ```

6. **Access the application:**
   - Open your browser and go to `http://localhost:8080`.

## Usage

### User Actions
- **Register/Login:** Access the registration and login pages from the homepage.
- **Browse Books:** Navigate to the "Books" section to view available books.
- **Add to Cart:** Select books and add them to your cart.
- **Checkout:** Proceed to checkout to complete the purchase and receive a receipt.

### Admin Actions
- **Admin Login:** Access the admin panel via the admin login page.
- **Manage Inventory:** Add, update, or remove books from the inventory.
- **View Sales History:** Check the sales history for book transactions.

## Contributing

Contributions are welcome! Please fork the repository and create a pull request with your changes.

## License

This project is licensed under the MIT License.
