
This phase defines the functional requirements, non-functional requirements, and technical requirements of the AI StudyBuddy project.

1. Functional Requirements

The system should provide the following functions:

User Authentication

- User registration and login.
- JWT-based authentication.
- Secure password storage using bcrypt.
- Role-based access for Students and Administrators.

Study Material Management

- Upload study materials.
- Store study materials securely.
- Retrieve and manage previously uploaded materials.

AI Summary Generation

- Process uploaded study content.
- Generate concise summaries using the Google Gemini AI API.

AI Flashcard Generation

- Generate flashcards from study materials.
- Store generated flashcards for future revision.

AI Quiz Generation

- Generate multiple-choice questions from study materials.
- Allow students to use quizzes for self-assessment.

Personalized Study Plan

- Generate study plans according to the student's learning goals, available study time, and examination timeline.
- Store generated study plans for future reference.

Administration

- Manage registered users.
- Monitor application activity.
- Monitor AI service utilization.
- Maintain system integrity.

2. Non-Functional Requirements

Security

- Protect user accounts using JWT authentication.
- Encrypt passwords using bcrypt.
- Restrict administrative functions using role-based access control.

Performance

- Process API requests efficiently.
- Provide timely AI-generated responses.
- Support efficient database operations.

Scalability

- Use a modular backend architecture.
- Allow additional AI-powered features to be integrated in the future.

Maintainability

- Separate authentication, business logic, database operations, and AI services into modules.
- Follow a structured RESTful API architecture.

Reliability

- Maintain secure communication between frontend and backend services.
- Ensure reliable database connectivity.

3. Project Requirements

Software Requirements

- Windows 10/11, macOS, or Linux
- Node.js v16 or above
- npm v8 or above
- Express.js
- MongoDB
- Mongoose
- Google Gemini AI API
- Postman or Thunder Client
- Visual Studio Code

Hardware Requirements

- Intel Core i5 8th Generation or above / AMD Ryzen 5 or equivalent
- Minimum 8 GB RAM
- 1 GB available storage

Technologies

- Frontend: React.js
- Backend: Node.js and Express.js
- Database: MongoDB
- AI: Google Gemini API
- Authentication: JWT
- Password Security: bcrypt

Expected Result

The requirements defined in this phase provide the foundation for designing and developing a secure, scalable, and AI-powered learning platform for students.
