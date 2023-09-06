# Getting Started with GitHub

GitHub is a powerful platform for version control and collaborative development. This tutorial will guide you through the process of creating a new repository, cloning an existing repository, and pushing code changes to it.

## Table of Contents

1. [Creating a New Repository](#creating-a-new-repository)
2. [Cloning a Repository](#cloning-a-repository)
3. [Pushing Code to a Repository](#pushing-code-to-a-repository)

------

### 1. Creating a New Repository

#### Step 1: Sign In or Create an Account

If you don't have a GitHub account, go to [GitHub's website](https://github.com/) and sign up. If you already have an account, sign in.

#### Step 2: Create a New Repository

1. Click on the "+" sign in the upper right corner of the GitHub homepage.
2. Select "New Repository" from the dropdown menu.

![Create Repository](https://user-images.githubusercontent.com/24832920/134765259-ff3b70f9-58ea-4a27-b161-ee2f60aa8f3c.png)

#### Step 3: Fill in Repository Details

- **Repository Name**: Choose a unique name for your repository.
- **Description**: Add a brief description of your project (optional).
- **Visibility**: Choose between public (visible to everyone) or private (only visible to collaborators).

![Repository Details](https://user-images.githubusercontent.com/24832920/134765536-ccab10e2-3e04-4d47-8d38-0f8a861c30b3.png)

#### Step 4: Initialize with a README

- Select the "Initialize this repository with a README" option. This will create an initial README file for your repository.

![Initialize README](https://user-images.githubusercontent.com/24832920/134765614-97a4a40c-18d4-4e7b-aa93-35c9569f93d9.png)

#### Step 5: Create Repository

Click the "Create repository" button to create your new repository.

---

### 2. Cloning a Repository

#### Step 1: Find a Repository to Clone

You can clone both your own repositories or those shared by others.

#### Step 2: Get the Repository URL

1. Open the repository you want to clone.
2. Click the "Code" button.

![Clone Repository](https://user-images.githubusercontent.com/24832920/134765762-e26d918b-6649-4ae5-85cf-d79a9a918580.png)

3. Copy the repository URL.

#### Step 3: Clone the Repository Locally

Open your terminal or command prompt and navigate to the directory where you want to clone the repository.

```bash
cd /path/to/your/directory
```

Use the `git clone` command followed by the repository URL you copied:

```bash
git clone https://github.com/username/repository-name.git
```

Replace `https://github.com/username/repository-name.git` with the actual repository URL.

#### Step 4: Access the Cloned Repository

You now have a local copy of the repository on your computer.

---

### 3. Pushing Code to a Repository

#### Step 1: Make Changes

Make changes to the files in your local repository using your preferred code editor or IDE.

#### Step 2: Stage and Commit Changes

1. Stage the changes by using the `git add` command:

```bash
git add .
```

This stages all the changes in your local repository.

2. Commit the changes with a descriptive message:

```bash
git commit -m "Your commit message here"
```

Replace `"Your commit message here"` with a brief, informative message about the changes you made.

#### Step 3: Push Changes to GitHub

Use the `git push` command to send your committed changes to GitHub:

```bash
git push origin main
```

Replace `main` with the name of the branch you're working on, e.g., `master` or `develop`.

#### Step 4: Verify Changes on GitHub

Visit your GitHub repository in a web browser to see your changes reflected in the repository.

#### Step 5: Obtaining GitHub token

You can follow the following steps, to obtain a GitHub token:

* Log in to your GitHub account and go to your “Settings” page.
* Click on “Developer settings” in the left-hand sidebar.
* Click on “Personal access tokens” and choose “Tokens (classic)”.
* Click on “Generate new token” then “Generate new token (classic)” .
* Give your token a description, so you can remember what it is for.
* Select all the scopes available.
* Click on “Generate token”.


```{note}
Your new token will be displayed. Be sure to copy it and save it for future use, as you won’t be able to see it again.
```

Once you have generated a token, you can use it to authenticate with the GitHub API or access repositories that require authentication. Keep your token secret and avoid sharing it with others to protect your GitHub account’s security.

