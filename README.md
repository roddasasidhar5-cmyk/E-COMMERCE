# E-COMMERCE
📖 Table of Contents
Project Overview
Core Functionalities
User Module
Administrator Module
Technology Stack
Implementation Guide
Prerequisites
Installation Procedure
Operational Guidelines
Potential Future Enhancements
Contact Information
🌟 Project Overview
The E-PRODUCTS Shopping project is a complete, full-stack e-commerce web application, engineered to serve as a practical demonstration of contemporary web development principles. The platform features a robust backend responsible for the management of product inventory, user accounts, and order processing. This is complemented by a dynamic, single-page application on the frontend, which is designed to deliver an intuitive and fluid user interface.

The application is architected to be highly navigable, facilitating a straightforward process for customers to browse products, manage a persistent shopping cart, and finalize orders. Concurrently, it provides a comprehensive dashboard for administrators to oversee the store's inventory, customer base, and sales activities.

✨ Core Functionalities
The application is bifurcated into two primary modules: a User-facing storefront and an Administrator dashboard.

User Module
Authentication: Provides a secure system for user registration and authentication.
Product Catalog: Displays all available products in a structured, grid-based layout for clear presentation.
Detailed Product View: Each product has a dedicated page, accessible via a single click, which presents an enlarged image, a comprehensive description, and quantity selection controls.
Shopping Cart Management: Enables users to add or remove items from a persistent shopping cart.
Order Processing: Implements a streamlined, multi-step checkout process, complete with an order summary for user verification.
Payment Mechanism: Utilizes a "Cash on Delivery" model for straightforward payment processing.
Order History: Offers a dedicated section where users can review the history and status of their previous orders.
System Notifications: Employs real-time toast notifications to provide non-intrusive feedback for user actions, such as adding items to the cart or confirming an order.
Account Management: Allows users to view and modify their profile information, including delivery address and contact number.
Session Termination: Facilitates a secure method for users to end their session.
Administrator Module
Administrator Authentication: Implements a distinct and secure login mechanism for administrative personnel.
Centralized Dashboard: Furnishes a unified interface for the comprehensive management of the e-commerce store.
Inventory Control: Grants administrators the ability to add new products to the catalog and remove existing ones.
Customer Relationship Management: Provides a view of all registered users on the platform.
Sales Monitoring: Allows for the review and monitoring of all orders placed by customers.
Session Termination: Provides a secure method for administrators to end their session.
🛠️ Technology Stack
The application is constructed utilizing a modern technology stack for both client-side and server-side development.

Frontend:

HTML5
CSS3
JavaScript (ES6+)
Bootstrap 5: Leveraged for responsive design and the implementation of user interface components.
Font Awesome: Utilized for iconography.
Backend:

Node.js: Serves as the JavaScript runtime environment.
Express.js: Employed as the web application framework for Node.js.
MongoDB: Functions as the NoSQL database for the storage of user, product, and order data.
Mongoose: Utilized as the Object Data Modeling (ODM) library for MongoDB and Node.js.
dotenv: Implemented for the management of environment variables.
CORS: Integrated to enable Cross-Origin Resource Sharing.
🚀 Implementation Guide
To establish a local instance of the application for development or testing purposes, please adhere to the following instructions.

Prerequisites
Ensure that the following software is installed on the local machine:

Node.js (which includes the Node Package Manager, npm)
MongoDB (or an active MongoDB Atlas account)
Installation Procedure
Clone the source repository:

git clone [https://github.com/Immortalcoder0/Major-Project.git](https://github.com/Immortalcoder0/Major-Project.git)
Navigate to the server directory and install the required dependencies:

cd server
npm install
Configure environment variables by creating a .env file within the server directory. This file should contain the MongoDB connection string and the desired port number:

MONGO_URI=your_mongodb_connection_string
PORT=5000
Initiate the backend server:

npm start
Launch the frontend application by opening the index.html file, located in the frontend directory, within a web browser.

Operational Guidelines
Subsequent to the successful initiation of the server and the launching of the frontend, the application may be operated as follows:

User Testing: A new user account may be registered, or alternatively, the default credentials (user@email.com) may be utilized.
Administrator Testing: Access to the administrative dashboard can be obtained by logging in with the default administrator credentials:
Email: admin@email.com
Password: admin123
The administrative interface permits the addition of new products, which can then be viewed and purchased through the user-facing storefront.

Potential Future Enhancements
The following is a list of potential enhancements that could be implemented to extend the functionality of the project:

Integration of a third-party payment gateway, such as Stripe or Razorpay.
Implementation of product search and filtering capabilities.
Introduction of product categorization to improve organization.
Development of an order tracking system for end-users.
Augmentation of security protocols through the replacement of session storage with JSON Web Tokens (JWTs).


Project Repository: https://github.com/Immortalcoder0/Major-Project.git
