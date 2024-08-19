# Spring Boot JWT Authentication Project

Welcome to the **Spring Boot JWT Authentication Project**. This project demonstrates how to implement authentication in a Spring Boot application using **JSON Web Tokens (JWT)**. The application features essential components for managing authentication, including custom entry points, token filters, and login request/response handling.

## 📂 Project Structure

- **`AuthEntryPointJwt.java`**: 
  - Handles unauthorized access and sends appropriate error responses.
  
- **`AuthTokenFilter.java`**: 
  - Filters incoming HTTP requests, validating JWT tokens and setting the authentication context.

- **`LoginRequest.java`**: 
  - Encapsulates the login request data, typically including username and password.

- **`LoginResponse.java`**: 
  - Defines the response sent back to the client upon successful authentication, usually containing the JWT token and user details.

## 🚀 Getting Started

### Prerequisites

Before running this project, ensure you have the following installed:

- [Java JDK 8 or higher](https://www.oracle.com/java/technologies/javase-downloads.html)
- [Maven 3.6.3 or higher](https://maven.apache.org/download.cgi)

### Running the Project

Follow these steps to clone and run the project:

1. **Clone the repository**:
   ```bash
   git clone git@github.com:yzarzar/SpringSecurityDemo.git
   cd SpringSecurityDemo
