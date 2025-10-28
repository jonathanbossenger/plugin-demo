# WordPress Plugin GitHub Copilot Instructions

This repository maintains a custom set of GitHub Copilot Coding Agent instructions specifically designed for WordPress plugin development.

## What is This?

GitHub Copilot allows you to provide custom instructions to the Copilot Coding Agent through a special file located at `.github/copilot-instructions.md` in your repository. These instructions help Copilot better understand your project's:

- Build processes and requirements
- Coding standards and conventions
- Development workflows
- Common issues and solutions
- Project-specific architecture

## What's Included

This repository contains comprehensive instructions for WordPress plugin development that cover:

- **Environment Requirements**: Node.js, npm, PHP, and Composer version specifications
- **Build Instructions**: Step-by-step dependency installation and build processes
- **Linting and Code Quality**: JavaScript, CSS, and PHP linting configurations
- **Project Architecture**: Standard WordPress plugin structure using Gutenberg blocks
- **WordPress Coding Guidelines**: Best practices and patterns for WordPress development
- **Validation Workflows**: Pre-commit checklists for code quality
- **Common Issues and Solutions**: Troubleshooting guide for typical problems

## How to Use

### Option 1: Copy to Your WordPress Plugin Repository

1. Create a `.github` directory in your WordPress plugin repository if it doesn't exist
2. Copy the `.github/copilot-instructions.md` file from this repository to your `.github/` directory
3. Customize the placeholders (e.g., `[your-plugin-name]`, `[your-block-name]`) to match your specific plugin

### Option 2: Use as a Reference

You can also use this file as a reference when creating your own custom instructions, adapting only the sections that are relevant to your project.

## Features

The instructions in this repository are designed to:

- ✅ Minimize unnecessary exploration and trial-and-error
- ✅ Enforce WordPress coding standards (tabs for indentation, proper hook registration)
- ✅ Provide exact build, lint, and test commands
- ✅ Document common pitfalls and their solutions
- ✅ Guide Copilot through the proper development workflow

## Requirements

These instructions assume your WordPress plugin uses:

- WordPress 6.8 or higher
- PHP 8.1 or higher  
- Node.js 20+ and npm 10+
- `@wordpress/scripts` for building blocks
- WordPress Coding Standards for PHP linting

If your plugin uses a different stack, you'll need to customize the instructions accordingly.

## Contributing

Suggestions and improvements are welcome! If you've found these instructions helpful and have ideas for enhancements, please open an issue or submit a pull request.

## About GitHub Copilot Instructions

GitHub Copilot custom instructions are part of Copilot's ability to understand project-specific context. By providing these instructions, you help Copilot:

- Make fewer mistakes by understanding your exact build process
- Follow your project's specific coding standards
- Know which commands to run for linting, building, and testing
- Avoid common issues that have already been solved

Learn more about GitHub Copilot custom instructions in the [GitHub documentation](https://docs.github.com/en/copilot/customizing-copilot/adding-custom-instructions-for-github-copilot).

## License

This project is open source and available for anyone to use and adapt for their WordPress plugin development needs.
