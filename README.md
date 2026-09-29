
# AI Study Buddy API🤖📚

## Project Overview

**AI Study Buddy** is a web-based learning assistant designed to help students with their academic learning. The system connects students with an Artificial Intelligence system that processes their questions and provides relevant responses.

The application helps students understand difficult concepts, clear their doubts, revise study materials, and organize their learning activities through an interactive and user-friendly platform.

---

## Objectives

* To provide instant academic assistance to students.
* To simplify difficult concepts through easy explanations.
* To support students in self-learning.
* To reduce the time required to search for basic academic information.
* To provide an interactive and user-friendly learning environment.

---

## Key Features

### 1. User Registration

Allows new users to create an account and access the AI Study Buddy application.

### 2. User Login

Allows registered users to securely log in and use the application's learning features.

### 3. Material Upload

Allows students to upload study materials for use in their learning and revision activities.


### 4. Flashcards

Helps students revise important concepts and information using flashcards.

### 5. Quiz

Provides quizzes that help students test their understanding of the learning material.

### 6. Summarization

Helps students obtain summarized study content for easier revision and understanding.

### 7. Study Plan

Helps students organize their learning activities through a structured study plan.

---

## System Architecture

The system consists of the following major components:

* **User Interface**
* **Backend**
* **AI Processing Module**
* **Database**

### Working Flow

```text
Student
   ↓
User Interface
   ↓
Backend
   ↓
AI Processing Module
   ↓
Generated Response
   ↓
User Interface
   ↓
Student
```

The student enters a query through the user interface. The backend receives and processes the request and sends it to the AI processing module. The AI module understands the query and generates an appropriate response, which is then displayed to the student.

---

## Technologies Used

| Component        | Technology                                           |
| ---------------- | ---------------------------------------------------- |
|                               |
| Backend          | Node.js, Express.js                                  |
| AI Technology    | Artificial Intelligence, Natural Language Processing |
| Database         | MongoDB                                              |
| Development Tool | Visual Studio Code                                   |

---

## Main Modules

```text
AI STUDY BUDDY
│
├── User Registration
├── User Login
├── Material Upload
├── Flashcards
├── Quiz
├── Summarization
└── Study Plan
```

---

## Advantages

* Provides quick learning assistance.
* Easy and simple to use.
* Helps students understand difficult topics.
* Supports independent learning.
* Saves time while searching for information.
* Creates an interactive learning experience.

---

## Future Enhancements

The system can be enhanced in the future by adding:

* Voice-based interaction
* Personalized study schedules
* Progress tracking
* Multilingual support
* Subject-wise learning recommendations
* Enhanced quizzes and learning activities

---

## Installation and Setup

### Prerequisites

Make sure the following are installed on your system:

* Node.js
* MongoDB
* Visual Studio Code
* Git

### Steps

1. Clone the project repository.

```bash
git clone <repository-url>
```

2. Navigate to the project directory.

```bash
cd AI-Study-Buddy
```

3. Install the required dependencies.

```bash
npm install
```

4. Configure the required environment variables.

5. Start the application.

```bash
npm start
```

6. Open the application in your web browser.

---

## Project Structure

```text
AI-Study-Buddy/
│
├── frontend/
│   ├── html/
│   ├── css/
│   └── javascript/
│
├── backend/
│   ├── routes/
│   ├── controllers/
│   ├── models/
│   └── server.js
│
├── database/
│
├── README.md
└── package.json
```

*Adjust the folder names above if your actual project structure is different.*

---

## Testing

The application can be tested for:

* User registration
* User login
* Material upload
* AI question answering
* Flashcards
* Quiz
* Summarization
* Study plan
* API response time
* Error handling

Performance testing can be performed using tools such as **Postman** to evaluate response time, throughput, error rate, CPU utilization, and memory utilization.

---

## Expected Outcome

AI Study Buddy provides students with a convenient platform for academic assistance. It combines Artificial Intelligence with learning features to make studying, revision, and self-learning easier and more interactive.

---

## Team Members

**Team ID:** SWTID-2026-7718

* **SAVITHA . M** — Team Leader
* **GOPIKA . M.G** — Team Member
* **ALEXANDRA . B** — Team Member
* **NITHYA . D** — Team Member

---

## Conclusion

AI Study Buddy is an educational application that combines Artificial Intelligence with student learning. It provides quick answers, explanations, study materials, quizzes, flashcards, summaries, and study planning through an interactive platform.

The project aims to support independent learning and make the overall study process easier and more effective.
