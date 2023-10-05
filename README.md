# NestJS Backend Template

## Introduction

This is a template for setting up a backend project using NestJS. It includes predefined scripts for building, formatting, and committing your code following best practices.

## Getting Started

### Prerequisites

- Node.js (v18.0.0 or higher)
- PNPM package manager

### Installation

1. Clone the repository:

   ``` bash
   git clone https://github.com/Incresco/nestjs-backend-template.git
   ```

2. Install the dependencies:

   ```bash
   pnpm install
   ```

### Running the Project

- **Development Mode**: Run `pnpm start:dev` for a dev server with live reloading.
- **Debug Mode**: Run `pnpm start:debug` to start the project with debug enabled.
- **Production Mode**: Run `pnpm start:prod` to run the compiled project.

### Building

Run `pnpm build` to build the project. The build artifacts will be stored in the `dist/` directory.

### Formatting

- **Prettier**: Run `pnpm run format` to automatically format your code using Prettier.

### Committing

- **Semantic Commits**: Run `pnpm run commit` to initiate a guided committing process ensuring semantic standards.

### Linting

- **ESLint**: Run `pnpm lint` to execute the linter on your project.

## Husky Hooks

This project is configured with Husky to automatically run formatting before every commit and validate commit messages.

## Support and Issues

If you encounter any problems or have suggestions, please log an issue on the [GitHub issue tracker](https://github.com/Incresco/nestjs-backend-template/issues). Your feedback is highly appreciated.

Happy coding! 🚀

