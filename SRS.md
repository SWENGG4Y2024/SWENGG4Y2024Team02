# Software Requirements Specification (SRS) for CozyCove

## Introduction
The Software Requirements Specification (SRS) for CozyCove outlines the functional and non-functional requirements for developing the platform. This document provides a comprehensive guide to the features, functionalities, and technical specifications necessary to meet the user requirements outlined in the URD.

## Description
CozyCove is a platform designed to connect guests with hosts offering properties for short-term stays. The platform facilitates property searching, booking, listing management, user profile management, secure payments, reviews, and communication between users. It aims to provide a seamless and secure user experience for both guests and hosts.

## Product Requirements

### Requirements for Guests

#### 1. Registration and ID Verification
- **Account Creation**: Guests must have the capability to create an account using their email address, phone number, or social media accounts.
- **ID Verification**: Guests are required to complete an ID verification process by providing a valid government-issued ID and a recent photograph.
- **Email and Phone Verification**: Verification links or codes should be sent to the guest's email and phone number to ensure authenticity.

#### 2. User Profile
- **Profile Information**: Guests must be given the ability to create and edit their profile, including personal information such as name, age, gender, and bio.
- **Preferences**: Guests should be allowed to set preferences for notifications, communication, and search filters.

#### 3. Property Search and Listing
- **Search Filters**: Guests should have access to property search filters such as location, price range, amenities, property type, and dates.
- **Map View**: Guests must be able to view available properties on a map.
- **Save Favorites**: Guests should be provided with the functionality to save properties to a favorites list for future reference.

#### 4. Property Booking
- **Booking Process**: Guests should have the capability to book a property directly from the listing page, specifying the check-in and check-out dates.
- **Booking Confirmation**: Guests must receive a booking confirmation via email and SMS.
- **Reservation Management**: Guests should have access to view, manage, and cancel their reservations from their profile.

#### 5. Secure Payments
- **Payment Methods**: The platform must support multiple payment methods, including credit/debit cards, PayPal, and other local payment options.
- **Payment Security**: Payments must be processed through a secure payment gateway to ensure the safety of financial information.
- **Payment Receipts**: Guests should receive an electronic receipt for each transaction.

#### 6. Cancel Bookings and Refunds
- **Cancellation Policies**: The platform must display the cancellation policies for each property.
- **Cancellation Process**: Guests should be able to cancel bookings directly from their reservation management page.
- **Refund Process**: Refunds should be processed according to the property's cancellation policy and refunded to the original payment method.

#### 7. Reviews and Ratings
- **Eligibility**: Only guests who have completed their stay should have the ability to leave reviews and ratings.
- **Review Content**: Guests should be allowed to provide a rating (1-5 stars) and write a detailed review of their stay. All ratings and reviews will be publicly available.

#### 8. Communication
- **Communication with the Host**: Guests should have access to an in-platform messaging system to communicate with hosts.
- **Communication with Customer Support**: Guests should have easy access to customer support through multiple channels, including in-app messaging, email, and phone.

### Requirements for Hosts

#### 9. Registration and ID Verification
- **Account Creation**: Hosts must be provided with the capability to create an account using their email address, phone number, or social media accounts.
- **ID Verification**: Hosts are required to complete an ID verification process by providing a valid government-issued ID and a recent photograph.
- **Email and Phone Verification**: Verification links or codes should be sent to the host's email and phone number to ensure authenticity.

#### 10. User Profile
- **Profile Information**: Hosts must be given the ability to create and edit their profile, including personal information such as name, age, gender, and bio.
- **Profile Picture**: Hosts should be allowed to upload a clear profile picture.
- **Verification Badges**: Hosts should be able to display verification badges once ID verification is completed.

#### 11. Managing Listings
- **Create Listings**: Hosts should be able to create new property listings, including details such as photos, description, amenities, house rules, pricing, and availability calendar.
- **Edit Listings**: Hosts must be able to edit existing listings to update information, photos, and availability.
- **Listing Status**: Hosts should be able to change the status of their listings (e.g., active, inactive, temporarily unavailable).
- **Pricing Management**: Hosts should have the ability to set and adjust pricing, including seasonal pricing and discounts.

#### 12. Booking Management
- **Booking Requests**: Hosts should receive and manage booking requests, with the option to accept or decline.
- **Booking Calendar**: Hosts must have access to a calendar view to manage booking dates and availability.
- **Instant Booking**: Hosts should have the option to enable or disable instant booking.
- **Booking Confirmation**: Hosts must receive booking confirmations via email and SMS.

