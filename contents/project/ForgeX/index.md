---
hide:
  - toc
---
##  ForgeX - Ultimate Golang ForgeX Library

![lo](#)


Powerful CLI tool designed to streamline the process of creating  projects with a robust and standardized structure. Not only does  ForgeX facilitate project initialization, but it also offers seamless integration with popular  frameworks, allowing you to focus on your application's code from the very beginning.

## Why Choose  ForgeX?

- **Easy Setup and Installation**:  ForgeX simplifies the setup process, making it a breeze to install and get started with your  projects.

- **Pre-established  Project Structure**: Save time and effort by having the entire  project structure set up automatically. No need to worry about directory layouts or configuration files.

- **HTTP Server Configuration Made Easy**: Whether you prefer 's standard library HTTP package, Chi, Gin, Fiber, HttpRouter, rilla/mux or Echo,  ForgeX caters to your server setup needs.

- **Focus on Your Application Code**: With  ForgeX handling the project scaffolding, you can dedicate more time and energy to developing your application logic.

## Project Structure

Here's an overview of the project structure created by  ForgeX when all options are utilized:

```bash
/ (Root)
├── .github/
│   └── workflows/
│       ├── test.yml           # GitHub Actions workflow for running tests.
│       └── release.yml           # GitHub Actions workflow for releasing the application.
├── cmd/
│   ├── api/
│   │   └── main.               # Main file for starting the server.
│   └── web/
│       ├── assets/
│       │   ├── css/
│       │   │   ├── input.css     # Tailwind input file for compiling output.css with CLI when HTMX is used
│       │   │   └── output.css    # Generated CSS file.
│       │   └── js/
│       │       └── htmx.min.js   # HTMX library for dynamic HTML content.
│       ├── base.templ            # Base HTML template file.
│       ├── base_templ.         # Generated  code for base template.
│       ├── efs.                # Includes assets into compiled binary.
│       ├── hello.              # Logic for handling "hello" form.
│       ├── hello.templ           # Template file for the "hello" endpoint.
│       └── hello_templ.        # Generated  code for the "hello" template. 
├── frontend/                     # React advanced flag. Excludes HTMX.
│   ├── node_modules/             # Node dependencies.
│   ├── public/
│   │   ├── index.html
│   │   └── favicon.ico
│   ├── src/                      # React source files.
│   │   ├── App.tsx               # Main React component.
│   │   ├── assets/               # React assets directory
│   │   │   └── lo.svg
│   │   ├── components/           # React components directory.
│   │   │   ├── Header.tsx
│   │   │   └── Footer.tsx
│   │   ├── styles/               # CSS/SCSS styles directory.
│   │   │   └── global.css
│   │   └── index.tsx             # Main entry point for React
│   ├── eslint.config.js          # ESLint configuration file.
│   ├── index.html                # Base HTML template.
│   ├── package.json              # Node.js package configuration.
│   ├── package-lock.json         # Lock file for Node.js dependencies.
│   ├── README.md                 # README file for the React project.
│   ├── tsconfig.app.json         # TypeScript configuration for the app.
│   ├── tsconfig.json             # Root TypeScript configuration.
│   ├── tsconfig.node.json        # TypeScript configuration for Node.js.
│   └── vite.config.ts            # Vite configuration file.
├── internal/
│   ├── database/
│   │   ├── database_test.      # File containing integration tests for the database operations.
│   │   └── database.           # File containing functions related to database operations.
│   └── server/
│       ├── routes.             # File defining HTTP routes.
│       ├── routes_test.        # Test file for testing HTTP handlers.
│       └── server.             # Main server logic.
├── .air.toml                     # Configuration file for Air, a live-reload utility.
├── docker-compose.yml            # Docker Compose configuration.
├── Dockerfile                    # Dockerfile configuration for the  project.
├── .env                          # Environment configuration file.
├── .gitignore                    # File specifying which files and directories to ignore in Git.
├── .mod                        #  module file for managing dependencies.
├── .releaser.yml               # Configuration file for Releaser, a tool for building and releasing binaries.
├── .sum                        #  module file containing checksums for dependencies.
├── Makefile                      # Makefile for defining and running commands.
├── tailwind.config.js            # Tailwind CSS configuration file for HTMX.
└── README.md                     # Project's README file containing essential information about the project.

```

This structure provides a comprehensive organization of your project, separating source code, tests, configurations and documentation.
