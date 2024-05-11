# Webpack Template Usage Guide

This guide explains how to use the Webpack project template. The template is
designed to help you quickly set up new web development projects using Webpack.

## Project Structure

- **src/**: Contains your project's source JavaScript files.
- **dist/**: Where Webpack will output the bundled files.
- **webpack.config.js**: Contains the Webpack configuration.
- **package.json**: Manages project dependencies and scripts.
- **.gitignore**: Prevents specified files and directories from being tracked by
  Git.

## Setup Instructions

To use this template for a new project, follow these steps:

### 1. Copy the Template

Copy the entire contents of the template folder to your new project directory.
You can do this manually in your file explorer or use the command line:

cp -r path/to/webpack-template/ path/to/new-project/

### 2. Initialize npm

Navigate to your project directory and run:

npm install This command installs all the dependencies defined in package.json.

### 3. Initialize Git (Optional)

If you want to use Git for version control, initialize it in the new project
directory:

cd path/to/new-project git init After initializing, consider committing the
initial state:

git add . git commit -m "Initial commit from Webpack template"

### 4. Start Development

Use the npm scripts defined in package.json to build or serve your project:

Build the project: npm run build

Launch development server: npm start
