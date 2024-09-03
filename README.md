E-Commerce Website

Overview

This project is a full-stack e-commerce application, developed with a *Java Spring Boot* backend and a *React.js* frontend. The application provides a comprehensive platform for users to browse products, add items to their cart, and proceed to checkout.

Features
 Backend (Java Spring Boot)
- *RESTful API*: Implements a robust API to handle requests from the frontend, including product listings, user authentication, and order processing.
- *Maven-Based*: Utilizes Maven for dependency management and build automation.
- *Database Integration*: Designed to interact with a relational database (likely MySQL or PostgreSQL) for storing user information, product details, and orders.
- *Unit Testing*: Includes unit tests to ensure the reliability and functionality of core features.

 Frontend (React.js)
- *Modern UI*: Built using React.js for a dynamic and responsive user interface.
- *State Management*: Uses React Context for global state management, ensuring a seamless user experience across different pages.
- *API Integration*: Handles communication with the backend through Axios, managing authentication, product data, and order submissions.
- *Vite.js*: Leveraged Vite for fast development and optimized production builds.

 Installation

 Backend
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
   

 Frontend
1. Navigate to the frontend directory:
   bash
   cd ecom-frontend-5-main
   
2. Install dependencies:
   bash
   npm install
   
3. Start the development server:
   bash
   npm run dev


### overview of the contents of both the backend and frontend parts of your project:

### Backend :
- *pom.xml*: Maven configuration file, indicating it's a Maven-based Java project.
- *mvnw, mvnw.cmd*: Maven Wrapper scripts to run Maven without needing a pre-installed version.
- *.mvn*: Maven-related configuration.
- *.gitignore*: Specifies files and directories that should be ignored by Git.
- *HELP.md*: Typically a help or guide document for the project.
- *src*: Contains the source code, likely with the main Java application and resources.
- *target*: Output directory where the compiled code and packages are stored.
- *.idea*: IntelliJ IDEA project files.

### Frontend:
- *.eslintrc.cjs*: Configuration file for ESLint, a JavaScript linting tool.
- *.gitignore*: Specifies files and directories that should be ignored by Git.
- *README.md*: Documentation file for the frontend.
- *index.html*: The main HTML file for the frontend.
- *package.json*: Lists dependencies and scripts for the frontend project.
- *package-lock.json*: Ensures consistency of installed npm packages.
- *public*: Likely contains static assets like images, fonts, etc.
- *src*: Contains the source code for the frontend.
- *vite.config.js*: Configuration file for Vite, a frontend build tool.
