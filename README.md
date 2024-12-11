# KIIT-Bus-Tracking-App
This app addresses the challenges of campus transportation by offering a centralized solution that simplifies user experiences and enhances engagement, enabling students, faculty, and staff to efficiently track, book, and utilize transport services. By implementing this application, we aim to overcome the limitations of traditional methods, such as reliance on manual scheduling, fragmented communication channels, or inefficient tracking systems, which often result in delays, confusion, and dissatisfaction. Furthermore, a well-designed mobile and web-based platform empowers users by providing real-time bus tracking, route optimization, and notifications for schedule updates.
# Functional Requirements
1. User Registration and Authentication:
Secure account creation and login for students, faculty, staff, and drivers.
Role-based access control for users (e.g., Rider, Driver, Admin).
2. Bus Tracking:
Real-time bus tracking for both Riders and Drivers.
Integration with Google Maps API to display routes and locations.
3. Route and Schedule Management:
Riders can search for available buses, routes, and timings.
Admins can create, modify, and assign schedules for efficient operations.
4. Notifications:
Push notifications for bus arrival updates, schedule changes, and delays.
Feedback System:
Users can submit feedback about the service for improvements.
Admin Dashboard:
A centralized platform to manage schedules, monitor buses, and view
system analytics.
7. Location Services:
Use of WebSockets to ensure continuous updates for bus
locations.
# Non-functional Requirements
1. Usability:
Intuitive interfaces for both Riders and Drivers to enhance user
experience.
Accessible design for ease of use across different devices.
2. Performance:
Fast response times, especially for location updates and schedule
retrieval.
Optimized data flow even during high user activity.
3. Security:
Strong data encryption for user accounts and bus location
information.
Robust authentication mechanisms to prevent unauthorized
access.
4. Scalability:
Support for an increasing number of users, buses, and routes
as the university expands.
5. Reliability:
Minimal downtime with fault-tolerant systems for high
availability.
Load balancers to manage traffic efficiently.
6.Integration:
Seamless integration with Google Maps API and
Firebase for real-time data handling.
7. Privacy:
Protection of user location data and adherence to data
privacy regulations.
# Project Planning
1. Requirement Gathering and Analysis:
Identifying user needs and core functionalities, such as real-time tracking,
schedule management, and notification systems.
Analyzing technical requirements for location services, authentication, and
data handling.
2. System Design:
Designing the application architecture, including database schemas, UI/UX
wireframes, and workflow diagrams.
Planning API interactions for real-time updates and route optimization.
3. Prototype Development:
Building a functional prototype to test core features like map integration,
live tracking, and role-based user access.
Collecting feedback for iterative improvements.
4. Development and Testing:
Completing frontend and backend development using React Native,
Node.js, MySQL, and Firebase AI.
Conducting rigorous testing of the app’s functionalities, such as real-time
location updates and user authentication.
5. Deployment:
Deploying the final version of the app and admin dashboard on cloud
platforms with scalability options.
Ensuring system reliability through load testing and redundancy planning.
# System Features
1. User Interfaces (Mobile and Web):
Driver Interface: Provides tools for route navigation, bus status updates, and receiving notifications from the admin.
Rider Interface: Allows users to search routes, track buses in real time, and receive
schedule updates.
2. Admin Dashboard:
A centralized interface for managing schedules, monitoring buses, and viewing usage analytics.
3. Backend Development:
API Development: RESTful APIs manage data flow between the frontend and
backend, handling user authentication, route data, and notifications.
Database Integration: MySQL is used to store user profiles, bus schedules, and feedback securely.
4. Real-Time Bus Tracking:
Integration with Google Maps API to provide live tracking of buses and display optimal routes.
WebSocket-based communication ensures continuous updates for location services.
5. Notification System:
Push notifications alert users about bus arrivals, delays, or route changes.
6. User Authentication:
JWT Authentication: JSON Web Tokens (JWT) provide secure, sessionless login for all users, ensuring that only authorized individuals access the system.
7. Scalability and Security:
Use of load balancers to handle increasing traffic.
Data encryption and secure server configurations protect user and location data.
