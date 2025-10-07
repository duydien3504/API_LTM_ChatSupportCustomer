# ChatHTKH - Real-time Chat Application

A real-time chat application built with Spring Boot, WebSocket, and React, featuring JWT authentication and SQL Server database.

## 🚀 Features

- **Real-time Messaging**: Instant message delivery using WebSocket
- **User Authentication**: Secure JWT-based authentication
- **RESTful API**: Clean and well-documented API endpoints
- **File Sharing**: Support for file uploads and sharing
- **Responsive Design**: Works on desktop and mobile devices
- **Database**: SQL Server with Hibernate ORM
- **API Documentation**: Interactive API documentation with Swagger UI

## 🛠️ Tech Stack

- **Backend**:
  - Java 21
  - Spring Boot 3.2.0
  - Spring Security with JWT
  - Spring WebSocket
  - Spring Data JPA
  - MapStruct for DTO mapping
  - Lombok for boilerplate reduction

- **Database**:
  - Microsoft SQL Server 2014+
  - Hibernate ORM
  - HikariCP connection pool

- **Frontend**: (To be implemented)
  - React.js
  - Redux Toolkit
  - Material-UI
  - Axios for HTTP requests

- **Tools**:
  - Maven for dependency management
  - Swagger/OpenAPI for API documentation
  - Git for version control

## 📦 Prerequisites

- Java 21 JDK or later
- Maven 3.6.3 or later
- SQL Server 2014 or later
- Node.js 16+ (for frontend development)

## 🚀 Getting Started

### Backend Setup

1. **Clone the repository**
   ```bash
   git clone https://github.com/yourusername/ChatHTKH.git
   cd ChatHTKH
   ```

2. **Configure the database**
   - Create a new database named `ChatHTKHDb` in your SQL Server
   - Update the database credentials in `src/main/resources/application.properties`

3. **Build and run the application**
   ```bash
   mvn clean install
   mvn spring-boot:run
   ```

4. **Access the application**
   - API Documentation: http://localhost:8080/api/swagger-ui.html
   - API Base URL: http://localhost:8080/api

### Frontend Setup (To be implemented)

## 🔧 Configuration

### Environment Variables

Create a `.env` file in the root directory with the following variables:

```env
# JWT Configuration
JWT_SECRET=your-secret-key
JWT_EXPIRATION=86400000

# Database Configuration
DB_URL=jdbc:sqlserver://localhost:1433;databaseName=ChatHTKHDb
DB_USERNAME=your_username
DB_PASSWORD=your_password
```

## 📚 API Documentation

API documentation is available at `/api/swagger-ui.html` when the application is running.

## 🤝 Contributing

1. Fork the repository
2. Create your feature branch (`git checkout -b feature/AmazingFeature`)
3. Commit your changes (`git commit -m 'Add some AmazingFeature'`)
4. Push to the branch (`git push origin feature/AmazingFeature`)
5. Open a Pull Request

## 📄 License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.

## 🙏 Acknowledgments

- Spring Framework
- React
- And all the amazing open-source libraries used in this project
