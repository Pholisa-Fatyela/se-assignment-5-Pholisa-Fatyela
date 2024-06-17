[![Review Assignment Due Date](https://classroom.github.com/assets/deadline-readme-button-24ddc0f5d75046c5622901739e7c5dd533143b0c8e959d652212380cedb1ea36.svg)](https://classroom.github.com/a/XoLGRbHq)
[![Open in Visual Studio Code](https://classroom.github.com/assets/open-in-vscode-718a45dd9cf7e7f842a935f5ebbe5719a5e09af4491e668f4dbf3b35d5cca122.svg)](https://classroom.github.com/online_ide?assignment_repo_id=15244946&assignment_repo_type=AssignmentRepo)
# SE-Assignment-5
Installation and Navigation of Visual Studio Code (VS Code)
 Instructions:
Answer the following questions based on your understanding of the installation and navigation of Visual Studio Code (VS Code). Provide detailed explanations and examples where appropriate.

# **Questions:**

## **1. Installation of VS Code:**
   - Describe the steps to download and install Visual Studio Code on Windows 11 operating system. Include any prerequisites that might be needed.
   - To install Visual Studio Code on Windows 11, ensure your system meets the requirements, download the installer from the official website, follow the installation steps, and optionally configure additional settings and software.

      1. Check System Requirements:

         Ensure your system meets the minimum requirements for Visual Studio Code (VS Code):
         Windows 11 (or compatible version)
         64-bit processor
         1.6 GHz or faster
         2 GB RAM (4 GB recommended)
         800 MB to 1 GB of available disk space

      2. Download VS Code:

         Go to the official Visual Studio Code download page.
         Click the download button for Windows, which will download the installer (usually VSCodeUserSetup-x64-<version>.exe).

      3. Run the Installer:

         Locate the downloaded .exe file and double-click it to start the installation process.
         If prompted by the User Account Control (UAC), click "Yes" to allow the installer to make changes to your device.

      4. Setup Installation Preferences:

         Read and accept the license agreement.
         Choose the installation location or accept the default path.
         Select additional tasks (optional):
         Create a desktop icon
         Add "Open with Code" action to Windows Explorer file context menu
         Add "Open with Code" action to Windows Explorer directory context menu
         Register Code as an editor for supported file types
         Add to PATH (important for command line usage)

      5. Install VS Code:

         Click "Install" to begin the installation.
         Wait for the installation process to complete.
      
      6. Launch VS Code:

         After installation, you can launch VS Code by:
         Checking the "Launch Visual Studio Code" box in the installer’s final screen and clicking "Finish".
         Using the desktop shortcut, if created.
         Searching for "Visual Studio Code" in the Start menu.
      
      7. Complete Initial Setup:

         On first launch, you may see a welcome page with options to customize settings, install extensions, or start a new project.
         Sign in with a Microsoft or GitHub account if needed for syncing settings and extensions.

## 2. **First-time Setup:**
   - After installing VS Code, what initial configurations and settings should be adjusted for an optimal coding environment? Mention any important settings or extensions.

      After installing Visual Studio Code (VS Code) on Windows 11, there are several initial configurations and settings you can adjust to optimize your coding environment. Here are the key steps to follow:

      1. **Update VS Code:**
         - Make sure you have the latest version of VS Code. Go to `Help` > `Check for Updates` to ensure you’re on the latest release.
      - Adjust `Editor: Font Size` and `Editor: Font Family`.

      2. **Configure Theme and Appearance:**
         - **Theme:** Choose a theme that suits your preference for better readability.
         - Go to `File` > `Preferences` > `Color Theme`, or use the shortcut `Ctrl + K` followed by `Ctrl + T`.
         - You can install additional themes from the Marketplace.
         - **Font and Size:** Set your preferred font family and size.
         - Go to `File` > `Preferences` > `Settings`, then search for `Font`.

      3. **Customize Editor Settings:**
         - **Line Numbers:** Toggle visibility via `View` > `Show Line Numbers`.
         - **Word Wrap:** Enable for better viewing of long lines.
         - Go to `File` > `Preferences` > `Settings`, search for `Word Wrap`, and set it to `on`.
         - **Auto Save:** Configure auto-save to reduce the risk of data loss.
         - Search for `Auto Save` in Settings and set the interval or on focus change.
         - **Tab and Indentation:** Customize tab size and indentation settings.
         - In `Settings`, search for `Tab Size` and `Insert Spaces`.

      4. **Set Up Integrated Terminal:**
         - Open the terminal with `Ctrl + ` (backtick).
         - Customize the shell (PowerShell, Command Prompt, Git Bash, or WSL) by clicking the dropdown menu in the terminal pane.
         - Go to `File` > `Preferences` > `Settings` and search for `Integrated Terminal Shell` to set the default shell.

      5. **Install Essential Extensions:**
         - **Language Support:** Install extensions for languages you’ll be coding in (e.g., Python, JavaScript, Java, C#).
         - **Code Formatters:** Tools like Prettier or ESLint for JavaScript, Black for Python, etc., to maintain consistent code style.
         - **Version Control:** Extensions for Git integration, like GitLens, enhance the built-in Git functionality.
         - **Debugging:** Language-specific debugging tools (e.g., Python extension includes debugging features).
         - **Snippet Tools:** Extensions like `ES7 React/Redux/GraphQL/React-Native snippets` for quicker code scaffolding.
         - **Remote Development:** If working in different environments, `Remote - WSL`, `Remote - SSH`, or `Remote - Containers` extensions are valuable.
         - **Live Share:** For real-time collaboration on code with others.

      6. **Configure Git Integration:**
         - Ensure Git is installed and available in your PATH.
         - Go to `File` > `Preferences` > `Settings` and search for `Git Path` if you need to set the specific path.
         - Configure global Git settings via the command line (`git config --global user.name "Your Name"` and `git config --global user.email "you@example.com"`).

      7. **Set Up Workspaces and Projects:**
         - Use Workspaces for managing multi-folder projects.
         - Open a folder or create a new workspace with `File` > `Add Folder to Workspace` or `File` > `Save Workspace As`.
         - Customize workspace settings for each project.

      8. **Adjust Keybindings:**
         - Modify keybindings to suit your workflow by going to `File` > `Preferences` > `Keyboard Shortcuts`.
         - You can search for specific commands and set custom shortcuts.

      9. **Sync Settings:**
         - Use the built-in Settings Sync to synchronize your settings, extensions, and keybindings across different devices.
         - Go to `File` > `Preferences` > `Settings Sync`, sign in with your Microsoft or GitHub account, and enable sync.

      10. **Explore Additional Settings:**
         - **Editor Configurations:** Adjust settings like minimap visibility, cursor style, and bracket matching.
         - **File Associations:** Customize how different file types are opened or handled in VS Code.
         - **Extensions Settings:** Each installed extension might have its own configurable settings under `File` > `Preferences` > `Settings`.

      By following these steps, you’ll create a more efficient and personalized coding environment in VS Code tailored to your development needs.

    

## **3. User Interface Overview:**
   - Explain the main components of the VS Code user interface. Identify and describe the purpose of the Activity Bar, Side Bar, Editor Group, and Status Bar.

      - Activity Bar: Quick access to core VS Code functionalities and extensions.
      - Side Bar: Displays detailed panels for files, search, source control, debugging, and extensions.
      - Editor Group: Main area for viewing and editing code with support for multiple files and split views.
      - Status Bar: Provides real-time information and controls related to the current workspace and editor status.
      
      These components together form a cohesive and flexible environment that supports efficient coding, debugging, and project management in VS Code.

## **04. Command Palette:**
   - What is the Command Palette in VS Code, and how can it be accessed? Provide examples of common tasks that can be performed using the Command Palette.

      - The Command Palette is an essential feature in VS Code that enhances productivity by providing a centralized and efficient way to access and execute commands. It supports a wide range of operations, from file management and code editing to debugging and task automation, making it a versatile tool for developers. 
      
      - Examples are **Searching and Replacing:**

         **Command:** `Find: Find in Files` or `Replace in Files`

         **Usage:** Search for text across multiple files or replace text in the entire project.

## **5. Extensions in VS Code:**
   - Discuss the role of extensions in VS Code. How can users find, install, and manage extensions? Provide examples of essential extensions for web development.

      - Extensions in VS Code are essential for tailoring the editor to specific development needs, adding language support, enhancing productivity, and integrating external tools and services. They can be found, installed, and managed through the Extensions view in VS Code or directly from the Visual Studio Code Marketplace. For web development, essential extensions include those for language support, productivity tools, version control, debugging, and code formatting.

      - Installing Extensions:
        - Via Extensions View:
         Click on an extension from the search results to open its details page.
         Click the `Install button` to add the extension to VS Code.
         - Via Command Palette:
         Press `Ctrl + Shift + P` to open the Command Palette.
         Type Extensions: Install Extensions and select it.
         Search for the desired extension and install it from the list.


      - Essential Extensions for Web Development
         - JavaScript and TypeScript: ESLint, Prettier - Code Formatter, and JavaScript (ES6) code snippets.
         - HTML and CSS: HTML CSS Support and CSS Peek.
         - React: ES7+ React/Redux/React-Native snippets and React PropTypes Intellisense.
         - Node.js: Node.js Extension Pack and NPM Intellisense.
         - Vue.js: Vetur and Vue 3 Snippets.
         - Debugger for Chrome: Allows debugging JavaScript code running in the Chrome browser directly from VS Code.

## **6. Integrated Terminal:**
   - Describe how to open and use the integrated terminal in VS Code. What are the advantages of using the integrated terminal compared to an external terminal?

      - How to Open the Integrated Terminal
         - Using the Menu:
         `Go to View > Terminal from the top menu bar.
         Alternatively, you can find it under Terminal > New Terminal.`
         - Using Keyboard Shortcuts:
         `Press Ctrl + (backtick) on Windows (or Cmd + on macOS).
         This shortcut toggles the integrated terminal panel open and closed.`
         - Using the Command Palette:
         `Press Ctrl + Shift + P to open the Command Palette.
         Type Terminal: Create New Terminal and select it from the list.`
      - The integrated terminal in VS Code provides a powerful, versatile, and convenient environment for executing command-line operations directly within the editor. Its integration with the workspace, support for multiple terminals and shells, and extensive customization options make it an invaluable tool for developers. Compared to using an external terminal, the integrated terminal offers the advantages of contextual integration, seamless navigation, and a unified interface that boosts productivity and efficiency.

## **7. File and Folder Management:**
   - Explain how to create, open, and manage files and folders in VS Code. How can users navigate between different files and directories efficiently?

      - VS Code provides a comprehensive set of tools for creating, opening, and managing files and folders. Whether using the Explorer, Command Palette, or keyboard shortcuts, VS Code makes it easy to organize and navigate your project files. Efficient navigation between files and directories is facilitated by features like Quick Open, Breadcrumbs, and Split View, allowing developers to maintain a smooth and productive workflow.

      - **Creating Files and Folders**
         - Using the Explorer View:
         `Open the Explorer View: Click the Explorer icon in the Activity Bar or press Ctrl + Shift + E.`
        - Create a New File:
         `Right-click on the desired folder in the Explorer and select New File, or press Ctrl + N. Type the name of the new file and press Enter.`
         - Create a New Folder:
         `Right-click on the desired parent folder and select New Folder. Enter the folder name and press Enter.`
        - Using the Command Palette:
        `Open the Command Palette: Press Ctrl + Shift + P.
         Create File/Folder: Type File: New File or Explorer: New Folder and press Enter.
         Follow the prompts to create a new file or folder in the desired location.`
        - Using the File Menu:
         `New File: Go to File > New File.
         New Folder: Open the desired folder in the Explorer and create a new folder as described above.`

      - Effecient Navigation:
         - Quick Open (Ctrl + P)
         - Go to File/Definition (F12)
         - Breadcrumb 
         - Side Bar and Explorer
         - Editor Tabs
         - Split View
         - File History (Ctrl + Tab)
         - Bookmarks and Tags


## **8. Settings and Preferences:**
   - Where can users find and customize settings in VS Code? Provide examples of how to change the theme, font size, and keybindings.

   -### Customizing Settings in Visual Studio Code (VS Code)

VS Code offers extensive customization options to tailor the editor to your preferences and workflow. Users can modify settings, change the theme, adjust the font size, and customize keybindings through an intuitive interface. Here's how to find and adjust these settings:

### Accessing Settings

1. **Settings Menu:**
   - Click on the gear icon in the lower-left corner of the window and select `Settings`.
   - Alternatively, go to `File` > `Preferences` > `Settings`.

2. **Command Palette:**
   - Press `Ctrl + Shift + P` to open the Command Palette.
   - Type `Preferences: Open Settings` and select it.

3. **Keyboard Shortcut:**
   - Press `Ctrl + ,` to directly open the settings editor.

### Settings Interface

- **User Settings:** Apply globally across all projects.
- **Workspace Settings:** Apply only to the current workspace or project.
- **Folder Settings:** Apply to a specific folder within a workspace.

Settings can be accessed and modified in two views:
- **GUI (Settings Editor):** A user-friendly interface for browsing and modifying settings.
- **JSON (Settings JSON):** Directly edit the `settings.json` file for advanced configurations.

### Changing the Theme

1. **Via the Settings Menu:**
   - Go to `File` > `Preferences` > `Color Theme`.
   - Browse through the list of installed themes and click to select the one you want.

2. **Using the Command Palette:**
   - Press `Ctrl + Shift + P`.
   - Type `Preferences: Color Theme` and select it.
   - Choose from the list of available themes.

3. **Through the Extensions View:**
   - Open the Extensions view with `Ctrl + Shift + X`.
   - Search for themes in the marketplace (e.g., `Material Theme`, `Dracula Official`).
   - Click `Install` on a theme extension to add it, then apply it using the methods above.

### Adjusting the Font Size

1. **Using the Settings GUI:**
   - Open the settings as described above.
   - Type `Font Size` in the search bar.
   - Adjust the `Editor: Font Size` slider or input box to your desired size.

2. **Directly in `settings.json`:**
   - Open the Command Palette (`Ctrl + Shift + P`).
   - Type `Preferences: Open Settings (JSON)` and select it.
   - Add or modify the setting:
     ```json
     "editor.fontSize": 16
     ```
   - Save the changes to apply the new font size.

3. **Temporary Zoom:**
   - Use `Ctrl + +` to zoom in or `Ctrl + -` to zoom out, which adjusts the entire interface size including the font.

### Customizing Keybindings

1. **Via the Settings Menu:**
   - Go to `File` > `Preferences` > `Keyboard Shortcuts`.
   - Alternatively, press `Ctrl + K` followed by `Ctrl + S`.

2. **Using the Command Palette:**
   - Press `Ctrl + Shift + P`.
   - Type `Preferences: Open Keyboard Shortcuts` and select it.

3. **Modifying Keybindings:**
   - The Keybindings editor displays a list of all commands with their current shortcuts.
   - Search for a specific command using the search bar.
   - Click on the keybinding you want to change and press the new key combination.
   - Click the `OK` button to save the new keybinding.
   - Example:
     - To change the shortcut for opening a new terminal from `Ctrl + `` to `Ctrl + Alt + T`:
       - Search for `Terminal: Create New Integrated Terminal`.
       - Click on the current shortcut and press `Ctrl + Alt + T`.
       - Confirm and save the new keybinding.

4. **Editing `keybindings.json`:**
   - Open the Command Palette (`Ctrl + Shift + P`).
   - Type `Preferences: Open Keyboard Shortcuts (JSON)` and select it.
   - Add or modify keybindings directly in the `keybindings.json` file:
     ```json
     [
       {
         "key": "ctrl+alt+t",
         "command": "workbench.action.terminal.new",
         "when": "terminalFocus"
       }
     ]
     ```
   - Save the file to apply the new keybinding.

### Summary

VS Code provides flexible and comprehensive settings that can be customized to suit individual preferences and workflows. Accessing and modifying settings can be done through the GUI or by editing JSON files directly. Key customizations include changing the theme, adjusting the font size, and setting keybindings to streamline development tasks. These tools help create a personalized and efficient coding environment.

## **9. Debugging in VS Code:**
   - Outline the steps to set up and start debugging a simple program in VS Code. What are some key debugging features available in VS Code?

   ### Setting Up and Starting Debugging in Visual Studio Code (VS Code)

Debugging is an essential part of software development, and VS Code provides a powerful set of debugging tools to help you find and fix issues in your code. Here’s a step-by-step guide to set up and start debugging a simple program in VS Code, along with an overview of key debugging features.

### Steps to Set Up and Start Debugging

1. **Open or Create a Project:**
   - Launch VS Code and open your project folder.
   - Go to `File` > `Open Folder` and select your project directory.
   - Alternatively, create a new folder and add your files (e.g., a simple Python script or JavaScript file).

2. **Install Necessary Extensions:**
   - Depending on your programming language, you might need to install the relevant language extension.
   - Open the Extensions view with `Ctrl + Shift + X`.
   - Search for and install the extension for your language (e.g., `Python`, `JavaScript`, `C++`).

3. **Configure the Debugger:**
   - Click the Run and Debug icon in the Activity Bar (or press `Ctrl + Shift + D`).
   - If it’s your first time debugging the project, click the `Run and Debug` button, and VS Code will suggest creating a launch configuration.
   - Select the appropriate environment for your code (e.g., Node.js for JavaScript, Python).
   - VS Code will generate a `.vscode` folder with a `launch.json` file containing your debugging configuration.
   
   Example `launch.json` for a Node.js application:
   ```json
   {
     "version": "0.2.0",
     "configurations": [
       {
         "type": "node",
         "request": "launch",
         "name": "Launch Program",
         "skipFiles": ["<node_internals>/**"],
         "program": "${workspaceFolder}/app.js"
       }
     ]
   }
   ```

4. **Set Breakpoints:**
   - Open the file you want to debug.
   - Click in the left margin next to the line number where you want to pause execution, or press `F9`.
   - A red dot will appear, indicating a breakpoint.

5. **Start Debugging:**
   - Click the green play button in the Debug panel or press `F5` to start debugging.
   - Your program will start running and pause at any breakpoints you’ve set.
   - If your configuration requires input parameters or special settings, ensure they are specified in the `launch.json` file.

6. **Inspect Variables and Flow:**
   - Once paused at a breakpoint, you can hover over variables to see their current values.
   - Use the Variables panel to inspect all local variables.
   - The Call Stack panel shows the current execution stack, allowing you to navigate through function calls.

7. **Control Execution:**
   - Use the debugging toolbar to control the execution of your program:
     - `Continue (F5)`: Resume running until the next breakpoint.
     - `Step Over (F10)`: Move to the next line of code, stepping over function calls.
     - `Step Into (F11)`: Step into the function call to debug inside it.
     - `Step Out (Shift + F11)`: Step out of the current function.
     - `Restart (Ctrl + Shift + F5)`: Restart the debugging session.
     - `Stop (Shift + F5)`: Stop the debugging session.

### Key Debugging Features in VS Code

1. **Breakpoints:**
   - Set, enable/disable, and remove breakpoints directly in the code editor.
   - Conditional breakpoints: Set conditions for when a breakpoint should pause execution.
   - Logpoints: Output messages to the console without pausing execution.

2. **Variable Inspection:**
   - Hover over variables in the editor to see their current values.
   - The Variables panel shows local, global, and watch variables.
   - The Watch panel allows you to track specific variables or expressions.

3. **Call Stack:**
   - View the current call stack in the Call Stack panel.
   - Navigate up and down the stack to inspect the state of the program at different levels of the stack.

4. **Debug Console:**
   - Execute commands and evaluate expressions in the Debug Console.
   - View output and log messages directly in the console.

5. **Integrated Terminal:**
   - Use the Integrated Terminal to run shell commands and scripts without leaving VS Code.
   - Useful for running additional commands or inspecting files during debugging.

6. **Inline Debugging:**
   - VS Code shows variable values inline with your code while debugging.
   - Provides real-time feedback on variable states as you step through the code.

7. **Conditional Breakpoints and Hit Counts:**
   - Conditional Breakpoints: Break only if a specified condition is true.
   - Hit Counts: Break after a breakpoint has been hit a specified number of times.

8. **Debugging Configurations:**
   - Support for complex debugging configurations in the `launch.json` file.
   - Specify different environments, arguments, and settings for each configuration.

9. **Multi-target Debugging:**
   - Debug multiple targets simultaneously, such as a client and server application.
   - Useful for debugging applications that consist of multiple components.

10. **Remote Debugging:**
    - Attach to processes running on remote machines or Docker containers.
    - Useful for debugging applications in production or isolated environments.

### Summary

VS Code’s debugging capabilities provide a robust environment for developing and troubleshooting code. By following the steps to set up and start debugging, you can easily configure breakpoints, inspect variables, and control program execution. Key features such as variable inspection, the call stack, the debug console, and the ability to set conditional breakpoints make debugging in VS Code both powerful and intuitive.

## **10. Using Source Control:**
   - How can users integrate Git with VS Code for version control? Describe the process of initializing a repository, making commits, and pushing changes to GitHub.

      - ### Integrating Git with Visual Studio Code (VS Code) for Version Control

VS Code has robust built-in support for Git, making it a powerful tool for version control. Here’s how you can integrate Git with VS Code, including initializing a repository, making commits, and pushing changes to GitHub.

### Step-by-Step Guide to Integrating Git with VS Code

#### Prerequisites
1. **Install Git:**
   - Download and install Git from [git-scm.com](https://git-scm.com/downloads).
   - During installation, ensure that Git is added to your system PATH.

2. **Set Up Git in VS Code:**
   - Open VS Code and navigate to `File` > `Preferences` > `Settings`.
   - Search for `Git Path` and verify that VS Code has detected your Git installation. If not, set the path manually to the Git executable.

#### Initializing a Repository

1. **Open a Project Folder:**
   - Launch VS Code and open the folder you want to use for your project.
   - Go to `File` > `Open Folder` and select your project directory.

2. **Initialize the Repository:**
   - Open the Source Control view by clicking the Source Control icon in the Activity Bar or pressing `Ctrl + Shift + G`.
   - Click the `Initialize Repository` button.
   - VS Code will create a `.git` directory in your project folder, initializing it as a Git repository.

3. **Configure Git (First-Time Setup):**
   - Set your username and email for Git commits:
     ```bash
     git config --global user.name "Your Name"
     git config --global user.email "you@example.com"
     ```
   - This is typically done in the terminal. You can open the terminal in VS Code using `Ctrl + ``.

#### Making Commits

1. **Stage Changes:**
   - In the Source Control view, all changes will appear in the `Changes` section.
   - Click the `+` icon next to individual files to stage them, or click the `+` icon at the top to stage all changes.

2. **Write a Commit Message:**
   - Once changes are staged, a text box labeled `Message` will appear at the top of the Source Control view.
   - Write a concise commit message describing your changes.

3. **Commit Changes:**
   - Click the checkmark icon above the `Message` box to commit the staged changes.
   - Your changes are now committed to the local repository.

#### Pushing Changes to GitHub

1. **Create a New Repository on GitHub:**
   - Go to [GitHub](https://github.com) and sign in.
   - Click the `+` button in the upper-right corner and select `New repository`.
   - Fill in the repository name, description (optional), and set visibility (public or private).
   - Click `Create repository`.

2. **Link Your Local Repository to GitHub:**
   - Copy the URL of your new GitHub repository.
   - In VS Code’s terminal, add the remote origin for your local repository:
     ```bash
     git remote add origin https://github.com/yourusername/your-repository.git
     ```
   - Replace the URL with your repository’s URL.

3. **Push Changes to GitHub:**
   - Push your local commits to the GitHub repository:
     ```bash
     git push -u origin main
     ```
   - The `-u` option sets the upstream for the branch, so you only need to use `git push` in the future.
   - If your branch is named something other than `main`, replace `main` with your branch name.

4. **Enter GitHub Credentials:**
   - If prompted, enter your GitHub username and password, or use a personal access token if you have 2FA enabled.
   - You can also configure Git to use SSH keys for authentication to avoid entering credentials each time.

### Key Git Features in VS Code

1. **Source Control View:**
   - Access the Source Control view by clicking the Source Control icon or pressing `Ctrl + Shift + G`.
   - View and manage all changes, staged files, and commit history.

2. **Branch Management:**
   - Switch between branches, create new branches, and manage branch operations from the Source Control view or Command Palette (`Ctrl + Shift + P` > `Git: Checkout to...`).

3. **Diff View:**
   - See a side-by-side comparison of changes in files by clicking on modified files in the Source Control view.
   - Shows what has been added, modified, or deleted in the file.

4. **Merge Conflict Resolution:**
   - VS Code provides tools to resolve merge conflicts with inline options to accept current, incoming, or both changes.
   - Highlight conflicting sections and choose resolutions directly in the editor.

5. **GitLens Extension:**
   - Install the GitLens extension for enhanced Git capabilities, such as detailed file history, blame annotations, and more.

6. **Integrated Terminal:**
   - Use the integrated terminal for advanced Git commands that are not available through the VS Code interface.

### Summary

Integrating Git with VS Code provides a streamlined version control experience within your development environment. By initializing a repository, making commits, and pushing changes to GitHub, you can maintain a robust workflow for managing code changes. VS Code’s built-in Git support, combined with features like branch management, diff views, and merge conflict resolution, makes it an ideal tool for both beginners and experienced developers.


## Submission Guidelines:
- Your answers should be well-structured, concise, and to the point.
- Provide screenshots or step-by-step instructions where applicable.
- Cite any references or sources you use in your answers.
- Submit your completed assignment by 1st July 