#### 13. Cancel Bookings
- **Cancellation Policies**: The platform must support multiple cancellation policies (e.g., flexible, moderate, strict) that hosts can choose from.
- **Cancellation Process**: Hosts should be able to cancel bookings directly from their booking management page.
- **Penalties and Consequences**: Hosts should be informed of any penalties or consequences associated with cancellations.

#### 14. Communication
- **Communication with the Guest**: Hosts should have access to an in-platform messaging system to communicate with guests.
- **Communication with Customer Support**: Hosts should have easy access to customer support through multiple channels, including in-app messaging, email, and phone.

### Requirements for Customer Support

#### 15. Call and Chat Support
- **Multichannel Support**: Customer support agents must be able to handle inquiries through both phone calls and live chat.
- **Chat Interface**: The chat interface should allow customer support agents to manage multiple conversations simultaneously.
- **Call Management**: The call system should include features such as call routing, call hold, call transfer, and call recording for quality assurance.
- **Response Time**: Customer support agents should adhere to specified response times for both chat and call support to ensure timely assistance.
- **Communication History**: Customer support agents should have access to the complete communication history with a user for context in ongoing support interactions.

#### 16. Access to Booking Details
- **Booking Overview**: Customer support agents must have access to a comprehensive overview of all bookings, including current, past, and future reservations.
- **Booking Details**: Detailed information for each booking should include guest and host information, booking dates, property details, payment status, and any special requests or notes.
- **Booking Management**: Customer support agents should have the ability to modify bookings, cancel reservations, and process refunds according to the platform's policies.
- **Issue Resolution**: Customer support agents should be able to log and track issues related to bookings, ensuring they are resolved efficiently.

#### 17. Access to Property Details
- **Property Listings**: Customer support agents must have access to detailed information about all properties listed on the platform.
- **Property Details**: Information should include property descriptions, amenities, house rules, photos, pricing, availability, and host contact information.
- **Property Management**: Customer support agents should have the ability to update property details, manage listing status, and assist hosts with listing issues.
- **Verification Status**: Customer support agents should be able to view and manage the verification status of properties and hosts.

#### 18. ID Verification of Guests and Hosts
- **Verification Management**: Customer support agents should have access to verify the authenticity of IDs uploaded by the Guests and Hosts and manage the verification process.
- **Security and Privacy**: Customer support agents should have access to user information in a secure manner, ensuring the privacy and security of all data.

## User Interface
### Guest Interface
- **Homepage**: Search bar, featured properties, and user login/signup options.
- **Search Results**: List view and map view with filters.
- **Property Listing Page**: Property details, photos, amenities, reviews, booking options.
- **User Profile**: Editable profile details, preferences, reservation history.
- **Messaging System**: Chat interface for guest-host communication.

### Host Interface
- **Dashboard**: Overview of listings, bookings, and messages.
- **Listing Management**: Create/edit listings, manage availability and pricing.
- **Booking Management**: Calendar view, booking requests, booking history.
- **Profile Management**: Editable profile details, verification status.

### Customer Support Interface
- **Support Dashboard**: Overview of active inquiries and communication history.
- **Chat Interface**: Manage multiple chat sessions.
- **Call System**: Call routing and management features.
- **Booking and Property Access**: Detailed access to booking and property information.
- **Issue Tracking**: Log and track support issues.

## Technical Specifications
### Platform Architecture
- **Frontend**: React.js for the user interface.
- **Backend**: Node.js with Express.js for the server-side logic.
- **Database**: MongoDB for data storage.
- **Authentication**: OAuth2 for secure authentication and authorization.
- **Payment Gateway**: Integration with Stripe and PayPal for secure payments.
- **Hosting**: AWS for scalable hosting solutions.

### Security Measures
- **Data Encryption**: Use SSL/TLS for data transmission.
- **Secure Authentication**: Implement two-factor authentication (2FA).
- **User Data Privacy**: Comply with GDPR and other relevant data protection regulations.
- **Regular Audits**: Conduct regular security audits and vulnerability assessments.

### Performance Requirements
- **Scalability**: The platform must handle high traffic volumes efficiently.
- **Load Balancing**: Implement load balancing to distribute traffic evenly.
- **Response Time**: Ensure quick response times for user interactions.
- **Uptime**: Aim for 99.9% uptime with minimal downtime.

## Additional Requirements
- **Localization**: Support multiple languages and currencies.
- **Accessibility**: Ensure the platform is accessible to users with disabilities.
- **Mobile Compatibility**: Provide a responsive design for mobile devices.
- **Backup and Recovery**: Implement regular data backups and disaster recovery plans.

