# Software-Documentation-And-Technical-Writing - Final Documentation.
 ## Project Overview
The Cure Well Pharmacy App is a mobile application designed to simplify pharmaceutical services by providing users access to multiple pharmacies for price comparison, consultations with pharmacists, and online medication ordering with delivery options. This README outlines the core features, installation process, usage guidelines, and relevant details to assist developers, administrators, and users.

## Table of Contents:
### Ch1
- Software Overview and Purpose
 ### Ch2
- Software Features
- Define the Audience
- Documentation Assumptions
- Validate Your Assumptions (Gap Analysis)
- Software Requirements (SRS Doc)
- Build Personas, Stories, and Journey Maps (Persona Doc)
### Ch3
- Software Architecture Design (SDD)
- Documentation Plan (Choose the Right Content Types)
Readme and Troubleshooting (Compulsory)
Choose two additional types as needed.
- Adding visual content
-Conclusion and Future work
- References
- Appendix
- Adding code sample and testing plan (use QAD)
- Adding any that may be useful for readers or others

## Audience:
1.	Customers: General users who access the app to purchase medications, consult with pharmacists, and manage their orders.
2.	Pharmacy Owners and Administrators: Users responsible for managing inventory, tracking orders, and overseeing pharmacy operations within the app.
3.	Pharmacists: Healthcare professionals using the app to provide consultations and manage prescriptions.
4.	Development Team: Developers, system architects, and quality assurance teams who are responsible for creating, testing, and maintaining the app.
5.	Project Managers and Stakeholders: Individuals overseeing the development, ensuring the app meets its goals and requirements.

## Software Features:
•	Price Comparison: Users can browse and compare prices of medications from different pharmacies.

•	Pharmacist Consultations: The app offers real-time chat functionality where users can consult with pharmacists.

•	Order and Delivery Management: Users can place orders, choose delivery options (personal or to friends), and track their deliveries.

•	Secure Payment Processing: The app integrates payment methods like Apple Pay and credit cards, with features like credit card scanning for easy payment.

•	Login and User Authentication: Secure login for users using email and password, with enhanced security for administrators .

•	Product Browsing and Search: Users can search for medications and sort results by various filters like price or pharmacy.

•	Push Notifications: Users receive updates and notifications about their orders or consultations.

•	GPS and Location-based Services: The app uses GPS to help users find nearby pharmacies and ensure accurate delivery addresses.

•	Cart and Checkout: Users can review items in their shopping cart, adjust quantities, and proceed to checkout.

•	User Feedback: Customers can rate the service they received from pharmacists.

## Installation:
### Prerequisites:
- Xcode for iOS development.
- Swift for frontend and Java for backend API development.
- iOS devices for testing.

## Usage Instructions
### Customer Login and Registration:
Login: Users can log in using their registered email and password.
Registration: New users can create accounts by providing their name, email, phone number, and password.
### Searching for Medications:
Use the search bar to enter the medication name or use filters.
Results are displayed based on the predefined list of medications.
### Placing an Order:
Add medications to the cart.
Review and adjust quantities in the shopping cart.
Choose delivery location and payment method.
Confirm the order to receive a delivery estimate and confirmation.
### Consulting a Pharmacist:
From the home page, click on “Consult with a Pharmacist.”
Start a real-time chat to ask questions or seek advice.

## Development
### Code Structure:
Frontend: Built using Swift for iOS app development.
Backend: Java-based APIs handle data retrieval, storage (MySQL, Firebase), and business logic.
Database: Firebase for authentication and MySQL for product, order, and consultation data.
### Development Tools:
Xcode: For iOS development.
GitHub: Version control system.
Firebase: User authentication and real-time database.
MySQL: For backend data management.

## Testing
### Quality Assurance Strategy:
Unit Testing: Test individual components such as payment processing, login authentication, and search functionality.
Integration Testing: Ensure smooth interaction between the frontend (Swift) and backend (Java APIs).
User Acceptance Testing (UAT): Verify that the app meets the user’s functional requirements.
### Sample Tests:
Credit Card Payment Processing: Ensures proper input, validation, and billing for credit card transactions.
User Login: Tests for successful authentication with valid credentials.
Search Functionality: Verifies that search results are accurate based on user input​ز

## Known Issues:
- Compatibility is currently limited to iOS devices only (no Android support).
- Users may experience delays in pharmacist consultations during non-peak hours due to staffing.

## Contributors
- Layan Alharbi - Developer
- Ghaya Alhazmi - Developer
- Raydaa Almabadi - Quality Assurance Lead

