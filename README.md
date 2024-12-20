# CS360

Overview
The Inventory Management App was developed as a mobile application designed to simplify inventory tracking for small businesses and personal use. Its primary goal was to address user needs for real-time stock tracking, low inventory notifications, and secure user authentication.



Requirements and Goals
The app was designed to:

Provide a user-friendly interface for managing inventory.
Allow users to add, update, delete, and view inventory items in a grid layout.
Include SMS alerts for low stock notifications.
Offer secure login functionality with persistent data storage.
The app addressed user needs for an intuitive inventory management system by focusing on ease of use, reliability, and real-time feedback.



UI Design and Features
To support user needs, the app included:

Login Screen: For secure authentication and personalized access.
Main Inventory Screen: Displaying inventory items in a grid layout with clear, accessible features.
Add and Update Item Screens: Simplified forms to ensure seamless data input.
Low Stock Notifications: SMS integration to alert users of critical inventory levels.
The UI was designed with user-centered principles, including clean layouts, intuitive navigation, and accessibility considerations. Iterative testing ensured the design was practical and met user expectations.



Development Approach
The app was developed using modular Code Structure: Breaking down the app into smaller, manageable components for scalability.
SQLite Database: For persistent storage of user and inventory data.
Permissions Handling: To ensure SMS integration worked while maintaining app functionality for users who denied permissions.
These strategies ensured the app's maintainability and adaptability for future enhancements.



Testing and Debugging
Testing was conducted using:

Android Emulator: To simulate various device configurations and ensure consistent functionality.
Unit Testing: For individual components such as database operations and SMS functionality.
Iterative Debugging: Using log outputs and exception handling to identify and resolve issues.
This process revealed edge cases where user permissions or incorrect data inputs could disrupt functionality, allowing proactive fixes to enhance user experience.



Challenges and Innovations
One key challenge was integrating SMS functionality while ensuring the app worked for users who declined permissions. Innovatively, the app maintained separate pathways for notifications and core features, ensuring usability regardless of user settings.

Demonstrated Knowledge and Skills
The SQLite Database Integration was a standout component, demonstrating effective use of persistent data storage and CRUD (Create, Read, Update, Delete) operations. Additionally, the app's smooth integration of SMS notifications and user-centered UI design reflects the technical skills and best practices applied throughout development.

