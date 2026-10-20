# Core Banking Service RESTful CLI


A web-based Java banking application integrating secure, session-based authentication built alongside strict validation algorithms to securely process transactions and store user account details.


## <-- Key Security Features -->

**Session-Based Authentication**: Secure access control mechanism that manages user state and sessions to safely authorize account actions. Built-in validation algorithms strictly verify usernames and account details before persisting data. Comprehensive command-line interface allows authenticated users to securely deposit, withdraw, and transfer funds between accounts.
  

## Frontend & Client-Side:


*   **HTML**: -- Structural layout for the banking application's web interface.
  
*   **CSS**: -- Custom styles applied to ensure a functional and readable user experience.
  
*   **JavaScript**: -- Dynamic interactions and client-side handling for account management.
  


## Backend Core & Frameworks:


*   **Java**: -- Core object-oriented programming language driving the banking logic.
  
*   **MVC Architecture**: -- Model-View-Controller pattern separating business logic, data models, and the CLI layer.
  


## Security & Data Layer:


*   **SQL Database**: -- Relational database system used to securely store and persist user credentials and balances.
  
*   **Connection Factory**: -- Structural design pattern used to establish and manage active SQL database connections.
  
*   **MongoDB**: -- NoSQL database component integrated alongside SQL for alternative data handling.
  
*   **XML Schemas**: -- Structure and validation definitions used for data modeling and exchange formats.

  

## Dev Tools, Testing & Logging:


*   **Gradle Wrapper**: -- Build automation tool ensuring consistent project compilation and dependency resolution.
  
*   **Unit Testing**: -- Target test suites verifying the integrity of data access objects (DAO) and database connections.
  
*   **Apache Log4j**: -- Logging framework utilized for system activity tracking, monitoring transactions, and debugging.
