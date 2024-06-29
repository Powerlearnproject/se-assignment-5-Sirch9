[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15256287&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

 Questions:

1. Installation of VS Code:
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   * Download the Visual Studio Code installer for Windows.
   * Once it is downloaded, run the installer (VSCodeUserSetup-{version}.exe).
   * By default, VS Code is installed under C:\Users\ {Username}\AppData\Local\Programs\Microsoft VS Code.
   - Prerequisites
   * Operating System: Windows 11(VS Code is compatible with both 32-bit and 64-bit version)
   * Disk Space: Approximately 200 MB of free disk space for the installation.

2. First-time Setup:
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.
   * Settings:
    - Font and Theme: Set your preferred font and theme by navigating to File > Preferences > Settings.
      You can search for "font" and "theme" to customize these options.
    - Indentation: Adjust the tab size and indentation to match your coding style. Search for "tab size" 
      and "indentation" in the settings to modify these preferences.
    - Auto Save: Enable auto save to ensure that your changes are automatically saved. Search for 
     "autosave"  in the settings and choose your preferred option.
    - Line Numbers: Display line numbers for easier navigation within your code. Search for "line numbers" 
      in the settings and enable this feature.
    - Extensions: Install essential extensions for your programming language or framework to enhance your 
      coding experience.

   * Extensions:
    - Bracket Pair Colorizer: This extension helps to identify matching brackets with colors, making it 
      easier to navigate complex code.
    - ESLint: If you are working with JavaScript, ESLint can help you identify and fix problems in your code.
    - Prettier: Prettier is a code formatter that can automatically format your code to maintain a consistent
      style.
    - GitLens: GitLens provides valuable insights into your Git repository directly within VS Code, making it
      easier to understand code authorship and history.
    - Live Server: For web development, Live Server can launch a development local server with live reload
      feature for static and dynamic pages.

3. User Interface Overview:
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

   - Activity Bar
   * The Activity Bar is located on the far left side of the VS Code window. It provides quick access to  
     various views and functionalities within VS Code.
     - Components:
        * Explorer: Allows navigation through files and folders in your project.
        * Search: Provides tools for searching across files.
        * Source Control: Integrates with version control systems like Git for managing code changes.
        * Run and Debug: Facilitates running and debugging applications directly from VS Code.
        * Extensions: Manages VS Code extensions, enabling you to add new features and functionalities.
   
   - Side Bar
   * The Side Bar is adjacent to the Activity Bar and contains additional panels and views related to the 
     current project or file.
      - Components:
        * File Explorer: Shows the directory structure of the current workspace for easy navigation.
        * Search: Provides tools for searching within the current file or across the entire project.
        * Git Integration: Shows Git repository status and allows for version control operations.
        * Extensions: Lists installed extensions and allows for managing them.
        * Debugging: Displays debugging-related information and controls.

   - Editor Group
   * The Editor Group is the main area where you edit and work with files
      - Components
        * Tabs: Each open file is represented as a tab within the Editor Group, allowing you to easily switch
          between files.
        * Active Editor: Displays the content of the currently active file for editing.
        * Split Editors: Allows you to split the Editor Group horizontally or vertically to view and edit
          multiple files simultaneously.

   - Status Bar 
   * The Status Bar is located at the bottom of the VS Code window and provides information about the current
     state of the editor and project.
       - Components
        * Language Mode: Displays the programming language mode of the current file.
        * Line Endings: Indicates the line ending format used in the current file.
        * Encoding: Shows the character encoding of the current file.
        * Git Branch: Displays the current Git branch name if the project is under version control.
        * Notifications: Shows information and notifications about tasks, errors, and warnings.

4. Command Palette:
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks    that can be performed using the Command Palette.
      * The Command Palette provides access to many commands. You can run editor commands, open files, search
        for symbols, and see a quick outline of a file, all using the same interactive window. Here are a few tips: Ctrl+P enables you to navigate to any file or symbol by typing its name.

5. Extensions in VS Code:
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.
     - Roles of extensions
     * Enhanced Functionality
     * Customization
     * Community-Driven

     - Finding Extensions
       * In VS Code, click on the Extensions icon in the Activity Bar (or press Ctrl+Shift+X).
       * This view allows searching for extensions by name or category. It includes ratings, reviews, and download counts to help users choose.

     - Installing Extensions
       * Once you find an extension, click the Install button next to it in the Extensions view
       * Some extensions may require additional dependencies or permissions, which will be prompted during 
         installation

     - Managing Extensions
       * Extensions can be enabled or disabled easily from the Extensions view.
       * VS Code notifies users when updates are available for installed extensions. Updates can be applied with a single click
       * Users can uninstall extensions they no longer need directly from the Extensions view.

     - Essential extensions for web development.
       * Prettier - Code formatter
       * Live Server
       * HTML CSS Support


6. Integrated Terminal:
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?
   * To open the integrated terminal in VS Code, you can use the following steps:
       - Press Ctrl + ` (backtick) on Windows or Linux, or Cmd + ` on macOS.
         Alternatively, you can go to the View menu, then select Terminal.
         Once the integrated terminal is open, you can use it just like any other terminal.
         You can run commands, install packages, and manage your project without leaving the VS Code interface.

   * Advantages of using the integrated terminal compared to an external terminal include:

       - Seamless integration: It's conveniently located within the VS Code interface, allowing you to work without 
         switching between   different applications.
       - Workspace awareness: The integrated terminal automatically starts in the root of your workspace, making it easier to run 
         commands specific to your project.
       - Customization: You can customize the terminal's appearance, behavior, and shortcuts to suit your preferences.
       - Split panes: You can split the terminal into multiple panes, allowing you to see different outputs at the same time.
         Using the integrated terminal can streamline your workflow and improve productivity by keeping everything in one place.

7. File and Folder Management:
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

       * To create a new file in VS Code, you can use the following steps:

           - Click on the Explorer icon in the Activity Bar on the side of the window.
             Right-click on the folder where you want to create the file.
             Select "New File" from the context menu and give the file a name.
             To open an existing file or folder in VS Code:

           - Click on the "File" menu at the top of the window.
             Select "Open..." and navigate to the file or folder you want to open.
             Managing Files and Folders
             To manage files and folders in VS Code, you can use the following options:
             Rename: Right-click on the file or folder in the Explorer and select "Rename" from the context menu.
             Delete: Right-click on the file or folder in the Explorer and select "Delete" from the context menu.
             Move: You can drag and drop files and folders within the Explorer to move them to a different location.
             Navigating Between Files and Directories
             To navigate between different files and directories efficiently in VS Code, you can use the following shortcuts:

           - Switching Between Open Files: Use Ctrl + Tab to cycle through open files.
             Go to File: Press Ctrl + P to open the Quick Open menu, then start typing the name of the file you want to open.
             Explorer Navigation: Use the Explorer view to navigate between different files and folders by clicking on them.
             Additionally, you can use the built-in search functionality (Ctrl + F) to quickly find and open files within your project.

8. Settings and Preferences:
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   * Users can find and customize settings in VS Code in the following ways:

Settings Location:
   - Access settings by navigating to `File -> Preferences -> Settings` (or press `Ctrl+,`).
   - Alternatively, use `Ctrl+Shift+P` to open the command palette, then search for and select `Preferences: Open Settings (JSON)` or `Preferences: Open Settings (UI)`.

Changing Themes:
   - To change the theme, go to `File -> Preferences -> Color Theme` and select a theme from the list.
   - Custom themes can be installed from the VS Code Marketplace and activated in the same way.

Adjusting Font Size:
   - Modify the font size by going to `File -> Preferences -> Settings` (or press `Ctrl+,`), then search for `editor.fontSize` in the search bar.
   - Adjust the value to change the font size. For example, `"editor.fontSize": 14`.

Customizing Key Bindings:
   - Customize key bindings by opening the command palette with `Ctrl+Shift+P`, then searching for and selecting `Preferences: Open Keyboard Shortcuts`.
   - Use the `keybindings.json` file to define custom key bindings or modify existing ones.


9. Debugging in VS Code:
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?
    
     * Debugger extensions
       VS Code has built-in debugging support for the Node.js runtime and can debug JavaScript, TypeScript, or any other language that gets transpiled to JavaScript.

       For debugging other languages and runtimes (including PHP, Ruby, Go, C#, Python, C++, PowerShell and many others), look for Debuggers extensions in the VS Code Marketplace or select Install Additional Debuggers in the top-level Run menu.

       Below are several popular extensions which include debugging support:

10. Using Source Control:
    - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

    * Open VS Code, initialize Git repository (`git init`), stage changes (`git add .`), commit (`git commit -m "Message"`), add remote (`git remote add origin <remote_repository_URL>`), push changes (`git push -u origin main`).



    * References 
        - https://www.studocu.com/
        - https://chatgpt.com/
        - https://code.visualstudio.com/

 Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

