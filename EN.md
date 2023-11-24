# Documentation: How to Make the First Commit on GitHub via Terminal

## 1. Initial Setup

Before you begin, make sure to have Git installed on your machine. If not, you can download it from [git-scm.com](https://git-scm.com/downloads).

## 2. Create a Repository on GitHub

1. **Access GitHub and Log In:**
   - Open your web browser and go to [GitHub](https://github.com/). Log in to your GitHub account.

2. **Create a New Repository:**
   - Click on the "+" sign in the upper right corner of the page and select "New repository" from the dropdown menu.

3. **Fill in New Repository Information:**
   - Fill in the repository name in the "Repository name" field.
   - Add an optional description in the "Description" field.
   - Choose whether to make the repository public or private.
   - Select the option "Initialize this repository with a README" if you want to create a README file in the repository.
   - Click "Create repository" to create the new repository.

4. **Get the Repository Link:**
   - On the repository page, click the "Code" button.
   - In the popup window, click the copy icon next to the URL to copy the repository link.

## 3. In the Terminal, Execute the Following Commands:

```bash
# Initialize a local repository
git init

# Add all files to the staging area
git add .

# Make the first commit
git commit -m "First commit"

# Create a new branch (optional)
git branch -M main

# Add the remote repository
git remote add origin <paste the repository link>

# Try to push the changes to GitHub
git push -u origin main
```
Replace <paste the repository link> with the link you copied earlier.

**Note:** If you encounter an error when trying to push, you can try forcing the push using the following command:

# Getting GitHub Changes to Local Repository (Pull)

When working on a team project where others contribute to the same GitHub repository, it's crucial to keep your local repository up-to-date with the latest changes. To achieve this, you can use the `git pull` command, which fetches the changes from GitHub to your local repository.

## How to Pull Changes:

Before executing the `git pull` command, it's important to understand that this command merges the GitHub changes with your local work. If you have unpushed local changes (uncommitted local commits), Git will attempt to automatically merge the GitHub changes with your local changes.

**In the Terminal, Execute the Following Command:**
```bash
git pull origin main
```

This command fetches the latest changes from the main branch on GitHub to your local repository.
