# Code Realm

Code Realm is an AI-powered collaborative coding web app that enables developers to generate coding sessions, collaborate in real-time, and have voice communication with team members. With an integrated AI assistant based on Grok, Code Realm simplifies collaborative coding and enhances the development experience.

## Features

- **Session Generation**: Create and manage coding sessions with server names and passwords.
- **Real-time Collaboration**: Collaborate with team members in real-time using a built-in code editor.
- **Voice Communication**: Integrated voice communication to discuss and collaborate effectively.
- **AI Assistant**: Grok-based AI chatbot that assists with code explanations and debugging.
- **Session Management**: View and manage session members.
- **Subscription & Login**: Users can sign up and log in to access features securely.

## Tech Stack

- **Frontend**: Next.js, Tailwind CSS, JavaScript
- **Backend**: Spring Boot, MongoDB, Spring Security
- **Real-time Communication**: Fluvio for stateful dataflow
- **AI Integration**: Grok-based AI assistant for code explanations

## Installation

### Prerequisites

- Java 17 or higher
- MongoDB
- Node.js and npm

### Backend Setup

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/code-realm.git
   cd code-realm/backend
   ```

2. Install dependencies:

   ```bash
   ./mvnw clean install
   ```

3. Configure MongoDB connection in `application.properties`:

   ```properties
   spring.data.mongodb.uri=mongodb://localhost:27017/code-realm
   ```

4. Run the Spring Boot application:

   ```bash
   ./mvnw spring-boot:run
   ```

   The backend will now be running on `http://localhost:8080`.

### Frontend Setup

1. Navigate to the frontend directory:

   ```bash
   cd ../frontend
   ```

2. Install dependencies:

   ```bash
   npm install
   ```

3. Run the Next.js application:

   ```bash
   npm run dev
   ```

   The frontend will be available at `http://localhost:3000`.

## Usage

1. Open the frontend in your browser at `http://localhost:3000`.
2. Log in or sign up to start using Code Realm.
3. Create a new coding session by generating a server name and password.
4. Invite team members to the session and collaborate in real-time using the code editor.
5. Use the Grok-based AI assistant to get code explanations and suggestions.
6. Use the voice communication feature to discuss code and resolve issues.

## License

This project is licensed under the MIT License - see the [LICENSE](LICENSE) file for details.
