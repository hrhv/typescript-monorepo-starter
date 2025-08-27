# TypeScript Monorepo Starter Pack

A Turborepo-based monorepo with global Prettier and ESLint configurations.

## Features

- **Turborepo** for fast, incremental builds
- **Global Prettier** configuration for consistent code formatting
- **Global ESLint** configuration with TypeScript support
- **VSCode** workspace settings for seamless development experience

## Getting Started

1. Install dependencies:
   ```bash
   yarn install
   ```

2. Add new apps to the `apps/` directory

## Available Scripts

- `yarn dev` - Start development servers
- `yarn build` - Build all packages
- `yarn start` - Start production servers
- `yarn clean` - Clean build outputs
- `yarn test` - Run tests
- `yarn lint` - Lint all code
- `yarn lint:fix` - Lint and auto-fix code
- `yarn format` - Format all code with Prettier
- `yarn format:check` - Check if code is properly formatted

## Code Quality

### Prettier
- Automatically formats code on save (VSCode)
- Consistent code style across the entire monorepo
- Configuration: `.prettierrc`

### ESLint
- TypeScript-aware linting
- Consistent code quality rules
- Configuration: `.eslintrc.js`

## Adding New Apps

1. Create a new directory in `apps/`
2. Add a `package.json` with your app configuration
3. The global Prettier and ESLint configs will automatically apply

## VSCode Setup

Install these extensions for the best experience:
- **Prettier - Code formatter**
- **ESLint**

The workspace settings in `.vscode/settings.json` will automatically:
- Format code on save using Prettier
- Fix ESLint issues on save
- Use the project's Prettier and ESLint configurations
