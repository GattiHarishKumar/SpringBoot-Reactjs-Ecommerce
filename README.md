# E-Commerce Website

### Overview

This project is a full-stack e-commerce application, developed with a *Java Spring Boot* backend and a *React.js* frontend. The application provides a comprehensive platform for users to browse products, add items to their cart, and proceed to checkout.

# Features
 ### Backend (Java Spring Boot)
- *RESTful API*: Implements a robust API to handle requests from the frontend, including product listings, user authentication, and order processing.
- *Maven-Based*: Utilizes Maven for dependency management and build automation.
- *Database Integration*: Designed to interact with a relational database (likely MySQL or PostgreSQL) for storing user information, product details, and orders.
- *Unit Testing*: Includes unit tests to ensure the reliability and functionality of core features.

 ### Frontend (React.js)
- *Modern UI*: Built using React.js for a dynamic and responsive user interface.
- *State Management*: Uses React Context for global state management, ensuring a seamless user experience across different pages.
- *API Integration*: Handles communication with the backend through Axios, managing authentication, product data, and order submissions.
- *Vite.js*: Leveraged Vite for fast development and optimized production builds.

#  Installation

 ### Backend
1. Clone the repository.
2. Navigate to the backend directory:
   bash
          cd ecom-proj
   
3. Build the project with Maven:
   bash
        ./mvnw clean install
   
4. Run the application:
   bash
        ./mvnw spring-boot:run
   

 ### Frontend
1. Navigate to the frontend directory:
   bash
        cd ecom-frontend-5-main
   
2. Install dependencies:
   bash
        npm install
   
4. Start the development server:
   bash
        npm run dev

