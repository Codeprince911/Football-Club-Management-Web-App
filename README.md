# RP United Football Club Management System

A comprehensive web application for managing RP United Football Club operations, including user management, product sales, event organization, and payment processing.
![Screenshot 2025-01-21 162143](https://github.com/user-attachments/assets/9c5d882e-d599-4000-9b66-02bd6f40e1c2)

## Features

### User Management
- User registration and authentication
- JWT-based security
- Role-based access control
- Profile management

### Product Management
- Product catalog
- Inventory tracking
- Product categories
- Stock management

### Order Management
- Shopping cart functionality
- Order processing
- Order history
- Payment integration

### Event Management
- Event creation and scheduling
- Participant registration
- Capacity management
- Event reminders

### Payment Integration
- Secure payment processing with Stripe
- Multiple payment methods
- Refund handling
- Payment webhooks

### Email Notifications
- Welcome emails
- Order confirmations
- Event registrations
- Payment receipts
- Automated reminders

### Monitoring and Security
- Health checks
- Performance metrics
- Comprehensive logging
- Error tracking
- API documentation

## Technology Stack

- Backend: Spring Boot 3.x
- Security: Spring Security with JWT
- Database: MySQL
- Payment: Stripe API
- Documentation: OpenAPI/Swagger
- Monitoring: Spring Actuator
- Email: Spring Mail with Gmail SMTP
- Scheduling: Spring Scheduler
- Caching: Caffeine

## Setup Instructions

1. Clone the repository:
   ```bash
   git clone https://github.com/your-username/rp-united.git
   ```

2. Configure environment variables:
   ```properties
   MYSQL_HOST=your-mysql-host
   MYSQL_PORT=3306
   MYSQL_DATABASE=rpunited
   MYSQL_USERNAME=your-username
   MYSQL_PASSWORD=your-password
   
   JWT_SECRET=your-jwt-secret
   
   MAIL_USERNAME=your-email@gmail.com
   MAIL_PASSWORD=your-email-password
   
   STRIPE_API_KEY=your-stripe-api-key
   STRIPE_WEBHOOK_SECRET=your-stripe-webhook-secret
   ```

3. Build the project:
   ```bash
   cd rp-united
   ./mvnw clean install
   ```

4. Run the application:
   ```bash
   ./mvnw spring-boot:run
   ```

## API Documentation

Access the API documentation at:
- Swagger UI: `http://localhost:8080/swagger-ui.html`
- OpenAPI Spec: `http://localhost:8080/api-docs`

## Monitoring

Access monitoring endpoints at:
- Health Check: `http://localhost:8080/actuator/health`
- Metrics: `http://localhost:8080/actuator/metrics`
- Info: `http://localhost:8080/actuator/info`

## Development Guidelines

1. Code Style
   - Follow Java code conventions
   - Use meaningful variable and method names
   - Add appropriate comments and documentation

2. Testing
   - Write unit tests for new features
   - Ensure test coverage for critical components
   - Run integration tests before deployment

3. Security
   - Never commit sensitive credentials
   - Use environment variables for secrets
   - Follow security best practices

4. Error Handling
   - Use appropriate exception types
   - Provide meaningful error messages
   - Log errors with proper context

## Contributing

1. Fork the repository
2. Create a feature branch
3. Commit your changes
4. Push to the branch
5. Create a Pull Request

## License

This project is proprietary and confidential. All rights reserved by RP United Football Club.
