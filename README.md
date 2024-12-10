# Password Strength Checker - Monorepo

This is the monorepo for the Password Strength Checker project, combining the backend and frontend implementations. The application evaluates password strength based on entropy, mutation warnings, predictable patterns, and user-specific data.

### Features

#### Backend

    Provides RESTful APIs for password analysis.
    Calculates password entropy.
    Detects predictable patterns and common mutations.
    Securely stores user data using hashed passwords.

#### Frontend

    Offers an interactive UI for password analysis.
    Displays password strength with tips for improvement.
    Insights include entropy, mutation warnings, and prediction warnings.

#### Monorepo Structure

    Password-Strength-Checker/
    ├── backend/       # Contains the backend implementation
    ├── frontend/      # Contains the frontend implementation
    └── README.md      # This file

Each directory contains its own README.md with additional details specific to the backend or frontend.
Getting Started

<span style="font-size: 18px; font-weight: bold;">Prerequisites:</span>

    Node.js (v14+)
    MongoDB (for backend)

##### Installation Instructions
Step 1: Clone the Monorepo

    git clone https://github.com/usv240/password-strength-checker.git
    cd password-strength-checker

Step 2: Setup Backend

  Navigate to the backend directory:

    cd backend

Install dependencies:

    npm install

Start MongoDB on your machine and ensure it's running.
Configure the MongoDB connection string in the code:

    mongodb://localhost:27017/Passwordchecker

Run the backend server:

    npm start

Step 3: Setup Frontend

  Navigate to the frontend directory:

    cd frontend

Install dependencies:

    npm install

Ensure the backend server is running on http://localhost:3002 (default configuration).
Run the frontend application:

    npm start

The frontend will be available at http://localhost:3000.

### Original Repositories

This monorepo is a combined version of the following repositories:

    [Password_Checker_Backend](https://github.com/usv240/Password_Checker_Backend) : The original backend implementation.
    [Password_Checker_Frontend](https://github.com/usv240/Password_Checker_Frontend) : The original frontend implementation.

If you want to explore the individual implementations, visit the above links.

### Screenshots
https://drive.google.com/file/d/13rcea6CnAyGL6swSXwTSAArwTy1NrJIq/view?usp=sharing, 
https://drive.google.com/file/d/1BjNrwFhpn4dZlepMj0qNgCPSBY6Oe74C/view?usp=sharing, 
https://drive.google.com/file/d/1aukhhGAzkH_Gfgr8yRLja1wNH9kmMwY2/view?usp=sharing, 
https://drive.google.com/file/d/1kvu23ktG0P25EffBEh5V_CgtCZFmA1ai/view?usp=sharing

For any queries or contributions, feel free to contact me.
