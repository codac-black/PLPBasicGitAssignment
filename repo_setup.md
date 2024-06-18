# Repository Setup

The objective of this assignment was to familiarize myself with the basic workflow of creating a GitHub repository, connecting it to a local folder, and making commits and pushes.

## Requirements

- A GitHub account (created one if not already available).
- Git installed on the local machine.
- A code editor of choice (e.g., Visual Studio Code, Sublime Text).

## Task 1: Repository Setup

1. GitHub Repository Creation:
    - Logged in to the GitHub account.
    - Created a new repository on GitHub (named "PLPBasicGitAssignment").
    - Initialized it with a README file.

## Task 2: Local Setup

2. Local Folder Setup:
    - Created a new folder on the local machine (e.g., "PLPBasicGitAssignment").
    - Opened a terminal or command prompt and navigated to the created folder.

3. Git Initialization:
    - Initialized a new Git repository in the local folder.

4. Connecting to GitHub:
    - Linked the local repository to the GitHub repository created in Task 1.
    ```shell
    git remote add origin <repository-url>
    ```
    Replaced `<repository-url>` with the actual URL of the GitHub repository.

## Task 3: Making Changes

5. Created a File:
    - Inside the local folder, created a new text file (e.g., `hello.txt`).
    - Added a simple text message (e.g., "Hello, Git!").

6. Committing Changes:
    - Staged the changes.
    ```shell
    git add hello.txt
    ```
    - Committed the changes.
    ```shell
    git commit -m "Added hello.txt with a greeting"
    ```

## Task 4: Pushing to GitHub

7. Pushing to GitHub:
    - Pushed the committed changes to the GitHub repository.
    ```shell
    git push -u origin main
    ```

## Task 5: Verification

8. Verified on GitHub:
    - Visited the GitHub repository in a web browser and confirmed that the `hello.txt` file and commit message were visible.

