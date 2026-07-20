Set-Content -Path README.md -Value @"
# Spring Boot CRUD API - Item API

A RESTful CRUD API built using **Spring Boot 4.1.0** and **Java 25** as part of Lab 05.

## Features
- Manages an in-memory repository of items.
- Provides a clean controller architecture at baseline path: \`/api/items\`.
- Validated build lifecycle utilizing Apache Maven.

## Getting Started

### Prerequisites
- Java 25 or higher
- Apache Maven 3.9+

### Running the Application Locally
\`\`\`bash
mvn spring-boot:run
\`\`\`
The application will boot up an embedded Apache Tomcat server listening on port \`8080\`.

### Testing Endpoint Access
\`\`\`powershell
Invoke-RestMethod -Uri http://localhost:8080/api/items
\`\`\`

## License
This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
"@