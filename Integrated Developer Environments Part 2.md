Setting Up the PyCharm Integrated Developer Environment
If you have not already installed an integrated developer environment (IDE), please check out this full installation guide and walkthrough here. I would recommend installing the free PyCharm Community Edition IDE for Python application and software development, as well as the Jupyter Notebook. This guide will take you through the steps of setting up an initial project space and configuration for your developer environment.

1. Click the PyCharm Desktop Icon
Once the PyCharm IDE is correctly installed, open the application by clicking on the desktop icon. This should load the application and bring up the IDE in a brief moment.

2. Click the New Project Button
Once the PyCharm IDE finishes loading and is running, it will bring you to a ‘Welcome’ screen where you are able to start your first Python project. Click the New Project button in the top right of the IDE.

3. Select Pure Python in the Left-hand Sidebar
The Pure Python tab will be automatically selected when you start a New Project. If the Pure Python tab is not selected or was clicked off of, reselect it to continue. The default new project environment is set to Virtualenv. Virtualenv is an isolated environment where modules and packages can be installed without affecting the system wide configurations. If you would like to install only a select amount of Python packages or modules, or have sort of constraint on your local machine, leave the new environment setting as the default Virtualenv.

Otherwise, I would recommend using the Anaconda Python distribution. Instructions on how to download and install the Anaconda package and environment manager can be found here.

4. Select a New Environment using Conda
If the Anaconda Python distribution has been correctly installed on your local machine, you will be able to click through different new environment settings. Select New environment using Conda. Conda is short for the Anaconda package and environment manager. You are able to change the name of your project in the top location bar as well as the location of where the project files will be stored. I would recommend leaving the rest of the settings as the default ones provided by the PyCharm IDE.

If you do not have Python 3.9 or another release version installed, please check out this quick and simple Python installation guide.

5. The New Conda Environment will be Created
The newly created Conda environment and python project will begin to initialize. If everything has been correctly installed, the PyCharm IDE will open the new project files.

6. Projects, Files, and the Editor
The project folder and an outline of its file structure will be available in the menu on the left-hand side of the IDE. You can minimize the menu containing the file structure by clicking on the Project tab. Different types of files can be added, deleted, moved, or renamed inside the project and directly from within the IDE. The bottom bar contains different menus which allow you to access the packages currently installed in your project, the python console, different highlighted errors and problems in your project files and code, and a terminal for reading, writing, running files, etc.

Jetbrains the company who developed PyCharm provides extremely useful and comprehensive documentation detailing all the functionality of the IDE. You can read even more about the PyCharm IDE here.

7. Open up the bottom Terminal Tab
Click the terminal tab at the bottom left-hand side of the IDE to open up the local terminal in the IDE. From the terminal you have access to do many different things such as run, create, move, or delete files, as well as install or upgrade modules and packages into the environment. To click into the terminal, mouse over the outlined square next to the name of your project folder: \YourProjectNameHere>

8. Type python main.py in the Terminal
Once you are inside the IDE terminal, type python main.py. This will run the main.py file that was created by the default project settings.

9. The Terminal outputs ‘Hi, PyCharm’
The terminal runs the contents of the main.py file and will output ‘Hi, PyCharm’. The IDE should be correctly setup and configured for running simple Python files and scripts at this point.

Setting Up the Jupyter Notebook
This section will detail how to setup the Jupyter Notebook web application and developer environment through the command line interface (CLI) using Python’s package manager pip.

Python is required to properly install the Jupyter Notebook. If you do not have Python 3.9 or another release version installed, please check out this quick and simple Python installation guide.

Otherwise, I would recommend installing the Anaconda Python distribution which comes with the Jupyter Notebook already built into it. Instructions on how to download and install the Anaconda package and environment manager can be found here.

1. Open up the Command Prompt, a Linux Terminal, or macOS Terminal
Depending on your operating system you will have different command line interface (CLI) applications for accessing, downloading, deleting, etc. files on your local machine. You fill first need to open a CLI application and click into the interface and next to the listed file path: C:\YourFilePathHere>

2. Type pip install notebook in the CLI
Pip is the package manager provided by the Python programming language. It can be used to install, upgrade, downgrade, and uninstall different packages and modules from your local machine. You can check if you have the latest version of pip by typing:

pip install —upgrade pip
Next, to install the Jupyter Notebook using the CLI type:

pip install notebook
Press enter to begin the download and installation process.

3. Downloading the Jupyter Notebook
The Jupyter Notebook files will begin to download and will present a visualization of the installation process in the CLI. A warning is showing due to a newer version of Pip of being available for install as well. This specific warning will not cause any errors or issues with the download process of the Jupyter Notebook. Once the installation has finished you will then be again presented with C:\YourFilePathHere> in the CLI.

4. Type jupyter notebook in the CLI
To run the Jupyter Notebook in your web browser type in the CLI:

jupyter notebook

5. Files, Folders, and .ipynb Notebooks
A list of folders, files, and .ipynb notebooks will be presented in the Jupyter Notebook environment running in the web browser. You are able to click into the different folders to access specific files. You are able to upload additional files from your local machine to the workspace environment as well.

6. Create a New Notebook, File, or Folder
You are able to create new Python 3 notebooks, files, and folders by clicking the New button at the top right-hand side of the workspace environment. You are able to see every current notebook running by clicking the Running tab at the top left-hand side of the workspace environment.

Click New and select Python 3 (pykernel) from under the Notebook section.

7. The .ipynb Notebook
A new .ipynb Python 3 Notebook will have been created where you are able to run code blocks in isolated cells.

Project Jupyter provides a wealth of comprehensive documentation detailing all the functionality of the web application and developer environment. You can read even more about the Jupyter Notebook here.