## Requirements Traceability Matrix

The Requirements Traceability Matrix (RTM) maps the User Requirements Document (URD) to the Software Requirements Specification (SRS) to ensure that all user requirements are addressed in the software requirements. This matrix helps in validating that the software meets the needs of the users and ensures completeness and correctness in requirements management.

| Requirement ID | User Requirement (URD)                                         | Software Requirement (SRS)                                                          | Comments/Status       |
|----------------|-----------------------------------------------------------------|-------------------------------------------------------------------------------------|-----------------------|
| URD-001        | Guests must be able to create an account                        | The system shall allow users to register via email, phone, or social media accounts. | Implemented           |
| URD-002        | Guests must complete an ID verification                         | The system shall provide an ID verification process requiring a government-issued ID and a photo. | In Progress           |
| URD-003        | Guests must be able to search for properties using various filters | The system shall provide search filters for location, price range, amenities, property type, and dates. | Implemented           |
| URD-004        | Guests must be able to view available properties on a map       | The system shall display available properties on a map.                             | Pending               |
| URD-005        | Guests must be able to save properties to a favorites list      | The system shall allow users to save properties to a favorites list.                | Implemented           |
| URD-006        | Guests must be able to book a property                          | The system shall allow users to book a property directly from the listing page, specifying check-in and check-out dates. | Implemented           |
| URD-007        | Guests must receive booking confirmation via email and SMS      | The system shall send booking confirmations via email and SMS.                      | In Progress           |
| URD-008        | Guests must be able to view, manage, and cancel reservations    | The system shall allow users to view, manage, and cancel their reservations from their profile. | Implemented           |
| URD-009        | Guests must be able to make secure payments                     | The system shall support multiple payment methods and process payments through a secure gateway. | Implemented           |
| URD-010        | Guests must receive an electronic receipt for each transaction  | The system shall send an electronic receipt for each transaction.                   | Pending               |
| URD-011        | Guests must be able to cancel bookings and receive refunds      | The system shall allow users to cancel bookings and process refunds according to the property's cancellation policy. | In Progress           |
| URD-012        | Guests must be able to leave reviews and ratings                | The system shall allow users to leave reviews and ratings for properties they have stayed at. | Implemented           |
| URD-013        | Guests must be able to communicate with hosts                   | The system shall provide an in-platform messaging system for guest-host communication. | Implemented           |
| URD-014        | Guests must have access to customer support                     | The system shall provide customer support through in-app messaging, email, and phone. | Implemented           |
| URD-015        | Hosts must be able to create and manage property listings       | The system shall allow hosts to create and manage property listings, including photos, descriptions, and availability. | Implemented           |
| URD-016        | Hosts must be able to manage booking requests                   | The system shall allow hosts to receive, accept, or decline booking requests.       | Implemented           |
| URD-017        | Hosts must have access to a booking calendar                    | The system shall provide a calendar view for hosts to manage booking dates and availability. | In Progress           |
| URD-018        | Hosts must be able to communicate with guests                   | The system shall provide an in-platform messaging system for host-guest communication. | Implemented           |
| URD-019        | Hosts must have access to customer support                      | The system shall provide customer support for hosts through in-app messaging, email, and phone. | Implemented           |
| URD-020        | Customer support agents must have access to booking details     | The system shall provide customer support agents with access to detailed booking information for assistance. | In Progress           |
| URD-021        | Customer support agents must have access to property details    | The system shall provide customer support agents with access to detailed property information for assistance. | In Progress           |
| URD-022        | Customer support agents must manage ID verification             | The system shall provide customer support agents with tools to verify the authenticity of IDs uploaded by guests and hosts. | Pending               |
| URD-023        | Customer support agents must ensure security and privacy        | The system shall ensure customer support agents access user information securely, maintaining data privacy and security. | Pending               |



## Appendices
### Glossary
- **Guest**: A user looking to book a property.
- **Host**: A user listing a property for rent.
- **Booking**: A confirmed reservation of a property.
- **ID Verification**: The process of validating a user's identity using government-issued ID.

### References
- User Requirements Document (URD) for CozyCove
- GDPR Compliance Guidelines
- Payment Card Industry Data Security Standard (PCI DSS)
- [SWEBOK Guide](https://www.computer.org/web/swebok)
- [IEEE Standard 829-2008](https://standards.ieee.org/standard/829-2008.html)
