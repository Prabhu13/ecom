# Smart Retail RFID

## Description

Smart Retail RFID is a full-stack application that leverages RFID technology for efficient inventory management and an enhanced customer shopping experience. Retailers can track products in real-time, manage stock efficiently, and provide customers with up-to-date product information via a simple, user-friendly interface. This application is built to run locally, without relying on cloud services, making it ideal for offline use in retail stores.

## Features

- **Real-time Inventory Management**: Track products and manage stock levels in real-time using RFID technology
- **Product Information Display**: View product details and pricing, ensuring that customers always have the most up-to-date information
- **Seamless User Experience**: User-friendly interface built for both retail employees and customers to interact with
- **Offline Capabilities**: Runs locally on your machine without the need for cloud services, making it suitable for stores without internet connectivity
- **Basic Inventory Tracking**: Simple system for adding, updating, and removing items from the inventory

## Tech Stack

### Frontend
- React.js
- React Router
- HTML5, CSS3, Bootstrap for styling

### Backend
- Java (Spring Boot)
- Hibernate (for database connection)

### Database
- MySQL (locally hosted)

### RFID
- RFID-based scanning system for inventory management

### Version Control
- Git and GitHub for version control

### Tools
- IntelliJ IDEA (Java development)
- VS Code (for React development)
- MySQL Workbench (for database management)

## Installation

### Prerequisites

1. **Java**: Make sure you have Java 8 or higher installed
2. **Node.js**: Install Node.js (which includes npm) for React development
3. **MySQL**: Ensure MySQL is installed and running on your machine
4. **Git**: Install Git for version control

### Steps

1. **Clone the repository:**
   ```bash
   git clone https://github.com/yourusername/smart-retail-rfid.git
   cd smart-retail-rfid
   ```

2. **Backend (Java Spring Boot Setup):**
   - Navigate to the backend folder:
     ```bash
     cd backend
     ```
   - Ensure your MySQL database is up and running. Create a database named `retail_rfid`
   - Update the database connection details in `application.properties` in the backend project:
     ```properties
     spring.datasource.url=jdbc:mysql://localhost:3306/retail_rfid
     spring.datasource.username=root
     spring.datasource.password=yourpassword
     ```
   - Build and run the Spring Boot application:
     ```bash
     mvn clean install
     mvn spring-boot:run
     ```

3. **Frontend (React Setup):**
   - Navigate to the frontend folder:
     ```bash
     cd frontend
     ```
   - Install the dependencies:
     ```bash
     npm install
     ```
   - Start the React development server:
     ```bash
     npm start
     ```

4. **Run the application:**
   - Once both the backend and frontend are running, you should be able to access the application by navigating to http://localhost:3000 in your browser

## Usage

- **Retailers**: Use the application to scan RFID tags, add or remove products from the inventory, and view real-time stock levels
- **Customers**: Scan product RFID tags to view product details, availability, and pricing information on the app

## License

This project is licensed under the MIT License - see the LICENSE file for details.

## Contact

For further queries or contributions, feel free to reach out via GitHub Issues.
