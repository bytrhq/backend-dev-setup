# Tooling and Environment Setup
  This guide provides step-by-step instructions for setting up a development environment on a Windows machine. It includes the installation of Node.js, NPM, Visual Studio Code (VSCode), Git Bash, and configuration of Git and GitHub.

# SD1.1 - Installation Guide

## Guide to Setting Up a Development Environment on Windows
   This guide will walk you through the steps of setting up a development environment on your Windows machine, including the installation of Node.js, NPM, VSCode, Git Bash, and configuring Git and GitHub.

[Installing NodeJS & NPM] (https://www.notion.so/Installing-NodeJS-NPM-0a3c86e5dab245c19a428858733d0b43?pvs=21)
[Installing VSCode & Extensions] (https://www.notion.so/Installing-VSCode-Extensions-b5d3164b5b864eef9e5895e96570ef9f?pvs=21)
[Installing Git Bash] (https://www.notion.so/Installing-Git-Bash-b0b6fe6d730b45f194bf88709fe4a87c?pvs=21)


## Table of Contents

1. [Installing Node.js & NPM](#1-installing-nodejs--npm)
2. [Installing VSCode & Extensions](#2-installing-vscode--extensions)
   - [2.1 Extension Installation and Their Usage](#21-extension-installation-and-their-usage)
   - [2.2 Enable Bracket Pair Colorization](#22-enable-bracket-pair-colorization)
3. [Installing Git Bash](#3-installing-git-bash)
4. [Creating a GitHub Account and Connecting Git and GitHub](#4-creating-a-github-account-and-connecting-git-and-github)
   - [4.1 Creating a GitHub Account](#41-creating-a-github-account)
   - [4.2 Connecting Git to GitHub](#42-connecting-git-to-github)


## 1. Installing Node.js & NPM

Node.js is a JavaScript runtime built on Chrome's V8 JavaScript engine. NPM (Node Package Manager) comes bundled with Node.js and is used to install Node.js packages.

### Steps to Install Node.js and NPM:

1. Visit the [Node.js official website](https://nodejs.org/).
2. Download the LTS (Long Term Support) version for Windows from the homepage or the downloads page.
3. Run the installer and follow the prompts in the setup wizard.
4. Ensure NPM package manager is included in the installation.
5. Verify the installation:
   - Open Command Prompt and type:
     ```bash
     node -v
     npm -v
     ```
   - This should display the installed versions of Node.js and NPM.

## 2. Installing VSCode & Extensions

Visual Studio Code (VSCode) is a popular code editor that supports many programming languages and frameworks.

### Steps to Install VSCode:

1. Visit the [VSCode official website](https://code.visualstudio.com/).
2. Download the installer for Windows.
3. Run the installer:
   - Accept the terms and conditions.
   - Leave the default installation location and check the box to add VSCode to the system PATH for easier access from the command line.
   - Check all the boxes shown in the installer.

### 2.1 Extension Installation and Their Usage

Extensions enhance the functionality of VSCode. Here are some recommended extensions:

- **Prettier - Code Formatter**
  - Open VSCode.
  - Go to the Extensions view by clicking on the Extensions icon in the Activity Bar or press `Ctrl+Shift+X`.
  - Search for "Prettier" and click Install.
  - Prettier will format your code automatically when you save files. [Prettier Documentation](https://prettier.io/docs/en/)

- **GitLens — Git supercharged**
  - Search for "GitLens" in the Extensions view and click Install.
  - GitLens helps visualize code authorship via Git blame annotations and code lens. [GitLens Documentation](https://gitlens.ampproject.org/)

- **Better Comments**
  - Search for "Better Comments" and click Install.
  - This extension helps create more human-friendly comments in your code. [Better Comments Documentation](https://marketplace.visualstudio.com/items?itemName=aaron-bond.better-comments)

### 2.2 Enable Bracket Pair Colorization

Bracket pair colorization enhances code readability by color-coding matching brackets.

1. Open Settings in VSCode by clicking on the gear icon at the bottom left and selecting Settings or press `Ctrl+,`.
2. In the search bar, type `Bracket Pair Colorization`.
3. Check the box next to `Editor > Bracket Pair Colorization: Enabled`.

## 3. Installing Git Bash

Git Bash provides a bash emulation to run Git from the command line.

### Steps to Install Git Bash:

1. Visit the [Git official website](https://git-scm.com/).
2. Download the Git installer for Windows.
3. Run the installer:
   - Accept the terms and conditions.
   - Leave the default installation location.
   - Check all the boxes shown in the installer.
   - Keep Vim as the default editor for Git.
   - Choose to override & keep the name as main.
   - Select Git from the command line and also from 3rd-party software option.
   - Keep all default options in the future steps and finish installation.

## 4. Creating a GitHub Account and Connecting Git and GitHub

GitHub is a cloud-based hosting service that lets you manage Git repositories.

### 4.1 Creating a GitHub Account

1. Visit the [GitHub official website](https://github.com/).
2. Click on the Sign Up button.
3. Follow the prompts to create your account.

### 4.2 Connecting Git to GitHub

💡 Ensure that the email and name you configure are both professional and appropriate.

1. Open Git Bash.
2. Configure your Git username and email using the following commands:
   ```bash
   git config --global user.name "Your Name"
   git config --global user.email "your.email@example.com"
