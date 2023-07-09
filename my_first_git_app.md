# Git Case Study: My First Git App

## Objective
The objective of this case study is to familiarize yourself with Git commands and perform basic operations such as creating a project, creating a README file, adding content, committing the file, and pushing it to a remote repository. This case study will help you get started with Git and understand the basic workflow.

## Prerequisites
1. Ubuntu operating system installed on your machine.
2. Git installed on your machine. If not installed, run `sudo apt-get install git` to install Git.

## Steps

### Step 1: Creating a Project Directory
1. Open your terminal.
2. Navigate to the directory where you want to create your project.
3. Run the following command to create a new directory named "myapp":

mkdir myapp

This will create a new directory to hold your project.

### Step 2: Creating a README File
1. Run the following command to navigate into the "myapp" directory:

cd myapp

2. Run the following command to create a new file named `README.md`:

touch README.md

3. Open the `README.md` file in a text editor of your choice.
4. Add the following content to the file: "My first git app to help me understand git basic commands usage."

### Step 3: Adding and Committing the README File
1. Run the following command to initialize a new Git repository in the "myapp" directory:

git init

This will create an empty Git repository in the "myapp" directory.
2. Run the following command to stage the changes you made to the `README.md` file:

git add README.md

This will add the `README.md` file to the staging area.
3. Run the following command to commit the changes with a descriptive message:

git commit -m "Initial commit"

This will create a commit with the changes you made to the `README.md` file.

### Step 4: Pushing the README File to a Remote Repository
1. If you have an existing remote repository (e.g., GitLab or GitHub), copy the remote repository URL.
2. Run the following command to add the remote repository:

git remote add origin <repository_url>

Replace `<repository_url>` with the actual URL of your remote repository.
3. Run the following command to push the committed changes to the remote repository:

git push -u origin master

This will push the changes to the `master` branch of the remote repository.

Congratulations! You have successfully completed the case study, creating a project directory named "myapp," adding content to a README file, committing the file, and pushing it to a remote repository. This basic workflow is a fundamental part of using Git for version control.

