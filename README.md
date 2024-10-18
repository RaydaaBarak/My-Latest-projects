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

## Quality Assurance Documentation (QAD)
### Quality Management Plan:
Functionality: payment , Login , Search
1- payment
GOAL: to handle payment by allowing the user to choose a payment method and enter relevant information.
OUTCOME: Bill Confirmation: The user receives a confirmation of the bill regardless of the payment method.
Target Objective:prompt the user for their preferred payment method, either Apple Pay or credit card, and process the payment accordingly by collecting the necessary details 
Performance Measures/Data Source(s)/ Frequency/Responsible Person: The system should accurately capture and process the payment method that selected by user. Data Validation: Ensuring valid inputs for payment details like: card name and number
Responsible Person: Developer,System Admin.

2- Login: 
GOAL: provide a secure and reliable user authentication mechanism that allows users to log in to the "Cure Well" pharmacy app using their unique username and password.
OUTCOME: 
•Users are successfully authenticated with their credentials.
•User data (username and password) is stored
Target Objective:
-Ensure a 100% successful login process for registered users with correct credentials.
-Implement security mechanisms to prevent unauthorized access.
Performance Measures/Data Source(s)/ Frequency/Responsible Person:
Successful Logins:
•	Measure: Number of successful logins per day.
•	Data Source: Application logs, authentication success records.
•	Frequency: Daily monitoring to track usage and any login failures.
Responsible Person:
•	Lead Developer
•	Security Specialist 
•	System Administrator 

3-  Search
GOAL: it allows users to find medications by entering search queries, and displaying relevant results from a pre-defined list of medications.
OUTCOME:Result 100% correct products after searching  & Sort product correctly
Target Objective: Helping the user to find the medicine he wants through search.
Performance Measures/Data Source(s)/ Frequency/Responsible Person:Speed of returning search results. Search Accuracy: Correctness of matching results. Data Source(s): Hardcoded list of medicines. Frequency Executed in real-time with each user query. 
Responsible Person:Developers responsible for implementation and maintenance.

## Test Specifications:
Test Name: Credit Card Payment Processing. 
Description: 
This test ensures that when the user selects "Credit Card" as the payment method, the system correctly prompts for and accepts credit card details (cardholder name and card number) and displays the appropriate billing information. 
Requirement:
 The system must prompt the user to enter their card name and card number, and then display both the card name and number as part of the bill output. 
Prerequisites:
 The PaymentSystem class and its payment() method are implemented.
 The Scanner object is initialized for input. 
The terminal or console is available to input text and view the output.
Setup: 
1. Initialize a Scanner object for user input. 
2. Call the payment() method to initiate the payment process


Test Name: User Login Processing
Description:
This test ensures that when the user is prompted to log in, the system correctly prompts for and accepts a username and password, stores these credentials, and validates successful user login.
Requirement:
The system must prompt the user to enter their username and password. The credentials should be stored in an array of User objects, and the username and password should be retrievable for future use.
Prerequisites:
•	The Login class and its main() method are implemented.
•	The User class is implemented with setUserName() and setPassword() methods.
•	The Scanner object is initialized for input.
•	The terminal or console is available to input the username and password and view the results.
Setup:
Initialize a Scanner object for user input.
Create an array of User objects.


Test Name: Search Functionality 
Test Description:
 Verify that the search feature correctly identifies and returns matching medications based on user input. 
Requirement(s):
 Users can search for medications by name.
 The search is case-insensitive and returns accurate results. 
Prerequisites:
 The application must be running. 
The selected medication list must be pre-configured
Setup: 
1-Ensure the application is running. 
2-Initialize the predefined list of medicines


## Known Issues:
- Compatibility is currently limited to iOS devices only (no Android support).
- Users may experience delays in pharmacist consultations during non-peak hours due to staffing.

## Contributors
- Layan Alharbi - Developer
- Ghaya Alhazmi - Developer
- Raydaa Almabadi - Quality Assurance Lead

