Features
User Context Provider:

Centralized state management for user data.
Provides a shared users state to all components.
Allows adding new users dynamically.
Role-Based User Management:

Includes users with predefined roles: Admin, Super User, and User.
Custom Hook:

Provides an easy way to access user data using useUsers().
Code Overview
1. UserContext
A Context to manage and provide user data across the application.
2. UserProvider Component
Wraps the application and shares users state and addUser function with its children.
3. useUsers Hook
Simplifies access to UserContext.


ID's and Password to access the different roles and designations:-
{ id: "admin1", password: "admin123", role: "Admin" },
{ id: "superuser1", password: "superuser123", role: "Super User" },
{ id: "user1", password: "user123", role: "User" },
