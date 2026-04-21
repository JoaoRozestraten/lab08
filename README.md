# Web Development Labs

Repository created on 08/26/2024.

**Objective:** Store and track files from past classes, laboratories, and future assignments related to the Web Development course.

##  Directory Structure & Laboratories

This repository contains progressively complex exercises covering both Frontend and Backend web development:

*   **`lab01` & `lab02`:** Introduction to fundamental HTML tags, page structure, and text formatting.
*   **`lab04`:** A multi-page image gallery featuring Nature, Space, and Technology themes, styled with CSS.
*   **`lab16`:** A functional calculator developed using HTML, CSS, and JavaScript.
*   **`lab32`:** A simple interactive Quiz application built with HTML, CSS, and JavaScript.
*   **`lab64`:** Introduction to backend development with Node.js and Express. Features include static page routing (Home, About), EJS template rendering, and file upload functionality capable of handling uploads via both HTML forms and the terminal.
*   **`lab128`:** Basic Node.js server setup and configuration.
*   **`PI` (Projeto Integrador / Integrative Project):** A more comprehensive project combining frontend and backend concepts. It includes user authentication pages (Login, Register) and a questionnaire (qst), all served via a Node.js backend.

##  How to Run the Projects

### Static Frontend Projects (Lab 01 to Lab 32)
Simply navigate to the respective laboratory folder and open the `.html` files directly in your web browser. 
*(Alternatively, you can use an extension like Live Server in VS Code).*

### Backend Node.js Projects (`lab64`, `lab128`, `PI`)
To run any of the Node.js projects, follow these steps in your terminal:

1.  Navigate to the specific project directory:
    ```bash
    cd lab64  # or cd lab128, or cd PI
    ```
2.  Install the required dependencies:
    ```bash
    npm install
    ```
3.  Start the application server:
    ```bash
    node server.js
    ```
4.  Open your browser and navigate to the local server (usually `http://localhost:3000` unless specified otherwise in the console).
