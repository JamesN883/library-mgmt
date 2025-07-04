[![Contributors][contributors-shield]][contributors-url]
[![Forks][forks-shield]][forks-url]
[![Stargazers][stars-shield]][stars-url]
[![Issues][issues-shield]][issues-url]

# LibMan

A web-based **Library Management System** that helps librarians manage books, authors, members, and loan transactions with ease. Built with **Java Spring Boot** (backend) and **React** (frontend), LibMan supports CRUD operations, real-time updates, and intuitive navigation.

## 📚 Table of Contents
1. [Introduction](#introduction)
2. [Team Members](#team-members)
3. [Installation and Setup](#installation-and-setup)
4. [Features](#features)
5. [Challenges](#challenges)

## 📖 Introduction <a name="introduction"></a>
LibMan is a full-stack library management system that helps librarians manage books, members, and loan transactions efficiently.
The system is built using Java Spring Boot for the backend and React for the frontend. It supports CRUD operations, structured DTO-based APIs, and a responsive user interface for intuitive navigation.

## 👥 Team Members <a name="team-members"></a>

| Order | Name                       | Student ID   |
|:-----:|----------------------------|:------------:|
| 1     | Tran Nguyen Phuc           | ITCSIU21097  |
| 2     | Nguyen Mach Khang Huy      | ITCSIU21072  |
| 3     | Bui Cong Vinh              | ITCSIU22165  |
| 4     | Nguyen Bach Dong Phuong    | ITCSIU22118  |
| 5     | Nguyen Thi Quynh Nga       | ITCSIU22094  |
| 6     | Le Minh Duy                | ITCSIU22037  |
| 7     | **Nguyen Minh Viet**       | ITDSIU21130  |
| 8     | Tran Quoc Bao              | ITITWE20033  |

## 🚀 Installation and Setup <a name="installation-and-setup"></a>

1. Clone the repo
   ```sh
   git clone https://github.com/tnphucccc/LibMan.git
   ```
2. Start the backend
   ```sh
    cd backend
    mvn spring-boot:run
    ```
3. Start the frontend
    ```sh
     cd frontend
     npm install
     npm run start
     ```
4. Open your browser and navigate to `http://localhost:5173/`

## ✅ Features <a name="features"></a>
- 📚 Add, update, and delete books
- ✍️ Add, update, and delete authors
- 🧑 Add, update, and delete members
- 🔄 Borrow and return books
- 📜 View borrowing history
- 🔍 Search books

## ⚠️ Challenges <a name="challenges"></a>
- Managing relational data between books, members, and authors while preserving referential integrity
- Implementing structured DTOs for cleaner API design and validation
- Setting up seamless communication between React and Spring Boot APIs
- Ensuring smooth UX across data retrieval and modification processes

<!-- MARKDOWN LINKS & IMAGES -->
<!-- https://www.markdownguide.org/basic-syntax/#reference-style-links -->
[contributors-shield]: https://img.shields.io/github/contributors/tnphucccc/LibMan.svg?style=for-the-badge
[contributors-url]: https://github.com/tnphucccc/LibMan/graphs/contributors
[forks-shield]: https://img.shields.io/github/forks/tnphucccc/LibMan.svg?style=for-the-badge
[forks-url]: https://github.com/tnphucccc/LibMan/network/members
[stars-shield]: https://img.shields.io/github/stars/tnphucccc/LibMan.svg?style=for-the-badge
[stars-url]: https://github.com/tnphucccc/LibMan/stargazers
[issues-shield]: https://img.shields.io/github/issues/tnphucccc/LibMan.svg?style=for-the-badge
[issues-url]: https://github.com/tnphucccc/LibMan/issues
