Here is a complete, step-by-step guide to setting up your web development environment and preparing everything required for Assignment 1.2.

Step-by-Step Implementation Guide
1. Install Visual Studio Code
Action: Download and install Visual Studio Code for your operating system (Windows, macOS, or Linux). Follow the default installation prompts.

2. Install Node.js (LTS Version)
Action: Go to the official Node.js website and download the LTS (Long Term Support) version. Run the installer and ensure that the option to add Node.js to your system PATH is checked.

3. Install VS Code Extensions
Open Visual Studio Code.

Click on the Extensions icon on the left sidebar (or press Ctrl+Shift+X on Windows/Linux or Cmd+Shift+X on macOS).

Search for and install the following two extensions:

Live Server (by Ritwick Dey) — allows you to launch a local development server with live reload capability.

Prettier - Code Formatter (by Prettier) — automatically formats your code for clean styling.

4. Create the Project Folder
Open your terminal (or Command Prompt / PowerShell on Windows, Terminal on macOS) and run the following commands to create your practice folder and navigate into it:

Bash
mkdir web-development-practice
cd web-development-practice
Open this folder in VS Code by typing code . in your terminal, or by opening VS Code manually and selecting File > Open Folder to choose your newly created web-development-practice folder.

5. Create Project Files
Inside the web-development-practice folder, create the following three blank files:

index.html

style.css

script.js

Populate them with the foundational starter code below:

index.html

HTML
<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Assignment 1.2 - Development Environment</title>
    <link rel="stylesheet" href="style.css">
</head>
<body>
    <div class="container">
        <h1>Environment Setup Successful!</h1>
        <p>My web development workspace is fully operational.</p>
    </div>
    <script src="script.js"></script>
</body>
</html>
style.css

CSS
body {
    font-family: Arial, sans-serif;
    background-color: #f4f4f9;
    display: flex;
    justify-content: center;
    align-items: center;
    height: 100vh;
    margin: 0;
}
.container {
    text-align: center;
    background: white;
    padding: 30px;
    border-radius: 8px;
    box-shadow: 0 4px 8px rgba(0, 0, 0, 0.1);
}
h1 {
    color: #333;
}
script.js

JavaScript
console.log("Web development environment is working correctly!");
6. Run the HTML File Using Live Server
Open index.html inside Visual Studio Code.

Right-click anywhere inside the code editor window and select Open with Live Server (or click the "Go Live" button on the bottom-right corner of the VS Code status bar).

Your default web browser will automatically open to a local address (typically [http://127.0.0.1:5500](http://127.0.0.1:5500)) displaying your styled webpage.

7. Verify Node.js and npm Installations
Open your terminal inside VS Code (Terminal > New Terminal) or your system terminal and execute the following verification commands:

Bash
node -v
npm -v
Note: Take screenshots of your terminal showing the version outputs for your assignment submission.

Submission Checklist
Make sure you capture and save the following screenshots as required for your submission:

VS Code Workspace: Showing your project folder structure (index.html, style.css, script.js) and the open code editor.

Terminal Version Check: Showing the output of the node -v and npm -v commands.

Running Web Page: Showing your index.html file open and rendering properly in your browser via Live Server.