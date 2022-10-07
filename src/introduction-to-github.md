# Introduction To GitHub

## Table of content

- Introduction
- What is GitHub
- Why GitHub
- Git vs GitHub
- how to Clone a repository from GitHub
- how to make a pull request
- how to commit
- GitHub Desktop vs GitHub CLI
- Conclusion

---

## Introduction

As a software project grows, it becomes important to track and manage it.
This article will take you through one of the most popular means used to do this, **GitHub**. You will understand the basic concepts of GitHub such as repositories, commits, cloning and pull requests.

Certain requirements are necessary for you to flow along with this article. These include:

- a [GitHub account](http://github.com/)
- Internet Access
- Installed [Git](https://git-scm.com/) on your local computer

## What is GitHub

For you to have a better understanding of GitHub, you need to understand two important concepts associated with it,

- Version control
- Git

**Version control**, also known as source control, is the practice of tracking and managing changes to software code.

**Git** is an open-source version control system designed to handle projects of all scales with speed and efficiency. It handles everything GitHub-related that is on your computer.

**GitHub** is a code hosting platform for version control and collaboration. It offers a cloud-based Git repository hosting service which lets you and others to work together on projects from anywhere.

> A GitHub repository is a container of all your project's files and each file's revision history.

## Why GitHub

GitHub lets you and others to work together on projects from anywhere around the world.
It makes it a lot easier for individuals and teams to use Git for version control and collaboration.

## Git vs GitHub

**Git** is a version control system that lets you manage and keep track of your source code history whereas, **GitHub** is a cloud-based hosting service that lets you manage Git repositories.

If you have open-source projects that use Git, then GitHub will help you better manage them.

Another difference to note is that Git is installed and maintained on your local system while GitHub is the only cloud-based

## How to Clone a repository from GitHub

The act of cloning a GitHub repository refers to the process of copying the repository from GitHub to your local machine. In essence, by cloning a repository, you create a local copy of your project on which new changes and alterations are made and synced between the two storage locations (i.e. cloud and local)

This is usually done to make it easier to fix merge conflicts, add or remove files and push new commits

To clone a repository;

1. visit [GitHub.com](http://github.com/) and navigate to the repository's main page.

2. Above the list of files, click **Code**
   ![main page](img/img1.jpg)

3. Copy the URL for the repository
   ![copy url](img/img2.jpg)

4. Open Git Bash on your computer.

5. Change the current working directory(location) to the location where you want to save the cloned repository.

6. Type `git clone`, and then paste the URL you copied earlier
   ![paste url](img/img3.jpg)

7. Press **Enter** to create your local clone. ![create](img/img4.jpg)

## How to make a pull request

Pull requests let you tell others about changes you've pushed to a branch in a repository. Once a pull request is opened, you can discuss and review the potential changes with collaborators and add follow-up **commits** before your changes are accepted.

To create a pull request;

1. Navigate to the main page of the repository.
2. select **New pull request**
   ![pull request](img/img5.jpg)
3. select the branch you pushed your code to
4. click **Create pull request**![create](img/img6.jpg)
5. fill in the required details and **Create pull request** ![create](img/img7.jpg)

This lets the repo's maintainers review your contribution

## How to commit

A **commit** records changes made to one or more files in your repository. It is like saving a file, that's been edited, to your local repository.

To commit after making changes;

1. Navigate to the **source control** on your IDE
2. Hover over the **Changes** panel and click the **plus icon** to **stage** all your changes
   ![commit](img/img8.jpg)
3. open your terminal
4. type `git commit -m "your commit message"`
5. Press enter
   ![commit](img/img9.jpg)

> to sync these changes to your GitHub repository, type `git push` in your terminal and press **Enter** after committing

## GitHub Desktop vs Github CLI

GitHub Desktop is an application that enables GUI-based interaction with GitHub instead of using the command line or a web browser. You can use GitHub Desktop to complete most Git commands from your desktop with visual confirmation of changes.

> GUI (graphical user interface)

The GitHub CLI, however, is an open-source tool for using GitHub from your computer's command line.
When you're working from the command line, you can use the GitHub CLI to save time and avoid switching contexts.

## Conclusion

In this article, you have come to understand basic concepts and terminologies including

- What GitHub is
- Why GitHub is important
- the difference between Git and GitHub
- The processes involved in:
  - Cloning a repository from GitHub
  - making a pull request and
  - committing changes to a repository
- The difference between GitHub Desktop vs Github CLI