# VS Code Configuration Repository

This repository contains customised **Visual Studio Code** settings and extension recommendations organised by development environments. It helps to standardise and streamline the setup of Visual Studio Code across different types of projects.

## Folder Structure

- **General/**

  - Contains `settings.json` and `extensions.json` with general extensions that enhance productivity, code formatting, version control, and overall user experience in Visual Studio Code:

    - **Better Comments (aaron-bond.better-comments)**: Improves the readability of comments by providing different colors and highlighting for various types of comments, such as TODOs, warnings, and questions.

    - **CodeSnap (adpyke.codesnap)**: Allows you to take beautiful screenshots of your code directly within VS Code, making it easy to share snippets with others.

    - **Bookmarks (alefragnani.bookmarks)**: Helps you manage bookmarks in your code, making it easier to navigate and mark important lines or sections.

    - **GitLens (eamodio.gitlens)**: Enhances Git integration by providing detailed Git annotations, inline blame, repository history, and powerful version control tools.

    - **Prettier - Code Formatter (esbenp.prettier-vscode)**: Automatically formats your code according to the specified rules, ensuring consistent style across various programming languages.

    - **Code Runner (formulahendry.code-runner)**: Allows you to quickly run code snippets from various languages directly within the editor, speeding up the development process.

    - **TODO Tree (gruntfuggly.todo-tree)**: Provides a tree view of all the TODO comments in your project, making it easier to track and manage outstanding tasks.

    - **Peacock (johnpapa.vscode-peacock)**: Allows you to color-code your VS Code workspace to make it easier to visually distinguish between different projects or environments.

    - **CSS Peek (pranaygp.vscode-css-peek)**: Lets you peek into CSS definitions directly from your HTML or JavaScript, improving your workflow when working with front-end projects.

    - **Error Lens (usernamehw.errorlens)**: Highlights errors and warnings directly in the editor, making it easier to spot and fix issues in real-time without checking the Problems tab.

    - **Import Cost (wix.vscode-import-cost)**: Displays the size of imported JavaScript or TypeScript packages, helping you keep track of your project's bundle size.

    - **Material Icon Theme (pkief.material-icon-theme)**: A popular icon theme that adds visually appealing icons for files and folders, improving project navigation and aesthetics.

    - **One Monokai 80s (axiomaticstudios.one-monokai-80s)**: A retro-inspired color theme that adds a vibrant and fun look to your editor, based on the popular Monokai theme.

- **Docker/**

  - Contains `extensions.json` with extension recommendations focused on Docker and containerized development. These extensions provide tools for managing Docker containers, working with YAML files, and using containers for development environments:

    - **Docker (ms-azuretools.vscode-docker)**: Offers full support for working with **Docker** in VS Code, including managing containers, images, registries, and Docker Compose files. It simplifies building, running, and debugging containerized applications.

    - **Remote - Containers (ms-vscode-remote.remote-containers)**: Enables you to open any folder inside a **Docker container** as a development environment, making it easy to work within isolated and reproducible development setups.

    - **YAML (redhat.vscode-yaml)**: Provides powerful editing features for **YAML** files, such as autocompletion, validation, and linting, which are essential when working with Docker Compose files or Kubernetes configurations.

- **Flutter/**

  - Contains `extensions.json` with extension recommendations tailored for Flutter and Dart development. These extensions provide code snippets, project management tools, and enhanced Flutter workflow support:

    - **Flutter Snippets (alexisvt.flutter-snippets)**: Provides a collection of code snippets for **Flutter** to speed up common Flutter tasks, such as creating widgets, layouts, and state management snippets.

    - **Dart (dart-code.dart-code)**: Essential for **Dart** development, this extension provides IntelliSense, debugging, and other tools specifically for Dart programming, which powers Flutter applications.

    - **Flutter (dart-code.flutter)**: Adds full **Flutter** development support in VS Code, including the ability to run, debug, and deploy Flutter apps, as well as Flutter-specific IntelliSense and code navigation.

    - **Pubspec Assist (jeroen-meijer.pubspec-assist)**: Helps manage dependencies in your `pubspec.yaml` file by providing autocompletion and assisting in adding or removing packages from the file.

    - **Flutter Tree (marcelovelasquez.flutter-tree)**: Offers a tree view for the Flutter widget hierarchy, allowing you to visually navigate through widget trees and better manage complex UI structures in Flutter projects.

- **JavaScript/**

  - Contains `extensions.json` with extension recommendations tailored for JavaScript development, particularly with modern frameworks like React, Vite, and Tailwind CSS, along with GraphQL support:

    - **Vite (antfu.vite)**: Provides commands and tools to integrate **Vite** into your JavaScript projects, improving the build speed and overall development workflow with Vite-powered applications.

    - **Tailwind CSS IntelliSense (bradlc.vscode-tailwindcss)**: Adds autocompletion, IntelliSense, and linting for **Tailwind CSS**, making it easier to work with utility-first CSS in your JavaScript and React projects.

    - **ESLint (dbaeumer.vscode-eslint)**: A popular linter for JavaScript, ensuring your code follows best practices and identifying potential errors in both JavaScript and TypeScript files.

    - **ES7+ React/Redux/React-Native Snippets (dsznajder.es7-react-js-snippets)**: Provides a wide array of **React** and **Redux** code snippets, greatly speeding up the development process for React applications by offering shortcuts for common patterns.

    - **GraphQL (graphql.vscode-graphql)**: Offers comprehensive language support for **GraphQL**, including syntax highlighting, validation, and autocomplete for your GraphQL queries and schemas.

    - **GraphQL Syntax Highlighting (graphql.vscode-graphql-syntax)**: Adds detailed syntax highlighting for **GraphQL** files, making it easier to write and read GraphQL queries in your JavaScript projects.

- **Python/**

  - Contains `extensions.json` with extension recommendations tailored for Python development. These extensions provide comprehensive Python environment management, debugging, and IntelliSense capabilities to streamline Python workflows:

    - **Python Environment Manager (donjayamanne.python-environment-manager)**: Helps manage Python environments (virtual environments, conda, etc.) directly within VS Code, making it easy to switch between environments and ensure dependencies are correctly handled.

    - **Debugpy (ms-python.debugpy)**: Provides powerful debugging tools for Python applications, allowing breakpoints, variable inspection, and step-by-step execution to help diagnose issues efficiently.

    - **Pylint (ms-python.pylint)**: A popular linter for Python, ensuring that your code follows best practices and adheres to Python’s style guide (PEP 8) by identifying errors, potential issues, and style violations.

    - **Python (ms-python.python)**: The core extension for Python development, offering IntelliSense, linting, and powerful code navigation features for working with Python projects.

    - **Pylance (ms-python.vscode-pylance)**: Enhances Python IntelliSense with faster and more accurate code completions, type checking, and overall improved language server performance.

- **Unity/**

  - Contains `extensions.json` with extension recommendations specific to Unity development. These extensions provide tools for C# development, Unity-specific code snippets, shader editing, and Unity project integration:

    - **Unity Code Snippets (kleber-swf.unity-code-snippets)**: Offers a collection of useful Unity-specific code snippets to speed up common tasks in Unity development, such as creating MonoBehaviour scripts or event functions.

    - **C# (ms-dotnettools.csharp)**: Provides advanced IntelliSense, debugging, and refactoring tools for C# development, essential for working with Unity’s primary scripting language.

    - **.NET Install Tool for Extension Authors (ms-dotnettools.vscode-dotnet-runtime)**: Ensures the proper .NET runtime environment for running and debugging Unity C# scripts inside VS Code.

    - **Shader languages support for VS Code (slevesque.shader)**: Adds syntax highlighting and IntelliSense for shader languages, including HLSL and GLSL, which are used in Unity for custom rendering.

    - **Visual Studio Tools for Unity (visualstudiotoolsforunity.vstuc)**: Provides enhanced debugging and project synchronization between Unity and VS Code, allowing for a smoother Unity development experience.

- **UnrealEngine/**

  - Contains `extensions.json` with extension recommendations specific to Unreal Engine development. These extensions provide the necessary tools for C++ development, CMake integration, shader editing, and code formatting according to Unreal Engine's standards:

    - **C/C++ (ms-vscode.cpptools)**: Provides C++ IntelliSense, debugging, and basic code navigation, essential for Unreal Engine C++ development.

    - **CMake Tools (ms-vscode.cmake-tools)**: Facilitates working with CMake projects in Unreal Engine, including project configuration, building, and debugging.

    - **Shader languages support for VS Code (slevesque.shader)**: Adds syntax highlighting and IntelliSense for shader languages, including HLSL and GLSL, which are used in Unreal Engine for rendering.

    - **Clang-Format (xaver.clang-format)**: Ensures that your C++ code follows Unreal Engine's coding style guidelines, improving consistency and readability across the project.

## How to Use

1. **Clone the repository**:

   ```bash
   git clone https://github.com/johansource/vscode-config.git
   ```

2. **General Setup**:

   - Copy the contents of the `General/.vscode` folder into your project’s `.vscode` folder for basic VS Code settings and common extensions.
   - Alternatively, you can manually merge the settings in `settings.json` into your own project’s `.vscode/settings.json`.

3. **Environment-Specific Extensions**:

   - For specific development environments, navigate to the appropriate folder (e.g., `JavaScript`, `Python`, `Docker`, `Unity`) and copy the `extensions.json` file into your project’s `.vscode` folder.
   - VS Code will automatically prompt you to install the recommended extensions when you open your project.

   Example for JavaScript:

   ```bash
   cp JavaScript/extensions.json <your-project>/.vscode/
   ```

4. **Customise As Needed**:
   - Feel free to modify the `settings.json` and `extensions.json` files as your development needs evolve.
   - You can also add more environment-specific folders (e.g., Ruby, PHP) to this repository over time.

## Contributing

If you want to add more recommendations, feel free to open a pull request or contribute directly by adding new environment folders or extensions.
