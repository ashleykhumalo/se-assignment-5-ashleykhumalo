[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-22041afd0340ce965d47ae6ef1cefeee28c7c493a6346c4f15d667ab976d596c.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-2e0aaae1b6195c2367325f4f02e2d04e9abb55f0b24a779b69b11b9e10269abc.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15270488&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.

  To install Visual Studio Code on Windows 11 we firstly download Visual Studio from its official website on browser which is https://code.visualstudio.com/. After the VSCode has been downloaded we locate the file in the downloaded files and run the file which is 'VSCodeSetup.exe' file by double-clicking to run, we accept the licence agreement.The installer ask to choose  the destination for the installation and the default is usually fine. VSCode then gives optional additional tasks such as creating desktop icon, VSCode being added to PATH automatically.
  
   After selecting any options the next step will be clicking the 'install' button to begin the installation process. VSCode will be launched immediately after installation is complete. After VSCode has been launched the next step will be downloading any required extensions for coding such as Python which is essential. This is done by clicking the extension icon within VSCode and then searching any desired extensions. 

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

   After installing VS Code, the coding environment can be enhanced by installing essintial extensions such as Python, Code Runner, Prettier, Debugger for Chrome, Live Server, ESLint, and GitLens. Furthermore, customizing settings by selecting icon pack and a theme, adjustment of font size , and enabling auto save etc.

   Moreover, coding environment can also be enhanced by configuring Git integration and setting user information via the terminal. To ensure that there is Git integration we navigate 'source control' settings in VS Code and ensure that Git user settings are set and are running by git config --global user.name "Your Name" and git config --global user.email "your.email@example.com" in the terminal.

   Furthermore, we can improve the coding workspace by customizing keyboard shortcuts to fit the desired workflow, enable settings sync across devices, save other workspace specific settings and lastly setting up a preferred integrated terminal shell for a transparent development experience.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   The user interface of  Visual Studio Code (VS Code) consists of Activity Bar, Side Bar, Status Bar, and Editor Group.
   
   The Activity Bar can be found on the left side of the user interface provides access to important  functions Eplorer, Extensions, Run and Debug, Source control, and search , these core function are placed nearby for quick access.

   Moreover, The Side Bar which is located near the Side Bar, displays concise and straight forward views and panels for the selected activity, such as extension management and file nagivation.

   Furthermore, the user interface has the Status Bar which is located on the bottom . The Status Bar shows information about the current workspace, for instance the Git branch, cursor position, file encording and offers quick access to various commands and settings.

   Lastly, there is the central Editor Group which is a writing part and code editing part, it supports multiple files and the view can be split into halfs with a side-by-side view for editing. 


4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

   Command Palette in VS Code is a feature that is powerful which provides quick access to various range of commands and settings within the editor. This feature can be accessed by clicking 'Ctrl+Shift+P' at the same time (or Cmd+Shift+P on macOS). This can also be done by clicking 'view' and then clicking 'Command Palette' from the menu.

   Below are some of the examples of common tasks that can be performed by the Command Palette:

   - Installing Extensions by typing '>Extensions: Install Extensions' to search the extension and install it at the same time directly from marketplace.
   - Opening the files through typing '>Open File' to open any file by name quickly.
   - Git Commands running by typing commands such as '>Git: Clone' to clone repositories or '>Git: Commit' to commit changes.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

  Extensions is Visual Studio Code (VSC) enhance the development environment and at the same time customize it and this is done with additional functionalities and features. To install and manage extensions, users open the Extension view which is the icon on the Activity Bar on the left side of the user interface or open through pressing the buttons 'Ctrl+Shift+X' at the same time, in order to search for specific extensions, and using the options provided of installing and managing.

  Essential extensions for web development include Prettier, Live Server, Debugger for Chrome, HTML Snippets, ESLint, React, Vue.js, GitLens, CSS Peek, and Path Intellisence. All these extensions enhance productivity in software development by providing syntax highlighting, snippets, code formatting, version control insights, live server capabilities, and real-time linting.

6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

   To open and user the integrated terminal in Visual Studio Code (VS Code) we press 'Ctrl+' or simply click the 'View > Terminal' from the menu. The terminal opens at the bottom of the central Editors Group . Inside the terminal on the top part there is a plus sign button that has a dropdown options of different terminals, the plus sign is placed at the top right corner of the panel. When you have clicked the plus sign you can choose any of the desired terminals of options (e.g Git bash, Command Prompt, Powershell). These terminals all work the same way and you can type and execute any command and it will come out the same.

   Advantages of using the integrated terminal:

   - The terminal can open directly in the context of the workspace opened currently and there is no need to open it manually from settings.
   - It provides a seamless workflow which allows the user to run command tasks without leaving VS Code.
   - It offers customization of the integrated terminal's behavior and appearance through the VS Code settings, making it consistent with coding environment.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

  You can create files and folders in Visual Studio Code (VS Code) by right clicking the explorer view or by making use of the Command Palette typing (Ctrl+Shift+P). Furthermore, files will be opened by double-clicking in the Explorer, using the Command Palette typing this command (Ctrl+P) or by dragging them inside the central Editors Group.Moreover, the folders can be opened via 'File > Open Folder' or by using the Command Palette. 

  In order to delete or rename the files and folders we right- click and this works as for dragging and dropping to move them as well. To locate efficiently using Quick Open (Ctrl+P),  Keyboard shortcuts (Ctrl+Tab to switch files), to Navigate history (Alt+Left/Right), to Search (Ctrl+Shift+F),  and to Explorer view (Ctrl+Shift+E).

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   Users can customize settings in Visual Studio Code (VS Code) by accessing ('File > Preferences > Settings or pressing Ctrl+,'). In order to change the theme of the interface users can simply the Palette by clicking ('Ctrl+Shift+P'). Users should then type Preferences: Color Theme, and select a theme. To adjust and change the font size users should search (font size) in settings and modify ('Editor: Font Size'). In order to change the keybindings, users should navigate to File > Preferences > Keyboard Shortcuts or press (Ctrl+K Ctrl+S), and search the command that is desired, assign new key combination by clicking the plus icon or on the existing keybinding.

9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   Steps to Setting up and Starting Debugging in VS Code:

   1. Installation of necessary extensions
   - The first step is ensuring that necesaary language extensions are installed such as Python, if its not installed we can do this by  navigating the Extensions view (Ctrl+Shift+X) and  install the Python extension.

   2. Opening project
   - Next step is opening the project folder in Visual Studio Code (VS Code) by selecting (File > Open Folder) and locating to your project directory.

   3. Creating a simple program
   - The next part is creating a new file (e.g., app.py for Python) after created a code with errors.

   4. Open the debug view
   - To debug the code with errors we click the Debug icon in the Activity Bar or press ('Ctrl+Shift+D').

   5. Debug Cofiguration creation
   - In this step we click the Gear icon at the top part of the Debug view and we select ('Add configuration').
   - The next step is then choosing the appropriate for the users project by pressing ('e.g., Python: Current File').

   6. Setting Breakpoints
   - On the left margin located to the line numbers is where the user should click in their code in order to set breakpoints.

   7. Start Debugging
   - This step is when the user click the green plap button or press 'F5' to initialize debugging, in the Debug view.

      Key Debugging feature:

      1. Breakpoints
      - To set up breakpoints we click inside the margin that is located next to the line numbers and the debugger will pause execution at these points.

      2. Call Stack
      - To see the order and sequences of functions calls that led to current point of execution user views the call stack.

      3. Debug Console
      - In order to execute and evaluate code in the current debug context user use the Debug Console.

      4. Step Controls
      - For the user to navigate through the code execution line by line, user should use the Stepping Controls (Step Over, Step Into, Step Out).

      5. Conditional Breakpoints
      - To add a condition user should right click on a breakpoint and select (Edit Breakpoin) and this will make the breakpoint trigger only when specific criteria are met.

      6. Variable Inspection
      - In order to view or see current variables user should hover over variables in the Variable Panel.

      7. Watch Variables
      - User should add variables to watch in order to see their current values as the user step down through the code .


10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    Integration with VS Code for Version Control

    1. Git Installation
    - The first step is to ensure that Git is installed and if not then it should be downloaded on (https://git-scm.com/) and follow the steps and instructions of the installation process.

    2. Opening of Project in VS Code
    - The next step is selecting the 'File > Open Folder' to locate the project folder and then navigating to the project directory.

    Repository Initialization

    1. Git repository initializing
    - User click the Source Control icon in the Activity Bar or using the commands (Ctrl+Shift+G), to open Source Control.

    - To create a Git folder in project directory user should  click the (Initialize Repository) and this makes it a Git repository.

    Making Commits

    1. Stage Changes
    - There is a list of changes in the Source Control view (files that have been added, modified, and deleted).
    - To change the files user should hover over the files and click the plus icon ('+') next to the files or click the ('Stage All Changes') button.

    Commit Changes
    - At the top of the Source Control view user should type or enter a commit message in the message box.
    - User should click the checkmark button which is a green tick ('✔️') or alternatively press (Ctrl+Enter) to commit the staged changes.

    Pushing the changes made to Github
   
    1. Sign in to Github
    - If the user have never signed in, VS Code will prompt the user to sign in by following the prompts to authenticate.

    2. Add Remote Repository
    - In the next step the user should open the terminal in VS Code by simply going to the Activity Bar> Terminal> New Terminal or by pressing ('Ctrl+').
    - User should add Github Repository as remote through running the following in the terminal:
    (git remote add origin https://github.com/your-username/your-repo.git).
    - The user should his/her name name where it is 'your-name' and should put the repository name on 'your-repo'.

    3. Push Changes
    - User can push the committed changes to Github by clicking the ellipsis which is found in the Source Control view and then selecting 'push'.
    - User can also use the terminal by simply typing the following:
    (git push -u origin master)
    - This command will push changes in user's Git repository in 'master' branch.


    Referencing

    Visual Studio Code and Git learnt from class sessions 
    Additional Knowledge of VS Code learnt from YouTube- https://www.youtube.com/watch?v=VqCgcpAypFQ
    More knowledge about VS Code and Git learnt from LMS 

     Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

