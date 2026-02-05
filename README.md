Name: Raphael Harloverin Gunarso 

NIM: 2902641824 

Class: B4CC

Article: https://blog.devgenius.io/git-branch-and-git-merge-best-practices-for-git-basics-876a035fc7a7

In this article, I will show you how to use Git to clone and remote a GitHub repository from your local machine. We will also apply Git branching and merging to the repository we have created.

In general (not everyone), most people when learn git basics still do not fully understand how to implement Git branching and merging in a GitHub repository. As a result, some may feel less confident when creating a new branch in a repository and then merging it.

Hopefully, through this article, you will gain a better understanding of how to apply or use Git branching and merging in a GitHub repository.

Step 2 — Create a repository (repo) on github website

First, you can open the github website (https://www.github.com) and sign in with your github account. After that, you can click + icon in the top-right corner of the github website page, then select “New repository”. (check the image below).

After selecting “New Repository”, you will be directed to the “Create a New Repository” page. You can fill in the details as shown in the image, then click “Create Repository” to create the repository.
Prerequisite

    Github Account. You must have a github account in github website (https://github.com/). Please register a new github account if you don’t have the github account.
    Git Command. You must download and install git in your local machine/laptop. For Downloading the git, please refer to this link: https://git-scm.com/downloads
    Code Editor (Visual Studio Code). If you don’t have Visual studio code or code editor in your local machine/computer. Please download and install the code editor app. (https://code.visualstudio.com/download)

    In this article, you will learn about:

    How to Create and Remote the Github Repository From Local Machine.
    How to implementing Branches Using Git Branch and Git Merge.

Step 1 — Create folder and file in your local machine/computer

Create a new folder in your local machine/computer named “test_git” (for an example). We will use that folder as a working directory to remote our repository in github.

Open your code editor (Ex: Visual Studio Code, etc). After that, open the folder that you have prepared earlier in the Visual Studio Code (VS Code), then click on the “File” menu -> “Open Folder”, and select the folder you previously created on your computer. Or, you can also drag and drop the folder directly into VS Code, and the folder will be open.

If the folder (test_git) is already open in VS Code, the display will look like the image below.

Next, create a new file with Markdown (.md) format in that folder (test_git folder) named “README.md” (for an example). In this tutorial, I will populate the README.md file with an article titled “Indonesia Country”, which I sourced from Wikipedia. Of course, you can fill the README.md file with any content you like. After that, don’t forget to save the file (Ctrl + S). For more details about the Markdown (.md) format, you can learn through the following link: https://www.markdownguide.org/basic-syntax/

    A README.md file is a Markdown file commonly used in projects to provide important information about the project. It usually includes an introduction, installation instructions, usage guidelines, and other relevant details. The “.md” extension indicates that it uses Markdown formatting, allowing for easy styling like headings, lists, links, and code snippets.

    In repositories (e.g., GitHub, GitLab), the README.md file is automatically displayed on the main page to help users understand the project quickly.

Open the terminal in VS Code (Terminal -> New terminal). The terminal will then appear inside VS Code. Since my computer runs Windows Operating system, the default terminal is PowerShell. However, you can change it to your preferred terminal based on your needs.

After selecting “New Repository”, you will be directed to the “Create a New Repository” page. You can fill in the details as shown in the image, then click “Create Repository” to create the repository.

    Owner: indicates who owns the repository.

    Slash ( / ): used to separate the repository name from the owner.

    Repository name: filled with the name of your repository or project in the provided field. (Ex: learn_git_branch)

    Description: contains a description of the repository being created. This field is optional — you may fill it in or leave it blank.

After that, Congratulations! You will be directed to the GitHub repository page (check the image below), where you will find information for remotely accessing the repository. Next, we will remote the repository to the local machine/computer.

Step 3 — Remote the github repository from local machine using git command

Focus on the terminal in VS Code. Type and follow the Git commands below to remotely connect to the repository.

    First, type “git init” and press enter to Initialize a new Git repository (repo) in the current directory.
