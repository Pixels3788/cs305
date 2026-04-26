## CS 305 Module Eight Reflection

##Overview
In this project, I worked on improving the security of a web application for a fictional client, Artemis Financial. The client is a financial consulting company that wanted to secure client data and improve the communication safety in their application.

---

## What I Did
I refactored the application to add SHA-256 checksum verification and enabled HTTPS using SSL. I also generated a self signed certificate using Java Keytool and configured the Spring Boot application to use secure communication on port 8443.

---

## Security Improvements
I improved security by:
- Adding SHA-256 hashing for data integrity
- Enabling HTTPS with SSL/TLS encryption
- Generating and configuring a self signed certificate
- Running OWASP Dependency Check to scan for vulnerabilities

---

## Testing
I tested the application by running the '/hash' endpoint in both HTTP and HTTPS. I confirmed that the checksum was generated correctly and that secure communication worked. I also verified that no new vulnerabilities were introduced using dependency-check.

---

## What I learned
I learned how to secure a web application using HTTPS, implement hashing for data integrity, and how to use security tools like OWASP Dependency Check. This project helped me understand how real world applications are secured.

---

## For Employers
This project shows my ability to work with backend systems, apply secure coding practices, and improve application security using industry tools and standards.
