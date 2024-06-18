[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15277704&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

Visit the provided link: https://www.microsoft.com/software-download/windows11
Click on the blue "Download Now" button for the Windows 11 ISO file (disc image).
Choose a save location on your computer.
Click "Save" to download the ISO file.

Insert an empty USB drive with at least 8GB of storage space.
Download and install the Microsoft Media Creation Tool from this link: https://www.microsoft.com/software-download/windows11

Open the Media Creation Tool and select "Create installation media for another PC" option.
Select your language, architecture (64-bit or 32-bit) my prefrence is the 64-bit option, and edition of Windows 11.
Choose "USB flash drive" as the media type.
Select the inserted USB drive and click "Next".
The Media Creation Tool will download the Windows 11 files and create a bootable USB drive.

Boot from the USB, you will see the Windows 11 setup screen.
Choose your language, time and currency format, and keyboard input method.
Click "Next" to continue.

On the "Install Now" screen, enter your Windows 11 product key if you have one. If you don't have a product key, click "I don't have a product key" to continue.
Accept the license terms.

Choose "Custom: Install Windows only (advanced)" installation type.
Select the drive where you want to install Windows 11.
Click "Format" to format the drive (recommended for a clean installation).

Click "Next" to begin the installation process.
The installation will take some time. Your computer may restart several times during the process.

Once the installation is complete, you will be prompted to set up your Windows 11 account.
Connect to your Wi-Fi network.
Set up your privacy settings.

Choose a theme and color scheme.
Create a PIN or password for your account.
Your Windows 11 installation is now complete. You can proceed to install drivers, software, and personalize your system as desired.

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download


Step 1: Download Visual Studio Code
Navigate to the Visual Studio Code download page: https://code.visualstudio.com/Download
Choose the appropriate installer for your operating system and download the file.

Step 2: Install Visual Studio Code
Double-click the downloaded installer file.
Follow the on-screen instructions to complete the installation.
Accept the license agreement and choose the installation location.

Step 3: Configure Visual Studio Code
Launch Visual Studio Code.
If prompted, choose the "Create" option to create a new workspace.
To open a project folder, click on "File" > "Open Folder..." and select the desired folder.

Step 4: Install Language Extensions
For each programming language you want to work with, install the appropriate extension.
Click on the "Extensions" tab on the left sidebar.
Search for the extension for your language, e.g., "Python", "Java", or "C#".
Click the "Install" button for the extension and restart Visual Studio Code.

Step 5: Customize Your Workspace
To customize your workspace settings, click on "File" > "Settings" (on Windows and Linux).
Here you can adjust various settings such as:
Appearance (themes, font size)
User interface (layout, keyboard shortcuts)
Language-specific settings (e.g., linting rules)

Step 6: Start Coding
Create a new file or open an existing one by clicking on the "File" menu.
Start writing code and enjoy the features of Visual Studio Code, such as:
Code completion
Syntax highlighting
Debugging
Version control integration
Additional Tips:

Use the shortcut keys "Ctrl + K, Ctrl + S" to save your changes.
Explore the documentation and tutorials available on the Visual Studio Code website: https://code.visualstudio.com/docs/
Join the Visual Studio Code community forum for support and discussions: https://github.com/microsoft/vscode/discussions

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

1.Install Git
For Windows: Download the Git executable from https://git-scm.com/download and install it.

2.Configure Git
Set your username:
git config --global user.name "Your Name"
Set your email:
git config --global user.email "your@email.com"

3.Create a GitHub Account
Go to https://github.com and sign up for a free account.

4.Initialize a Git Repository
Navigate to the directory where your project is located.
Initialize a new Git repository:
git init

5.Make Your First Commit
Stage all the files you want to include in your first commit:
git add .
Commit the changes with a message describing the commit:
git commit -m "Initial commit"

6.Push to GitHub
Create a new repository on GitHub for your project.
Copy the clone URL of the remote repository on GitHub.
Add the remote repository to your local repository:
git remote add origin https://github.com/your-username/your-repo-name.git
Push your changes to the remote repository:
git push origin master
Additional Tips:

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

Step 1: Visit the Python website

Go to the official Python website: http://www.python.org
Step 2: Download the Python installer

Click on the "Downloads" link on the website's main page.
Select the appropriate Python version for your operating system.
Click on the download link for the executable file (.exe for Windows, .pkg for Mac, .tar.xz for Linux).
Step 3: Install Python

Run the downloaded executable file.
Follow the on-screen instructions to complete the installation.
Step 4: Verify the installation

Open your terminal or command prompt.
Type
python --version
and press Enter.
You should see the installed Python version printed in the terminal.
Installing Compilers, Interpreters, and Runtimes:

After installing Python, you may need to install additional tools depending on the specific programming languages and frameworks you will be using for your project.

Compilers: If you are using compiled languages like C or C++, you will need to install a compiler. You can typically find the compiler for your language on the language's official website.
Interpreters: Interpreted languages like JavaScript and PHP do not require a compiler. Instead, you will need to install an interpreter that can execute the code. Interpreters are usually available on the official website of the language or framework.
Runtimes: Some frameworks, such as Node.js or Java, require a runtime environment to run their code. These runtimes are typically available for download on the framework's official website.
To determine the specific tools you need:

Check the documentation or requirements section for your project.
Research the programming languages and frameworks you will be using.
Consult online resources or forums for specific installation instructions.
Once you have identified the necessary tools:

Visit the official website for each tool and download the appropriate installer or package.
Follow the on-screen instructions to complete the installation.
Verify that the installation was successful by running the corresponding command or checking the system path.

5. Install Package Managers:
   If applicable, install package managers like pip (Python).

Before installing Check if pip is already installed on your system: Open a terminal window and run the following command:
pip --version
If you see a version number printed, pip is already installed.

Install pip: If pip is not installed, install it using the following command:
python -m ensurepip --upgrade
Update pip: To install any available updates to pip, run the following command:
python -m pip install --upgrade pip
Additional Notes:

Ensure that Python is installed on your system before installing pip.
If you encounter any permissions issues, try running the commands with
sudo
.
Refer to the official pip documentation for more information: https://pip.pypa.io/en/latest/installing/.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

Step 1: Download the MySQL Installer

Visit the MySQL download page: https://dev.mysql.com/downloads/windows/installer/5.7.html
Click on the "Download" button for the Windows installer (x86 or x64 depending on your system).

Step 2: Install MySQL

Run the downloaded MySQL installer executable file.
Follow the on-screen instructions and choose the following options:
Select the "Custom" installation type.
Check the boxes for "MySQL Server" and "MySQL Workbench".
Click "Next" and choose the installation directory (default is recommended).
Click "Next" and choose "InnoDB" as the default storage engine.
Set up a root password for MySQL. This is the password you will use to log in to MySQL.
Click "Next" and select the "Typical" option for the MySQL Server configuration.
Click "Install" to start the installation.

Step 3: Configure MySQL

Open the MySQL Workbench application.
Click on the "Database" tab.
Enter the root password you set during the installation.
Click on the "Manage Connections" button and create a new connection to your MySQL server.
Open the "SQL Editor" tab.
Run the following commands to create a new database and grant permissions:
CREATE DATABASE my_database;
GRANT ALL PRIVILEGES ON my_database.* TO 'my_user'@'localhost' IDENTIFIED BY 'my_password';
FLUSH PRIVILEGES;

Step 4: Verify Installation

Open a command prompt or terminal window.
Type the following command to connect to MySQL as the root user:
mysql -u root -p
Enter your root password.
Type the following command to verify that the database and user were created:
SHOW DATABASES;
SHOW GRANTS FOR 'my_user'@'localhost';
You should see the newly created database and user in the output.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

I am running windows 11 and as a result will not require the use of a virtual macine.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

   Exploring Extensions, Plugins, and Add-Ons for Visual Studio

Step 1: Access the Visual Studio Marketplace

Open Visual Studio.
Click on the "Extensions" tab in the top menu.
This will open the Visual Studio Marketplace.
Step 2: Browse Extensions

Use the search bar to find specific extensions or browse by category.
Some popular categories include:
Code Editing
Debugging Tools
Productivity Tools
Version Control
Step 3: Explore Extension Details

Click on an extension to view its details.
Read the description, features, and user reviews.
Check the compatibility with your Visual Studio version and project type.
Step 4: Install Extensions

Click on the "Download" button to install the extension.
Depending on the extension, you may need to restart Visual Studio for the installation to take effect.
Step 5: Examples of Useful Extensions

Syntax Highlighting and Linting

Roslynator - Enables rich syntax highlighting and semantic analysis for C# and Visual Basic.
EditorConfig for Visual Studio - Enforces coding standards and conventions across team members.
Code Formatting

Prettier - Automatically formats JavaScript, JSON, and TypeScript code according to a consistent style.
CodeMaid - Provides code cleanup, formatting, and refactoring tools.
Version Control Integration

Git - Integrates Git version control functionality within Visual Studio.
Azure DevOps - Connects Visual Studio to Azure DevOps for project tracking and collaboration.
Additional Tips

Use filters to narrow down search results based on language, category, or feature.
Read user reviews and ratings to assess the quality of extensions.
Keep your extensions up-to-date to ensure compatibility and bug fixes.
Use the "Manage Extensions" window to enable, disable, or uninstall extensions.
Consider using an extension manager like Extensis for easier management and updates..

9. Document Your Setup:
    Create a comprehensive document outlining the steps you've taken to set up your developer environment. Include any configurations, customizations, or troubleshooting steps encountered during the process. 

#Deliverables:
- Document detailing the setup process with step-by-step instructions and screenshots where necessary.
- A GitHub repository containing a sample project initialized with Git and any necessary configuration files (e.g., .gitignore).
- A reflection on the challenges faced during setup and strategies employed to overcome them.

#Submission:
Submit your document and GitHub repository link through the designated platform or email to the instructor by the specified deadline.

#Evaluation Criteria:**
- Completeness and accuracy of setup documentation.
- Effectiveness of version control implementation.
- Appropriateness of tools selected for the project requirements.
- Clarity of reflection on challenges and solutions encountered.
- Adherence to submission guidelines and deadlines.

Note: Feel free to reach out for clarification or assistance with any aspect of the assignment.
