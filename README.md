# mern-cat-facts-notes
A full-stack MERN note-taking application where each note is paired with a random cat fact. Built with React, Node.js, MongoDB

# 🐱 Cat-Fact Note-Taking App

A simple note-taking web application built using the **MERN stack** (MongoDB, Express.js, React, Node.js). Each note is automatically assigned a random [cat fact](https://catfact.ninja/fact) upon creation.

---

##  Features

- Add notes with a title and content.
- Each note is auto-tagged with a random cat fact.
- View, search, and delete notes.
- Search by title, content, or cat fact.
- Actuator-style metrics (API call counter).
- Clean UI with functional components & React Context API.
- Dockerized for easy deployment.

---

## 📦 Tech Stack

- **Frontend**: React (with Context API, Hooks, Axios)
- **Backend**: Node.js, Express.js
- **Database**: MongoDB
- **Metrics**: Actuator-style HTTP request counter
- **Docker**: Backend & frontend containerization

---

##  Getting Started

### Prerequisites

- Node.js & npm
- MongoDB (or Docker)
- Docker (optional, for containerized setup)

-

#### 1. Clone the repository

```bash
git clone https://github.com/yourusername/catfact-notes-app.git
cd catfact-notes-app
