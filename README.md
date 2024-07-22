# Entrepreneur Support System

Entrepreneur Support System is a Java application designed to facilitate the interaction between startups and investors. The project aims to streamline the process of fundraising for startups while providing investors with opportunities to discover and support promising ventures.

## Features

### User Authentication
The application allows users to sign up and log in as either a startup or an investor. User authentication ensures secure access to the platform. Password encryption has been used for more secure password storage.

### Startup Features
- Startups can log in, view all investors, raise fund requests, and withdraw pending requests.
- The system provides a menu-driven interface for startups to navigate through these functionalities for a hassle-free interaction with investors.

### Investor Features
- Investors can log in, view all pending fund requests from startups, view startups within their domain, and choose to fund specific startups.
- The system matches startups with investors based on industry preferences.

### Authentic Information
Both startups and investors can provide detailed information during the sign-up process, including contact details, industry preferences, founding members, and startup descriptions. This information is stored securely in the database.

### Matching Algorithm
The application incorporates a matching algorithm to suggest potential matches between startups and investors based on industry alignment and funding requirements. This feature enhances the efficiency of fundraising efforts and increases the likelihood of successful partnerships.

### Action Monitoring
The system logs user actions such as login, signup, and fund requests, providing a comprehensive history of user interactions. This feature enables administrators to track user activities and monitor system usage.

### Information Retention
The system has a feature to store all past running requests that are now withdrawn, using triggers in the database.

## Technologies Used

- Java
- MySQL
- JDBC (Java Database Connectivity)

## Installation

1. Clone the repository:

2. Set up MySQL database:
- Create a database and configure the JDBC connection in your application properties.

3. Compile and run the application:
- Use your preferred IDE or command line tools to compile and run the Java application.

## Contributors

- Sanjana Inapokolla
- Prajakta Jadhav
- Ishani Deshmukh


