# My Yarn Monorepo

This is a monorepo managed with Yarn workspaces. It contains multiple packages in the `packages/` directory.

## Prerequisites

- Node.js >= 16.0.0
- Yarn >= 1.22.0

## Getting Started

1. Install dependencies:
```bash
yarn install
```

2. Available scripts:
- `yarn build` - Build all packages
- `yarn test` - Run tests for all packages
- `yarn lint` - Run linting for all packages
- `yarn clean` - Clean build artifacts
- `yarn dev` - Run development mode for all packages

## Project Structure

```
packages/
  ├── my-cursor-app/    # Your application package
  └── ...              # Other packages
```

## Adding a New Package

1. Create a new directory in `packages/`
2. Initialize a new package with `yarn init`
3. Add your package's dependencies
4. The package will automatically be included in the workspace

## Development

Each package can be developed independently or as part of the monorepo. Use `yarn workspace <package-name> <command>` to run commands for specific packages. 