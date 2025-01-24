# AI-Enhanced Profile Project

## Homework Steps

0. Install Node.js
   - Go to https://nodejs.org/
   - Download and install Node.js LTS version
   - Verify installation:
     ```bash
     node --version
     npm --version
     ```

1. Setup GitHub
   - Create a GitHub account
   - Configure your GitHub profile

2. Setup Cursor
   - Download Cursor from https://cursor.sh/
   - Install and configure Cursor on your machine

3. Fork My Repo
   - Go to the project repository
   - Click "Fork" button in the top-right corner
   - Wait for the fork to complete

4. Clone Repo to Local Machine
   - Open terminal/command prompt
   - Navigate to desired directory
   - Run: `git clone https://github.com/YOUR_USERNAME/ai-profile-project.git`

5. Use Cursor to Create a Component
   - Open the project in Cursor
   - Create your own custom component

6. Run the Project
   - Navigate to project directory
   - Install dependencies: `npm install`
   - Start the server: `npm start`
   - Open browser and visit: http://localhost:3000

7. Add & Commit Change
   - Check status: `git status`
   - Add changes: `git add .`
   - Commit: `git commit -m "Added my custom component"`

8. Push to Repo
   - Push changes: `git push origin main`
   - Verify changes on GitHub



## Project Overview

This project is a beginner-friendly web application that demonstrates how to create a simple profile card with AI-enhanced customization capabilities. It's designed to help students learn basic web development concepts and AI integration.

## Prerequisites

### Installing Git

Git is a version control system that helps you track changes in your code.

1. **Windows**:
   - Download Git from: https://git-scm.com/download/windows
   - Run the installer and follow the setup wizard
   - Verify installation by opening Command Prompt and typing:
     ```bash
     git --version
     ```

2. **macOS**:
   - If you have Homebrew installed:
     ```bash
     brew install git
     ```
   - Or download from: https://git-scm.com/download/mac
   - Verify installation:
     ```bash
     git --version
     ```

3. **Linux (Ubuntu/Debian)**:
   ```bash
   sudo apt update
   sudo apt install git
   git --version
   ```

For more detailed Git installation instructions, visit: https://git-scm.com/book/en/v2/Getting-Started-Installing-Git

### Installing Node.js

Node.js is required to run the server for this project.

1. **Windows**:
   - Download the LTS version from: https://nodejs.org/
   - Run the installer and follow the setup wizard
   - Verify installation:
     ```bash
     node --version
     npm --version
     ```

2. **macOS**:
   - Download the LTS version from: https://nodejs.org/
   - Or use Homebrew:
     ```bash
     brew install node
     ```
   - Verify installation:
     ```bash
     node --version
     npm --version
     ```

3. **Linux (Ubuntu/Debian)**:
   ```bash
   curl -fsSL https://deb.nodesource.com/setup_lts.x | sudo -E bash -
   sudo apt install -y nodejs
   node --version
   npm --version
   ```

For more detailed Node.js installation instructions, visit: https://nodejs.org/en/download/package-manager/

## Setting Up the Project

### 1. Fork the Repository

1. Go to the project repository on GitHub
2. Click the "Fork" button in the top-right corner
3. Wait for GitHub to create a copy in your account

### 2. Clone Your Fork

1. Open your terminal/command prompt
2. Navigate to where you want to store the project
3. Clone your forked repository:
   ```bash
   git clone https://github.com/YOUR_USERNAME/ai-profile-project.git
   cd ai-profile-project
   ```

### 3. Install Dependencies and Run

1. Install project dependencies:
   ```bash
   npm install
   ```

2. Start the server:
   ```bash
   npm start
   ```

3. Open your browser and visit:
   ```
   http://localhost:3000
   ```

## Making Changes

### 1. Modify the Code

1. Open the project in your favorite code editor
2. Main files you can modify:
   - `public/index.html` - Structure of the webpage
   - `public/styles.css` - Styling of the webpage
   - `server.js` - Server configuration

### 2. Save Your Changes

1. Check which files you've modified:
   ```bash
   git status
   ```

2. Add your changes to staging:
   ```bash
   git add .
   ```

3. Commit your changes with a descriptive message:
   ```bash
   git commit -m "Description of your changes"
   ```

### 3. Push to GitHub

1. Push your changes to your fork:
   ```bash
   git push origin main
   ```

## Project Structure

```
project-folder/
  ├── public/
  │   ├── index.html      # The main webpage
  │   └── styles.css      # Styling for the webpage
  ├── server.js           # Node.js server configuration
  ├── package.json        # Project dependencies and scripts
  └── README.md          # This file
```

## Troubleshooting

1. **Port Already in Use**
   ```bash
   # Kill the process using port 3000
   # Windows:
   netstat -ano | findstr :3000
   taskkill /PID <PID> /F

   # macOS/Linux:
   lsof -i :3000
   kill -9 <PID>
   ```

2. **Node Modules Missing**
   ```bash
   # Remove node_modules and reinstall
   rm -rf node_modules
   npm install
   ```

3. **Git Issues**
   - Ensure your Git credentials are configured:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "your.email@example.com"
     ```

## Additional Resources

- Git Documentation: https://git-scm.com/doc
- Node.js Documentation: https://nodejs.org/docs/
- Express.js Guide: https://expressjs.com/guide/routing.html
- HTML MDN Guide: https://developer.mozilla.org/docs/Web/HTML
- CSS MDN Guide: https://developer.mozilla.org/docs/Web/CSS