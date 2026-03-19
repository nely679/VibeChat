# Development Environment Setup for VibeChat

## Prerequisites

Before you begin, ensure you have the following installed:

- **Node.js** (version X.X.X) - Make sure you have Node.js installed. You can check your version with `node -v`.
- **npm** (comes with Node.js) - Used for package management. Check your version with `npm -v`.
- **Git** - Required for version control. Check your version with `git --version`.

## Setting Up the Development Environment

1. **Clone the Repository**  
   Open your terminal and run:
   ```bash
   git clone https://github.com/nely679/VibeChat.git
   cd VibeChat
   ```

2. **Install Dependencies**  
   Once you have cloned the repository, navigate to the project folder and install the necessary packages:
   ```bash
   npm install
   ```

3. **Setting Up Environment Variables**  
   You may need to create a `.env` file in the root of the project. This file will contain environment-specific variables:
   ```bash
   cp .env.example .env
   ```
   Fill out the necessary variables as per your setup.

4. **Running the Application**  
   To start the application, run:
   ```bash
   npm start
   ```
   Your application will be available at `http://localhost:3000` (or your specified port).

## Additional Notes

- Always check for any additional notes in the repository's documentation regarding setup.
- Keep your dependencies updated for the best performance and security.