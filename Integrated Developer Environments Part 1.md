# Integrated Developer Environments Part 1
Instructions on Installing Your Developer Environment

## What is an Integrated Developer Environment (IDE)?
An Integrated Developer Environment (IDE) is an application which provides comprehensive programming tools for software development using a graphical user interface (GUI). IDE’s usually provide a source code editor, build automation, and a debugger. The editor helps to assist you in writing programs by including features such as syntax highlighting, code auto-completion, and error handling. The debugger will graphically display the location of bugs or error in the code. A console or terminal is normally included to interact directly with the environment and files.

A popular IDE for Python programming with great plugins and a multitude of useful features is PyCharm. Other great developer environment options include the Jupyter Notebook, Visual Studio Code, and cloud environments such as Google Colaboratory (Colab) or Paperspace Gradient. Installations instructions for each of the IDEs is provided in detail below.

For Artificial Intelligence and Deep Learning applications you will need access to a system which has a GPU:

1. If you are in possession of a NVIDIA or AMD GPU you will be able to enable workspace access on your chosen local IDE or hosted Jupyter Notebook.

2. If you do not have access to a local GPU enabled workspace then you will need to either use one of the free cloud GPU enabled provided by Google Colab or Paperspace Gradient.

## PyCharm
Link to Install PyCharm IDE here.

PyCharm is a cross-platform IDE for Windows, macOS, and Linux operating systems providing a wide array of features such as intelligent code completion, error checking, and simple project file navigation. The PyCharm IDE helps to assist in writing clear, concise and maintainable code allowing for quality control with test assistance, PEP8 checks, and refactoring. PyCharm community edition provides substantial support for python programming development. I have provided instructions on installation as well as system requirements and a list of features available with PyCharm below.

#### Syntax Highlighting
Predefined color themes allow you to easily read highlighted Python code syntax.

#### Auto-Indentation and Code Formatting
Automatic indents are inserted on new lines with project compliant code formatting, built-in PEP-8 for Python, and code-style settings.

#### Code Auto Generation and Completion
Code auto-generation and completion allows for quick-fixes and code matching verification including keywords, classes, and variables. PyCharm will suggest the most appropriate and context-aware solution.

#### Visual and Inline Debugging
PyCharm provides a comprehensive python debugging GUI simplifying the code debugging process through visual integration. Live inline debugging information is shown directly in the editor with variable value uses located next to source code.

#### Conda and Jupyter Notebook Integration
Allows for separate Conda and Jupyter Notebook environment integration for each PyCharm project. Combines the Jupyter Notebook with additional features such as code auto-completion, error checking, etc.

#### Plugins
Plugins provide support for integration with different frameworks, developer tools and editor customizations.

#### Minimum System Requirements
RAM - 4 GB

CPU - Any modern one

Disk Space - 3.5 GB

Monitor Resolution - 1024x768

Operating System - Windows 8 or later, macOS 10.13 or later, GNOME, KDE, or Unity DE supported Linux distributions

### 1. Choose Your Operating System
Select the operating system which is currently installed on your computer or laptop. There will be a separate guide on how to install Linux as a dual boot system.


### 2. Click the Download Button under Community
The download will take about 5 to 15 seconds before it completes. There is also a paid professional and student version of the PyCharm IDE. If you have access to a .edu email you can register for the professional version for free and renew every year. The professional version allows you to build and integrate end-to-end applications. The community version is sufficient for almost all python use cases.


### 3. Click the Downloaded pycharm-community.exe file
Allow the program to make changes to your computer. Run as an administrator if necessary. The executable file will bring up the PyCharm Community Edition Setup Installer.


### 4. Click Next on the PyCharm Community Edition Setup Installer
This will bring you to the install location setup.


### 5. Choose the Installation Location folder for the PyCharm IDE
Select the folder that you wish to install the IDE. You can leave this as the default file path which it recommends and click next to move onto more installation options. You will most likely not need to change the location unless you feel that it is necessary to place it somewhere else.


### 6. Select the Installation Options for the PyCharm IDE
I would recommend selecting the options for a desktop shortcut icon, creating automatically recognized and associated python files, and adding and updating to system PATH. (You will have to restart your computer after the entire installation process is complete if you add the “bin” folder to PATH.) You may choose to not select any of the available options and can change your configurations in the IDE at a later point.


### 7. Choose the Start Menu Folder for the PyCharm IDE
You can choose to change the folder name or just leave it as the default JetBrains. Click the install button.


