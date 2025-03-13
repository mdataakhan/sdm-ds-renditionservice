The naming convention is to show this is microservice architecture sdm-ds is the service and renditionservice is one of the microservice 
In my local space there were already teams related microservices deployed hence I showed one of them as part of my demo.
I have removed java files due to compliance issue and replaced with simple java implementation.
Main focus of this Assignment was on how Devops tools like SonarQube, Mend, and Jenkins make life easier for developers working on microservice and to demostrate Cloud Foundary advantages.

# Git Workflow Guide

This guide outlines the steps to initialize a Git repository, add files, commit changes, and push them to a remote repository.

### 1. Initialize the Git repository

To start tracking your project with Git, you need to initialize a new repository in your project directory. Run the following command:

```bash
git init
```

This creates a `.git` folder and starts tracking the files in your directory.

### 2. Add files to staging

After initializing the repository, you need to add the files that you want to commit. To add all files in your current directory, run:

```bash
git add .
```

This command stages all files (new and modified) for the next commit.

### 3. Commit the staged files

Once the files are added, the next step is to commit them. Commits are snapshots of your project at a particular time. You can provide a message describing the changes you’ve made in the commit:

```bash
git commit -m "Initial commit"
```

Replace `"Initial commit"` with a relevant commit message that describes the changes you've made.

### 4. Push the changes to the remote repository

If you have a remote Git repository (like GitHub, GitLab, or Bitbucket), you need to push the changes to the remote repository. First, ensure you are connected to your remote repository, then push your changes to the main branch:

```bash
git push origin main
```

This command sends the local commits to the remote repository, specifically to the `main` branch.
