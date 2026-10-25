Assignment 1.4 — Git Essentials I

Aim

To convert a local project into a Git repository and learn basic Git commands.

Procedure

1. Installed Git and verified the installation.
2. Opened the terminal in the project folder.
3. Initialized a Git repository using "git init".
4. Configured the Git username and email.
5. Created an HTML file named "index.html".
6. Checked the repository status using "git status".
7. Added files using "git add" and saved changes using "git commit".
8. Created three meaningful commits to maintain the project history.

Terminal Commands

1. Verify Git Installation

git --version

2. Create and Initialize the Project

mkdir git-practice
cd git-practice
git init

3. Configure Git Username and Email

git config --global user.name "Your Name"
git config --global user.email "your.email@example.com"

Replace the example name and email with your own details.

4. Create the HTML File

Create a file named "index.html" and add the following code:

<!DOCTYPE html>
<html lang="en">
<head>
    <meta charset="UTF-8">
    <meta name="viewport" content="width=device-width, initial-scale=1.0">
    <title>Git Practice</title>
</head>
<body>
    <h1>Welcome to Git Practice</h1>
    <p>This is my first Git project.</p>
</body>
</html>

5. First Commit — Add HTML Structure

git status
git add index.html
git commit -m "Add initial HTML structure"

6. Second Commit — Add a Description

Add this paragraph inside the "<body>" element in "index.html":

<p>I am learning Git version control.</p>

Then run:

git status
git add index.html
git commit -m "Add Git learning description"

7. Third Commit — Update the Page Title

Change the title in "index.html" to:

<title>My Git Learning Project</title>

Then run:

git status
git add index.html
git commit -m "Update project page title"

8. Verify Commit History

git log --oneline

To check the final repository status:

git status

The working tree should be clean after all changes have been committed.

Expected Output

- Git is installed and its version is displayed.
- A local Git repository is initialized successfully.
- The "index.html" file is tracked by Git.
- Three meaningful commits are created successfully.
- The "git log --oneline" command displays the three commits.
- The final "git status" shows that the working tree is clean.

Observations

1. The "git init" command initializes a new Git repository.
2. The "git config" command sets the Git username and email.
3. The "git status" command displays the current state of the repository.
4. The "git add" command stages changes for committing.
5. The "git commit" command saves a snapshot of the staged changes.
6. The "git log --oneline" command displays the commit history in a concise format.
7. Git helps track changes and maintain different versions of a project.

Result

The local project was converted into a Git repository successfully. Git configuration, staging, committing, checking repository status, and viewing commit history were practiced.

Submission

Attach the following screenshots:

1. The project folder containing "index.html" and the ".git" repository folder (enable hidden files if necessary).
2. The terminal showing the output of "git log --oneline" with all three commits.
3. The terminal showing the final output of "git status".