### 8. Click Finish After the Installation Process Completes
You will have the option to launch the PyCharm IDE, or can click finish to complete the installation process and access it later. If you still need more help click here.


## Jupyter Notebook
Link to Install Jupyter Notebook here.

Jupyter Notebook is a server-client application, which allows you to run and edit a workspace notebooks through your web browser. It can be run locally without Internet access, or accessed through the Internet by installation on a remote server. Jupyter Notebooks consist of a kernel and a dashboard. The kernel is available for multiple different programming languages which run the user’s code. The dashboard provides access to notebook documents that you created. You can reopen previous documents as well as manage running kernels.

### Prerequisite: Python
Python is required to install the Jupyter Notebook.

### Installing the Jupyter Notebook with Anaconda
The Anaconda distribution allows for an easy installation process of Python and the Jupyter Notebook. It also includes multiple other common packages for machine learning, scientific computing and data science. Below are the installation steps provided by the documentation from the Jupyter website:

Use the following installation steps:

1. Download Anaconda. We recommend downloading Anaconda’s latest Python 3 version (currently Python 3.7).

2. Install the version of Anaconda which you downloaded, following the instructions on the download page.

3. Congratulations, you have installed Jupyter Notebook. To run the notebook:

```
jupyter notebook 
```
### Installing the Jupyter Notebook with pip
You may also install the Jupyter Notebook using Python’s package manager pip, through a command line interface such as command on prompt on Windows. The installation requires at least Python 3.3. Below are the instructions for installation:

Check for the latest pip:

```pip3 install --upgrade pip ```

Install the Jupyter Notebook using:

```pip3 install jupyter```

## Visual Studio Code
Link to Install Visual Studio Code here.

Visual Studio Code is a source code editor available for Windows, macOS and Linux with support for JavaScript, TypeScript and Node.js. Extensions can be added to provide support for additional programming languages such as C++, Java, Python, and Go. Visual Studio Code can be used as an alternative to PyCharm if you prefer the functionality and look of the developer environment. Similar to PyCharm, Visual Studio Code has a range of features which allow you to customize your developer environment. Some features include: syntax highlighting, code auto-complete, visual debugger, built-in Git commands, extensions for new languages, and themes. Instructions for how to install Visual Studio Code are below.

### 1. Choose Your Operating System
Select the operating system which is currently installed on your computer or laptop, and click the blue button below it to automatically start the download.


### 2. Click the Downloaded VSCodeUserSetup.exe file
Allow the program to make changes to your computer. Run as an administrator if necessary. The executable file will bring up the Microsoft Visual Studio Code Installer.


### 3. Accept the License Agreement
Click next after accepting the license agreement.


### 4. Select the Installation Options for the PyCharm IDE
I would recommend selecting the options for a desktop shortcut icon and adding to system PATH. (You will have to restart your computer after the entire installation process is complete if you add the “bin” folder to PATH.) You may choose to not select any of the available options and can change your configurations in the IDE at a later point.


### 5. Click the Install Button
If you need more information click here.



## Free GPU Enabled Cloud Developer Environments
If you do not have access to a local GPU enabled workspace there are two free cloud options, Google Colab and Paperspace Gradient, which both provide Jupyter notebooks with free GPUs. There are also paid options available which allow for access to better GPUs and CPUs in the cloud workspaces. Below is a comparison of the hardware available within the two free cloud environments.

### Google Colab
Sign up for Google Colab here.

You will need a Google account or email to sign up for Google Colab. You can mount your Google drive directly to your Colab environment to access files from there.

#### Colab Hardware
GPU - Nvidia K80s, T4s, P4s or P100s

GPU RAM - Up to 16 GB

Choose GPU - No

CPU/Cores - 2x 2.30GHz

RAM - 12 GB to 26.75 GB

Storage - 40 GB

Persistent Storage - No

Runtime - 12 hours

Sharing - Private and Public

### Paperspace Gradient
Sign up for Paperspace Gradient here.

You can sign up for Paperspace Gradient with a GitHub account, Google account or email.

#### Gradient Hardware
GPU - Nvidia M4000 or P5000

GPU RAM - Up to 16 GB

Choose GPU - Yes

CPU/Cores - 8x vCPU

RAM - 30 GB

Storage - 5 GB

Persistent Storage - Yes

Runtime - 6 hours

Sharing - Public

