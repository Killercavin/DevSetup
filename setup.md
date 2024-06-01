# Assignment

## Setup Development Environment

## Objective

This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

## Tasks

### Task 1: Selecting an Operating System

- **Windows 11 Operating System**
  - Download Windows 11 Operating System from the official Microsoft website [Windows 11](https://www.microsoft.com/en-us/windows/get-windows-11) that best matches your operating system (Windows 11 is only available for x64).
  - Download Rufus from the official website [Rufus](https://rufus.ie/).
  - Create a bootable USB drive using Rufus.
  - Restart your computer and boot from the USB drive.
  - Follow the on-screen instructions to install Windows 11 on your system.
  - Install the latest updates and security patches.
  - Configure the system settings and personalize the desktop.

### Task 2: Installing a Text Editor or Integrated Development Environment (IDE)

- **Visual Studio Code**
  - Download Visual Studio Code from the official website [VSCode](https://code.visualstudio.com) that best matches your operating system (use x64 for Windows 11).
  - Select the Visual Studio Code executable file.
  - Double-click or right-click the executable file to install Visual Studio Code on your system by following the on-screen instructions.

### Task 3: Setting Up Version Control

- **Git and GitHub**
  - Navigate to the GitHub website [GitHub](https://github.com) and create an account.
  - **Git**
    - Download Git from the official website [Git](https://git-scm.com) that best matches your operating system (use x64 for Windows 11).
    - Select the Git executable file.
    - Double-click or right-click the executable file to install Git on your system by following the on-screen instructions.
    - Open Git Bash, PowerShell, Command Prompt, or Terminal and configure your Git username and email address:
      ```sh
      git config --global user.name "Your Name"
      git config --global user.email "Your Email"
      git config --list
      ```

  - **GitHub SSH Key Generation**
    - Open Git Bash, PowerShell, Command Prompt, or Terminal.
    - Generate a new SSH key with the command:
      ```sh
      ssh-keygen -t ed25519 -C "your_email@example.com"
      ```
    - Copy the SSH key to the clipboard:
      ```sh
      clip < ~/.ssh/id_ed25519.pub
      ```
    - Navigate to the GitHub website and sign in to your account.
    - Go to your profile icon and select **Settings**.
    - Click on **SSH and GPG keys**.
    - Click on **New SSH key**.
    - Add a descriptive label for the new key (e.g., "Personal laptop").
    - Paste the copied SSH key into the key field and click **Add SSH key**.
    - Confirm the SSH key was added successfully:
      ```sh
      ssh -T git@github.com
      ```
      - The terminal output should be "Hi [{your_username}] ...".
    - Create a new repository on GitHub.
    - Clone the repository to your local machine:
      ```sh
      git clone https://github.com/DevSetup.git
      ```
    - Create a new file in the repository, add, commit, and push the changes:
      ```sh
      git add .
      git commit -m "Added a new file to the repository"
      git push
      ```

### Task 4: Install Necessary Programming Languages and Runtimes

- **Instructions for installing specific programming languages and runtimes would go here.**
- **Installing Python:**
  - Download Python from the official website [Python](https://www.python.org).
  - Select the Python executable file.
  - Double-click or right-click the executable file to install Python on your system by following the on-screen instructions.
  - Select the option to add Python to the system PATH during installation.
  - Verify the installation by running the command:
    ```sh
    python --version
    ```
- **Installing Dart:**
  - Download Dart from the official website [Dart](https://dart.dev).
  - Navigate to the **Windows** section and download the Dart SDK.
  - Download the Dart archive file.
  - Extract the contents of the archive file to a specific directory on your system or on the current folder of choice.
  - Create a directory for the Dart SDK (e.g., C:\Dart).
  - Navigate to the folder where the Dart archive was extracted.
  - Move the contents of the extracted folder to the Dart SDK directory.
  - Select the Dart/bin directory and copy the path.
  - Add the Dart bin directory to the system PATH:
    - Right-click on **This PC** or **My Computer**.
    - Select **Properties**.
    - Click on **Advanced system settings**.
    - Click on **Environment Variables**.
    - Under **System variables**, select **Path** and click **Edit**.
    - Click **New** and add the path to the Dart bin directory.
  - Verify the installation by running the command:
    ```sh
    dart --version
    ```
### Task 5: Configure a Database (MySQL): Download and install MySQL database on your system.
  - Download MySQL community version from the official website [MySQL](https://www.mysql.com). 
  - Select the MySQL installer file.
  - Double-click or right-click the executable file to install MySQL on your system by following the on-screen instructions.
  - Configure the MySQL server settings and set up a root password.
  - Verify the installation by running the command:
    ```sh
    mysql --version
    ```
### Task 6: Explore Extensions and Plugins:
- Start Visual Studio Code.
- Navigate to the Extensions view by clicking on the Extensions icon in the Activity Bar on the side of the window.
- Search for extensions or plugins that enhance your coding experience ie Python, Dart, MySQL, etc.
- Install the desired extensions or plugins by clicking on the Install button.
- Explore the features and functionalities of the installed extensions or plugins.
- Customize the settings of the extensions or plugins to suit your preferences.


## Submission
- Done! 
```sh 
echo Happy Coding!
```
