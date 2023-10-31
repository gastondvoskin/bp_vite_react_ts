# Boilerplate: React + TypeScript + Vite


## Overview

This template provides a minimal setup to get React working in Vite with HMR and some ESLint rules. 

### Modifications to the Original Template

- The entire content within App.tsx has been removed.
- The content of App.css was deleted and replaced with an empty App.module.css file.
- Most of the content in index.css was removed, leaving only :root and body.
- The assets directory has been removed.
- The public directory has been removed.
- This README.md has been edited.


## Prerequisites
Before you begin, ensure you have the following prerequisites in place:

1. **Clone Repository**: Clone this Git repository to your local machine.

2. **Install Dependencies**: Install project dependencies by running the following command:

    ```bash
    npm install
    ```

## Running the Project

1. **Start Development Environment**: To start the development environment and watch for changes, run the following command:

    ```bash
    npm run dev
    ```


## Starting a New Project

If you want to start a new project based on this boilerplate, follow these steps:

1. **Delete Git History**: Manually open the root directory. If you are on Windows, click `View` > `Show` > `Hidden Items` to view the hidden items. Delete the `.git` directory to remove the project's Git history.

4. **Start a New Git Repository**: Initialize a new Git repository and commit your project:

    ```bash
    git init
    git add .
    git commit -m "Initial commit (boilerplate)"
    ```

5. **Add a Remote Origin**: Create a repository in Azure Repos or your preferred version control platform and follow the steps provided to add the remote origin (e.g., `git remote add origin ...` and `git push -u origin main`).

6. **Rename the Root Directory**: Rename the root directory to your preferred project name.