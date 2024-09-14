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

- **JavaScript/**

  - Contains `extensions.json` with extension recommendations tailored for JavaScript development, particularly with modern frameworks like React, Vite, and Tailwind CSS, along with GraphQL support:

    - **Vite (antfu.vite)**: Provides commands and tools to integrate **Vite** into your JavaScript projects, improving the build speed and overall development workflow with Vite-powered applications.

    - **Tailwind CSS IntelliSense (bradlc.vscode-tailwindcss)**: Adds autocompletion, IntelliSense, and linting for **Tailwind CSS**, making it easier to work with utility-first CSS in your JavaScript and React projects.

    - **ESLint (dbaeumer.vscode-eslint)**: A popular linter for JavaScript, ensuring your code follows best practices and identifying potential errors in both JavaScript and TypeScript files.

    - **ES7+ React/Redux/React-Native Snippets (dsznajder.es7-react-js-snippets)**: Provides a wide array of **React** and **Redux** code snippets, greatly speeding up the development process for React applications by offering shortcuts for common patterns.

    - **GraphQL (graphql.vscode-graphql)**: Offers comprehensive language support for **GraphQL**, including syntax highlighting, validation, and autocomplete for your GraphQL queries and schemas.

    - **GraphQL Syntax Highlighting (graphql.vscode-graphql-syntax)**: Adds detailed syntax highlighting for **GraphQL** files, making it easier to write and read GraphQL queries in your JavaScript projects.

## How to Use

1. **Clone the repository**:

   ```bash
   git clone https://github.com/your-username/vscode-config.git
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
