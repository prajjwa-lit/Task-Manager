# Offline First Task Manager App

The **Offline First Task Manager App** is a modern, cross-platform task management solution designed to work seamlessly both online and offline. It combines a sleek user interface with robust backend functionality, ensuring a reliable and efficient experience for users.

---

## Features

- **Offline-First Functionality**: Manage tasks without an internet connection using local storage, with automatic synchronization when online.
- **Task Management**: Create, update, delete, and organize tasks effortlessly.
- **User Authentication**: Secure login and user-specific task management.
- **Cross-Platform Support**: Built with Flutter for compatibility across Android, iOS, and web.
- **Scalable Backend**: A containerized backend ensures scalability and portability.
- **Modern UI**: A visually appealing interface with custom fonts and smooth navigation.

---

## Tech Stack

### Frontend
- **Flutter**: For building a responsive and cross-platform UI.
- **Bloc (Cubit)**: For efficient state management.
- **SQLite**: For offline data storage.

### Backend
- **Node.js**: For a fast and scalable server-side runtime.
- **Express**: For building RESTful APIs.
- **TypeScript**: For type-safe backend development.
- **PostgreSQL**: For robust and reliable database management.
- **Docker**: For containerization and easy deployment.

---

## Project Structure

### Frontend
- **Flutter App**: Contains all UI components, state management logic, and SQLite integration for offline storage.

### Backend
- **Node.js Server**: Handles API requests, authentication, and task synchronization.
- **PostgreSQL Database**: Stores user and task data persistently.
- **Dockerized Environment**: Simplifies deployment and ensures consistency across environments.

---

## How It Works

1. **Offline Mode**: Tasks are stored locally in SQLite when offline.
2. **Online Sync**: When connected, tasks are synchronized with the PostgreSQL database via the backend.
3. **Authentication**: Users can securely log in to access their tasks across devices.

---

## Getting Started

### Prerequisites
- **Flutter SDK** installed for frontend development.
- **Node.js** and **npm** for backend development.
- **Docker** for containerized deployment.
- **PostgreSQL** database setup.

