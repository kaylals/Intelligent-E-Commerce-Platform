# Intelligent-E-Commerce-Platform


## Overview
The **Intelligent E-Commerce Platform** is a full-stack web application that combines the power of **Spring Boot** on the backend and **Angular** on the frontend to create a modern e-commerce platform. This project provides a scalable and modular solution for managing products, orders, customers, and payments, while also offering intelligent recommendations based on user behavior.

## Features
- **Product Management**: Create, update, and delete products with categories and pricing information.
- **Customer Management**: Handle customer registration, authentication, and profiles.
- **Shopping Cart**: Add products to the cart, manage quantities, and calculate totals.
- **Order Processing**: Checkout and order processing with payment integration.
- **Recommendations**: Personalized product recommendations based on purchase history and browsing behavior.
- **Admin Dashboard**: Manage products, categories, and orders with a user-friendly interface.
  
## Tech Stack
### Backend (Spring Boot):
- **Spring Boot**: Backend framework for developing RESTful APIs.
- **Spring Data JPA**: ORM tool for interacting with the database.
- **MySQL/PostgreSQL**: Relational database for storing application data.
- **Spring Security**: For authentication and authorization.
- **JWT (JSON Web Token)**: Token-based authentication.
  
### Frontend (Angular):
- **Angular**: Frontend framework for building dynamic and responsive user interfaces.
- **Bootstrap**: UI framework for responsive design.
- **Angular Router**: For navigation between different views.


### DevOps:
- **Git****: Version control.
- **Maven**: Dependency management and build automation.

## Installation

### Prerequisites
- **Node.js** (for Angular frontend)
- **Java 11+** (for Spring Boot backend)
- **MySQL/PostgreSQL** (or any other relational database)
- **Maven** (for backend dependency management)

### Backend (Spring Boot)

1. Clone the repository:
   ```bash
   git clone https://github.com/kaylals/Intelligent-E-Commerce-Platform.git
   cd Intelligent-E-Commerce-Platform/backend
   ```

2. Configure the database in `application.properties` (or `application.yml`):
   ```properties
   spring.datasource.url=jdbc:mysql://localhost:3306/ecommerce_db
   spring.datasource.username=yourUsername
   spring.datasource.password=yourPassword
   ```

3. Build and run the Spring Boot application:
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

### Frontend (Angular)

1. Navigate to the frontend directory:
   ```bash
   cd ../frontend
   ```

2. Install dependencies:
   ```bash
   npm install
   ```

3. Start the Angular development server:
   ```bash
   ng serve
   ```

4. Open your browser and go to `http://localhost:4200`.


## Usage
- **Admin**: Log in with admin credentials to manage products and orders.
- **User**: Register as a customer, browse products, add items to the cart, and place orders.
- **Recommendations**: Check out personalized product suggestions based on your shopping habits.

## Contributing
Feel free to open issues or submit pull requests for any improvements or bug fixes. Contributions are always welcome!
