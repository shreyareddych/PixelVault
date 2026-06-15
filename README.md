# PixelVault

A full-stack photo storage and sharing platform that enables users to securely upload, organize, manage, and access digital images through a responsive and intuitive web interface. PixelVault combines modern web technologies with a scalable backend architecture to deliver a seamless photo management experience.

---

## Overview

PixelVault is designed to simplify digital photo management by providing secure image storage, efficient data handling, and an easy-to-use user interface. The application follows modern software engineering practices and leverages a layered architecture to ensure maintainability, scalability, and performance.

---

## Features

* Secure user registration and authentication
* Photo upload and storage management
* Personal image gallery organization
* Browse, view, and manage uploaded photos
* Responsive and user-friendly interface
* Database-driven image metadata management
* RESTful API integration between frontend and backend
* Scalable architecture supporting future enhancements

---

## Technology Stack

### Frontend

* HTML5
* CSS3
* JavaScript

### Backend

* Java
* Spring Boot
* REST APIs

### Database

* MySQL

### Development Tools

* Git
* GitHub
* Maven

### Methodology

* Agile Scrum

---

## System Architecture

```text
+------------------+
|     Frontend     |
| HTML / CSS / JS  |
+--------+---------+
         |
         v
+------------------+
| Spring Boot APIs |
+--------+---------+
         |
         v
+------------------+
|      MySQL       |
|    Database      |
+------------------+
```

---

## Project Structure

```text
PixelVault/
│
├── src/
│   ├── main/
│   │   ├── java/
│   │   ├── resources/
│   │   └── static/
│   │
│   └── test/
│
├── database/
├── assets/
├── docs/
└── README.md
```

---

## Installation and Setup

### Clone the Repository

```bash
git clone https://github.com/your-username/PixelVault.git
```

### Navigate to the Project Directory

```bash
cd PixelVault
```

### Configure the Database

Update the database credentials in the application configuration file:

```properties
application.properties
```

### Run the Application

```bash
mvn spring-boot:run
```

The application will start locally and be accessible through your configured server port.

---




This project is intended for educational and learning purposes.
