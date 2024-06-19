[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/vbnbTt5m)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15292890&assignment_repo_type=AssignmentRepo)
# Dev_Setup
Setup Development Environment

#Assignment: Setting Up Your Developer Environment

#Objective:
This assignment aims to familiarize you with the tools and configurations necessary to set up an efficient developer environment for software engineering projects. Completing this assignment will give you the skills required to set up a robust and productive workspace conducive to coding, debugging, version control, and collaboration.

#Tasks:

1. Select Your Operating System (OS):
   Choose an operating system that best suits your preferences and project requirements. Download and Install Windows 11. https://www.microsoft.com/software-download/windows11

   a. Prefered OS is Windows 11

   b.Step to Install windows 11
     i) Download the media creation tool
        - Visit the (Windows 11 download page)[ https://www.microsoft.com/software-download/windows11}
        - Download the media tool.
    ii) Create a bootable USB drive or ISO File
        -Run the Media Media Creation tool
        -Follow the prompts to create a bootable USB drive minimum (8GB) or ISO file.
   iii)  Install windows 11
        -Insert the USB drive into computer
        -Restart the computer
        -Access the boot menu(usually by continuasly hitting F2,F12)
        -Select the USB drive as the boot device and press enter
        -Follow the installation prompts to complete the Installation of windows 11
        -After installation, the Windows 11 start-up screen will appear. Log in as you normally would and start exploring the new features of Windows 11  
   

2. Install a Text Editor or Integrated Development Environment (IDE):
   Select and install a text editor or IDE suitable for your programming languages and workflow. Download and Install Visual Studio Code. https://code.visualstudio.com/Download

 
Steps to Install PlatformIO IDE.
i) Download and install official Microsoft Visual Studio Code (https://code.visualstudio.com/Download) PlatformIO IDE is built on top of it
ii) Open VSCode Package Manager
iii) Search for the official platformio ide extension
iv) Install PlatformIO IDE.

3. Set Up Version Control System:
   Install Git and configure it on your local machine. Create a GitHub account for hosting your repositories. Initialize a Git repository for your project and make your first commit. https://github.com

   Steps to Install Git and Configure

  i) Download and install the latest version of Git.

     Note: Most Chrome OS devices from 2020 onwards now have a built-in Linux environment, which includes Git. To enable it, go to the Launcher, search for Linux, and click Turn on.
     If you are using an older Chrome OS device, another method is required:
     Install a terminal emulator such as Termux from the Google Play Store on your Chrome OS device.
     From the terminal emulator that you installed, install Git. For example, in Termux, enter apt install git and then type y when prompted.
 ii) Set your username in Git.
 iii) Set your commit email address in Git.

4. Install Necessary Programming Languages and Runtimes:
  Instal Python from http://wwww.python.org programming language required for your project and install their respective compilers, interpreters, or runtimes. Ensure you have the necessary tools to build and execute your code.

  Step 1: Visit the Python Website and Navigate to the Downloads Section
  First and foremost step is to open a browser and type Python Download or paste link (https://www.python.org/downloads/)
  Step 2: Choose the Python Version
  Step 3: Download the Python Installer
  Once the download is complete, run the installer program. On Windows, it will typically be a .exe file, on macOS, it will be a .pkg file, and on Linux, it will be a .tar.gz file.

Click on the version you want to download. – Python 3.12.3 (the latest stable release as of now is Python 3.12.3)


5. Install Package Managers:
   If applicable, install package managers like pip (Python).

   Method 1: Install PIP on Windows Using get-pip.py
   Step 1: Download PIP get-pip.py. Before installing PIP, download the get-pip.py file. ...
   Step 2: Installing PIP on Windows. To install PIP, run the following Python command: python get-pip.py. ...
   Step 3: Verify Installation. ...
   Step 4: Add Pip to Path. ...
   Step 5: Configuration.

6. Configure a Database (MySQL):
   Download and install MySQL database. https://dev.mysql.com/downloads/windows/installer/5.7.html

   Steps to Download 
     Step 1: Go to the official website of MySQL and download the community server edition software. Here, you will see the option to choose the Operating System, such as Windows.

     Step 2: Next, there are two options available to download the setup. Choose the version number for the MySQL community server, which you want. If you have good internet connectivity, then choose the mysql-installer-web-community. Otherwise, choose the other one.

      Steps to Install
      Step 1: After downloading the setup, unzip it anywhere and double click the MSI installer .exe file. It will give the following screen:

      Step 2: In the next wizard, choose the Setup Type. There are several types available, and you need to choose the appropriate option to install MySQL product and features. Here, we are going to select the Full option and click on the Next button.

      Step 3: Once we click on the Next button, it may give information about some features that may fail to install on your system due to a lack of requirements. We can resolve them by clicking on the Execute button that will install all requirements automatically or can skip them. Now, click on the Next button.

      Step 4: In the next wizard, we will see a dialog box that asks for our confirmation of a few products not getting installed. Here, we have to click on the Yes button.

      Step 5: Once we click on the Execute button, it will download and install all the products. After completing the installation, click on the Next button.

      Step 6: In the next wizard, we need to configure the MySQL Server and Router. Here, I am not going to configure the Router because there is no need to use it with MySQL. We are going to show you how to configure the server only. Now, click on the Next button.

      Step 7: As soon as you will click on the Next button, you can see the screen below. Here, we have to configure the MySQL Server. Now, choose the Standalone MySQL Server/Classic MySQL Replication option and click on Next. Here, you can also choose the InnoDB Cluster based on your needs.

      Step 8: In the next screen, the system will ask you to choose the Config Type and other connectivity options. Here, we are going to select the Config Type as 'Development Machine' and Connectivity as TCP/IP, and Port Number is 3306, then click on Next.

      Step 9: Now, select the Authentication Method and click on Next. Here, I am going to select the first option.

7. Set Up Development Environments and Virtualization (Optional):
   Consider using virtualization tools like Docker or virtual machines to isolate project dependencies and ensure consistent environments across different machines.

8. Explore Extensions and Plugins:
   Explore available extensions, plugins, and add-ons for your chosen text editor or IDE to enhance functionality, such as syntax highlighting, linting, code formatting, and version control integration.

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
