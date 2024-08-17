
# CodeMatrix

## About
CodeMatrix is a coding platform designed to provide an interactive coding experience. It allows users to enhance their coding skills by solving algorithmic challenges, submitting their solutions, and competing on global leaderboards. With a focus on usability and performance, it is the ideal platform for both novice and experienced coders to practice and improve their programming abilities.

## Features

-   **User Authentication**: Users can sign in to their accounts to access personalized features and track their progress.
-   **Problem Statements**: Users can browse and access a wide range of coding problems, organized into various difficulty levels.
-   **Solution Submission**: Users can submit their solutions to problems and receive immediate feedback on correctness and performance.
-   **Scoring System**: Points are awarded based on the speed and efficiency of the solution, encouraging optimized and faster problem-solving.
-   **Global Leaderboard**: A dynamic leaderboard displays top performers across daily, weekly, monthly, and all-time rankings, fostering a competitive and engaging environment

## Installation

To set up and run the CodeMatrix platform locally, follow these steps:

### 1. Clone the Repository

Clone the repository to your local machine:
```
git clone <repository-url>
cd CodeMatrix
```

### 2. Set Up the Frontend

1.  **Navigate to the Frontend Directory**:
    ```
    cd frontend
    ```
    
2.  **Install Frontend Dependencies**: Install the necessary dependencies:
    ```
    npm install
    ```
    
4.  **Start the Frontend Development Server**: Launch the frontend development server:
    ```
    npm start
    ```
    The frontend will be accessible at `http://localhost:5173`.
    

### 3. Set Up Firebase Functions

**Pre-requisites**:

-   Ensure you have [Node.js](https://nodejs.org/) and [npm](https://www.npmjs.com/) installed.
-   Install Firebase CLI if you haven’t already:
  ```
    npm install -g firebase-tools
  ```
    

### 4. Configure Firebase

**Firebase Configuration**:

1.  Make sure you have a Firebase project created in the Firebase Console.
2.  Configure your Firebase CLI to use your Firebase project:
    ```
    firebase login
    firebase use --add`
    ```
    
    Follow the prompts to select your Firebase project.

### 5. Set Up the Backend

1.  **Navigate to the Backend Directory**:
    ```
    cd ../backend
    ```
      
2.  **Install Backend Dependencies**: Install the necessary dependencies:
    ```
    npm install
    ```

## Future Improvements

-   **Enhanced Problem Types**: Expanding problem types and categories to include more diverse and challenging problems.
-   **Code Review System**: Implementing a feature for peer code reviews to provide feedback and suggestions.
-   **Real-Time Collaboration**: Adding real-time collaborative coding features for group problem-solving.
