## Introduction
This document provides a comprehensive design for a software system CozyCove. The purpose of this document is to outline the design principles, and components of the system to guide the development process.

## System Overview
The system is a web-based platform that allows users to list, discover, and book accommodations. It includes features for property owners to manage listings, for travelers to search and book properties, and for both parties to manage reservations and payments.

## Requirements
### Functional Requirements
- User Registration and Authentication
- Property Listing Management
- Search and Filter Properties
- Booking Management
- Payment Processing
- Reviews and Ratings

### Non-Functional Requirements
- Scalability
- Security
- Performance
- Usability

## Design Principles
The design of this system follows several key principles from SWEBOK to ensure high quality and maintainability.

### Abstraction
Components are designed to expose only necessary functionalities, hiding implementation details to reduce complexity.

### Modularity
The system is divided into distinct modules, each responsible for a specific functionality, promoting separation of concerns.

### Encapsulation
Each module's internal state is protected from unauthorized access, ensuring data integrity and reducing the risk of bugs.

### Separation of Concerns
Different aspects of the system, such as user interface, business logic, and data access, are separated to simplify development and maintenance.

### Reusability
Components are designed to be reusable across different parts of the system, reducing redundancy and improving efficiency.

## Component Design
### User Module
- Registration
- Authentication
- Profile Management

### Property Module
- Listing Creation
- Listing Management
- Search and Filters

### Booking Module
- Availability Checking
- Reservation Management
- Payment Processing

### Review Module
- Rating System
- Review Management

### Admin Module
- User Management
- Listing Approval
- System Monitoring

## Activity Diagrams
### Activity Diagram for Guest Registration and ID Verification
![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team02/assets/87032748/985f600d-5ded-4f11-af55-b30ce5158478)

### Activity Diagram for Property Search and Listing
![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team02/assets/87032748/b9e4101a-6170-48f1-93a7-949e54b1b0ee)

![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team02/assets/87032748/7850323e-05fc-4509-aa66-9bc5727668df)

### Activity Diagram for Guest-Host Communication
![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team02/assets/87032748/d36aa4f6-d113-4ad9-ad4a-4386054560e4)

### Activity Diagram for Customer Support Booking and Property Access
![image](https://github.com/SWENGG4Y2024/SWENGG4Y2024Team02/assets/87032748/39f93d92-c3cf-42f2-ae05-0dfac02e21f2)






## Database Design
The database design follows a relational model with the following key entities:
- **Users**: Stores user information and credentials.
- **Properties**: Contains property details and listings.
- **Bookings**: Manages reservation data.
- **Payments**: Tracks payment transactions.
- **Reviews**: Records user reviews and ratings.
  
## Conclusion
This design document outlines the  components, and principles for developing a software system CozyCove. Following these guidelines will help ensure a robust, scalable, and secure application.
