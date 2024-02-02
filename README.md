# Chat-App-RealTimeMessaging

Demo Link : [](https://chat-app-real-time-messaging.vercel.app)
Backend herkou Link : [](https://springboot-chatapp-85133f0b7893.herokuapp.com/)

## A chatapp with realtime messaging. 
- UI is inspried by [WhatsApp web.](https://web.whatsapp.com/) 
 
### Technology Stack:
- Spring Boot & React ensuring a robust and responsive chat application.
- JWT (JSON Web Tokens): Ensuring secure user authentication and authorization.
- MySQL: Handling data storage.
- Tailwind CSS: user interface.
- Redux & React Router DOM: providing seamless navigation.
- Web Socket for Real-time Chat: Enabling users to exchange messages instantly in a live chat environment.
  
### Key Features:

- Profile Update: Allow users to manage and update their profile information.
- Real-time Messaging: Facilitate instant communication between users with real-time chat functionality.
- User Authentication: Implement secure authentication measures ensuring user data protection.
- Chat Creation & Retrieval: Enable users to create new chats and fetch existing conversations.
- User Search.

# Installation : local (Full-Stack Project: Spring Boot + React)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- Java Development Kit (JDK) installed for the backend (Java 8 or later)
- Node.js and npm installed for the frontend
- Git installed for version control
  
## Clone the repository:

   ```bash
   git clone https://github.com/Shravan-Parikh/Chat-App-RealTimeMessaging.git
   ```

### Backend (Spring Boot)

- Navigate to the Springboot-App.
- Intially Build the App and Refactor it everywhere.

Update the Database Connection to your local MySql server.
- create a chatapp database in your MySql
- change the username and password to your local username password in application.properties.

Application.properties
```bash
#db specific properties
spring.datasource.url=jdbc:mysql://localhost:3306/chatapp
spring.datasource.driver-class-name=com.mysql.cj.jdbc.Driver
spring.datasource.username={username}
spring.datasource.password={password}
```
Now Run tha app using your IDE or use

```bash
./mvnw spring-boot:run
```
The backend server will start on http://localhost:5454

If faced with a error using Intellij.
- just update the project JDK to your local Java 17 JDK in Project Configuration.
- Project Configuration is available in the Run options. (In Intellij).

### Frontend (React)

- Navigate to the React-Client.

Install dependencies

```bash
npm install
```

Fix the issues if any

```bash
npm audit fix
```

start the Dev server

```bash
npm start
```
The frontend server will start on http://localhost:3000

## Now you can Test the application locally.




















