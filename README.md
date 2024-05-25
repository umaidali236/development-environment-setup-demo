# Development Environment Setup

This guide will walk you through setting up your software development environment using Visual Studio Code, Git, and GitHub Desktop.

## Prerequisites
   - A GitHub account.
 
## What are we doing today?

**Installing and configuring the following software tools :**

- [Visual Studio Code](https://code.visualstudio.com/)
- [Git](https://git-scm.com/)
- [GitHub Desktop](https://desktop.github.com/)

## Step 1: Install Visual Studio Code

- **VS Code (Visual Studio Code):** It's a lightweight but powerful source code editor developed by Microsoft. It's highly extensible through plugins and supports a variety of programming languages and development workflows. VS Code includes features like syntax highlighting, debugging capabilities, code completion, and version control integration.
Follow these steps to install it:

1. Visit the [Visual Studio Code website](https://code.visualstudio.com/).
2. Download the installer for your operating system (Windows, macOS, or Linux).
 ![vs-code](/documentation/images/vs-code.png)
3. Run the installer and follow the on-screen instructions to complete the installation.
4. First, accept the License Agreement, then click Next.
  ![vs-code](/documentation/images/vs-code/vs-code.jpg)
5. Choose the location for installation and click Next.
 ![vs-code](/documentation/images/vs-code/vs-code1.jpg)
6. Accept the default Start Menu folder name by clicking Next.
7. Check the boxes for 'Creating a desktop icon', and adding VS Code to the Right-Click menu functionality of Windows File Explorer, then click Next.
 ![vs-code](/documentation/images/vs-code/vs-code2.jpg)
8. Confirm the installation options, then click Install.
9. Click Finish to exit the installation and (by default) launch Visual Studio Code.

## Step 2: Install Git

Git is a distributed version control system that helps track changes in source code during software development. Here's how to install Git:

1. Visit the [Git website](https://git-scm.com/).
2. Download the installer for your operating system.
 ![git-for-windows](/documentation/images/git-win.png)
3. Run the installer and follow the on-screen instructions to complete the installation.
4. In the component selection screen, leave the defaults unless you need to change them and click Next.
 ![git-for-windows](/documentation/images/git/git-components.jpg)
5. Select a text editor you want to use with Git. Use the drop-down menu to select `visual studio code` and click Next.
 ![git-for-windows](/documentation/images/git/git-text-editor.jpg)
6. The next step allows you to choose a different name for your initial branch. The default is master.
 ![git-for-windows](/documentation/images/git/git-branch-name.jpg)
7. The next step allows you to change the PATH environment. The PATH is the default set of directories included when you run a command from the command line. Keep the middle (recommended) selection and click Next.
 ![git-for-windows](/documentation/images/git/git-path-environment.jpg)
8. The installer prompts you to select the SSH client for Git to use. Leave the default option and click Next.
 ![git-for-windows](/documentation/images/git/git-ssh.jpg)
9. The next option relates to server certificates. The default option is recommended for most users.
 ![git-for-windows](/documentation/images/git/git-ssl.jpg)
10. The following selection configures line-ending conversion, which relates to the way data is formatted. The default selection is recommended for Windows. Click Next to proceed.
 ![git-for-windows](/documentation/images/git/git-line-ending.jpg)
11. Choose the terminal emulator you want to use. The default MinTTY is recommended for its features. Click Next to continue.
 ![git-for-windows](/documentation/images/git/git-terminal.jpg)
12. The next step allows you to choose what the git pull command will do. The default option is recommended. Click Next to continue.
 ![git-for-windows](/documentation/images/git/git-gitpull.jpg)
13. The next step is to choose which credential helper to use. Git uses credential helpers to fetch or save credentials. The default option is the most stable one. Select your preferred credential manager and click Next.
 ![git-for-windows](/documentation/images/git/git-credential.jpg)
14. The next step lets you decide which extra options to enable.
 ![git-for-windows](/documentation/images/git/git-extra.jpg)
15. For the most stable operation, do not install experimental features and click Install.
 ![git-for-windows](/documentation/images/git/git-experimental.jpg)
16. Once the installation is complete, tick the boxes to view the Release Notes or launch Git Bash if you want to start using Git right away, and click Finish.

  ![git-for-windows](/documentation/images/git/git-finish.jpg)
   


## Step 3: Install GitHub Desktop

GitHub Desktop provides an easy-to-use interface for interacting with GitHub repositories. Follow these steps to install it:

1. Visit the [GitHub Desktop website](https://desktop.github.com/).
2. Download the installer for your operating system.
 ![github-desktop](/documentation/images/github-desktop.png)
3. Run the installer and follow the on-screen instructions to complete the installation.
4. Launch GitHub Desktop and click on sign in to GitHub account.
  ![github-desktop](/documentation/images/github-desktop/githubd-signin.jpg)
5. It will take you to the GitHub page and ask for your login credentials.
  ![github-desktop](/documentation/images/github-desktop/githubd-signin1.jpg)
6. After successfully signing in , click on open GitHub desktop.
  ![github-desktop](/documentation/images/github-desktop/githubd-prompt.jpg)
7. Then select Use my GitHub account name and email address and click on finish.
  ![github-desktop](/documentation/images/github-desktop/githubd-configure.jpg)
8. Then under the File tab click on Options. 
  ![github-desktop](/documentation/images/github-desktop/githubd-options.jpg)
9. In the Integrations section, select VS Code as External Editor.
  ![github-desktop](/documentation/images/github-desktop/githubd-integrations.jpg)
  
## Step 4 : Connecting GitHub with VSCode

1. Go to the source code tab from the left sidebar. You should see a 'Clone Repository' or 'Publish to GitHub' (if you have opened a folder already) option. Click on the Clone Repository and give it a GitHub repo link or click on 'Clone from GitHub'.
 ![github-desktop](/documentation/images/vscode/vscode.jpg)   
3. It will then show you a message that asks you to sign in to GitHub.
 ![github-desktop](/documentation/images/vscode/vscode1.jpg)  
4. Click on Allow button and it will open a browser tab with a GitHub login page.
 ![github-desktop](/documentation/images/vscode/vscode2.jpg)  
5. You should see a message like this and click Open.It should take a couple of seconds and you should be signed into your GitHub account.
 ![github-desktop](/documentation/images/vscode/vscode3.jpg)  
6. How do you know you are logged into GitHub with VS Code?click on the Profile icon at the bottom left corner to see if it says you are logged in to your GitHub account.
 ![github-desktop](/documentation/images/vscode/vscode4.jpg)

## Extensions for VS Code

### 1. ESLint

- Extension id :  ` dbaeumer.vscode-eslint `

- Enter the Extension id or ESLint in the Extensions search box

- Click on install

![eslint](/documentation/images/es-lint.png)

### 2. Markdownlint

- Extension id :  ` davidanson.vscode-markdownlint`

- Enter the Extension id or Markdownlint in the Extensions search box

- Click on install

![markdownlint](/documentation/images/markdownlint.png)

### 3. Github Pull requests

- Extension id :  `github.vscode-pull-request-github`

- Enter the Extension id or Github Pull requests in the Extensions search box

- Click on install

![github-pr](/documentation/images/github-pr.png)

### 4. Live Preview

- Extension id :  `ms-vscode.live-server`

- Enter the Extension id or Live Preview in the Extensions search box

- Click on install

![live-preview](/documentation/images/live-preview.png)

### 5. Prettier - Code formatter

- Extension id :  `ms-vscode.live-server`

- Enter the Extension id or Prettier - Code formatter in the Extensions search box

- Click on install

![prettier](/documentation/images/prettier.png)

### 6. JavaScript and TypeScript Nightly

- Extension id :  `ms-vscode.vscode-typescript-next`

- Enter the Extension id or JavaScript and TypeScript Nightly in the Extensions search box

- Click on install

![typescript](/documentation/images/typescript.png)

## Productivity tips

### VS Code

- Shift + alt + F : format
- Ctrl + S : save
- Ctrl + R : refresh
- Ctrl + T : new tab
- Ctrl + / : comment
- Ctrl + right arrow/ left arrow : jump one word to right or left
- Ctrl + Shift + right arrow/ left arrow : select word
- Alt + up arrow/ down arrow : shifts line up or down
- End : jumps to end of line
- Home : jumps to start of line

### Emmet tools

- ! : basic html structure
- div.container : div element with class='container'
- div#name : div element with id='name'
- div*5 : 5 div elements.


