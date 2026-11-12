# GitHub

## Introduction
GitHub is a cloud-based platform used to host Git repositories. It helps developers store, manage, share, and collaborate on software projects.

## Topics Covered
- Introduction to GitHub
- Features and uses of GitHub
- Creating a GitHub account
- Creating and managing repositories
- Public and private repositories
- Connecting local Git repositories to GitHub
- Remote repositories
- Pushing and pulling changes
- Cloning and forking repositories
- Pull requests and issues
- README files and repository documentation
- Project collaboration and contributions

## Beginner-Friendly Setup Commands

### 1. Configure Git
Set your username and email before making commits.

```bash
git config --global user.name "Your Name"
git config --global user.email "your-email@example.com"
```

Check your configuration:

```bash
git config --list
```

### 2. Create a Local Repository

```bash
mkdir my-project
cd my-project
git init
```

### 3. Add and Commit Files

```bash
git add .
git commit -m "Initial commit"
```

### 4. Create a Repository on GitHub
- Log in to GitHub.
- Click on **New Repository**.
- Enter a repository name.
- Choose Public or Private.
- Create the repository.

### 5. Connect Local Repository to GitHub

Replace the URL with your own GitHub repository URL.

```bash
git remote add origin https://github.com/username/repository-name.git
git branch -M main
```

### 6. Upload Your Project

```bash
git push -u origin main
```

## Important GitHub Commands

| Command | Purpose |
|---|---|
| `git clone URL` | Copy a remote repository |
| `git remote -v` | View remote repository URLs |
| `git push` | Upload local commits |
| `git pull` | Fetch and integrate remote changes |
| `git fetch` | Download remote changes without merging |
| `git push -u origin main` | Push the main branch and set its upstream |

## Learning Outcomes
- Understand GitHub and its features.
- Create and manage online repositories.
- Connect local projects to GitHub.
- Upload and download project changes.
- Understand cloning, forking, and pull requests.
- Collaborate and share projects online.

## Conclusion
This section covers the basics of GitHub, including repository creation, initial setup, remote operations, and collaboration features.