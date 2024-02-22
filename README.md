# JokesApp

## Overview

This Jokes Application offers a platform for users to explore, share, and enjoy humor through a collection of jokes. Featuring secure user authentication, it allows users to browse, search, edit, and delete jokes, in addition to providing functionalities for user registration and login. Developed with .NET and utilizing ORM for database interactions, it aims to deliver a seamless and engaging experience.

## Features

- **Browse and Search Jokes**: Access and find jokes easily through a user-friendly interface.
- **User Authentication**: Secure login and registration system to ensure a safe user environment.
- **Content Management**: Authenticated users can create, edit, and delete their jokes, promoting a dynamic and interactive platform.
- **Responsive Design**: Optimized for various devices and screen sizes, ensuring a consistent user experience.

  
## Security and User Management

Our Jokes Application is equipped with a secure login and registration system, ensuring that only authenticated users can contribute to the platform. Here are the key aspects:

- **Secure User Authentication**: We prioritize the security of user data and sessions. Our system is designed to safeguard against unauthorized access, providing a safe environment for all users.
- **Content Management Privileges**: Registered and logged-in users have the exclusive ability to create, edit, and delete jokes. This approach maintains the integrity of our content and fosters a trusted community of users.

## Prerequisites

Ensure the following are installed before setup:
- .NET SDK (version as per project requirements)
- A SQL database (e.g., SQL Server, MySQL)
- An IDE (e.g., Visual Studio, Visual Studio Code)

## Installation

1. **Clone the Repository**
   ```bash
   git clone https://yourrepositorylink.com/project.git

2. **Navigate to Project Directory**

   cd project-directory

3. **Install Dependencies**

   dotnet restore

4. **Database Setup**

   Apply migrations to set up your database:

   dotnet ef database update

5. **Configure Application**

   Update appsettings.json with your database connection string and other settings.

6. **Run the Application**

   Start the app using:

   dotnet run

Visit http://localhost:port as shown in your terminal to access the application.





