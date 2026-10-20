# Core Banking Service RESTful CLI

A secure, web-based Java banking application that integrates session-based authentication and strict validation algorithms to safely process financial transactions and persist user account details.

## 🚀 Key Features

* **Session-Based Authentication:** Manages explicit user states and active sessions to safely authorize sensitive account actions.
* **Strict Data Validation:** Utilizes robust server-side algorithms to verify user credentials and transaction parameters before persistence.
* **Comprehensive CLI Layer:** Enables authenticated users to securely deposit, withdraw, and transfer funds via an interactive command-line interface.
* **Transactional Security:** Features an isolated Data Access Object (DAO) architecture to safely manipulate accounts without data leaks.

## 🛠️ Tech Stack

### Frontend & Client-Side
* **HTML5 / CSS3:** Accessible, structural layout styled for a clean and readable user experience.
* **JavaScript (ES6):** Dynamic client-side interactions and asynchronous state management.

### Backend Core & Architecture

| Technology | Role |
| :--- | :--- |
| **Java** | Core OOP language driving business and transaction logic. |
| **MVC Architecture** | Design pattern cleanly separating models, views, and the CLI execution layer. |
| **XML Schemas** | Structuring and validation definitions for secure data modeling and exchange. |

### Security, Data & Devops
* **PostgreSQL:** Relational database management system storing credentials and account ledger balances.
* **Connection Factory Pattern:** Design pattern managing and pooling active SQL database connections efficiently.
* **Gradle Wrapper:** Build automation tool guaranteeing deterministic compilations and dependency trees.
* **Apache Log4j:** Enterprise-grade logging for transaction auditing, threat monitoring, and system debugging.

## 🧪 Testing

The repository ships with isolated unit testing suites to ensure system integrity:
* **DAO Verification:** Automated tests validating CRUD operations against account objects.
* **Connection Stability:** Unit tests enforcing that the database connection factory cleanly signs and terminates active pools.

To run the test suite locally:
```bash
./gradlew test
```

## ⚙️ Getting Started

### Prerequisites
* **Java Development Kit (JDK):** Version 11 or higher.
* **PostgreSQL:** An active instance with a configured database schema.

### Installation & Run
1. **Clone the repository:**
   ```bash
   git clone https://github.com
   cd core-banking-service
   ```
2. **Build the application:**
   ```bash
   ./gradlew build
   ```
3. **Execute the application:**
   ```bash
   ./gradlew bootRun
   ```

## 📜 License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
