# Digital-Sunsets
This will be the repository for the entire Digital Sunsets App

This repository is a monorepo managed by [Digital Sunsets](https://digital-sunsets.com/) and contains a Next.js application written in TypeScript.

## Table of Contents

- [Prerequisites](#prerequisites)
- [Installation](#installation)
- [Development](#development)
- [Build](#build)
- [Linting](#linting)
- [Testing](#testing)
- [Directory Structure](#directory-structure)
- [Contributing](#contributing)
- [License](#license)

## Prerequisites

Before you begin, ensure you have met the following requirements:

- **Node.js**: v14.x or later
- **Yarn**: v1.22.x or later (preferred over npm for Turborepo)
- **Git**: v2.20.x or later

## Installation

To set up the project locally, follow these steps:

1. **Clone the repository**:
    ```sh
    git clone https://github.com/your-username/your-repo-name.git
    cd your-repo-name
    ```

2. **Install dependencies**:
    ```sh
    yarn install
    ```

## Development

To start the development server for the Next.js application:

1. **Navigate to the Next.js app directory**:
    ```sh
    cd apps/next-app
    ```

2. **Start the development server**:
    ```sh
    yarn dev
    ```

3. Open your browser and navigate to `http://localhost:3000`.

## Build

To build the Next.js application for production:

1. **Navigate to the Next.js app directory**:
    ```sh
    cd apps/next-app
    ```

2. **Run the build command**:
    ```sh
    yarn build
    ```

## Linting

To run linting checks across the entire monorepo:

1. **Navigate to the root directory**:
    ```sh
    cd your-repo-name
    ```

2. **Run the lint command**:
    ```sh
    yarn lint
    ```

## Testing

To run tests for the Next.js application:

1. **Navigate to the Next.js app directory**:
    ```sh
    cd apps/next-app
    ```

2. **Run the test command**:
    ```sh
    yarn test
    ```

## Directory Structure

The repository is structured as follows:
your-repo-name/
├── apps/
│ └── next-app/ # Next.js application
│ ├── public/
│ ├── src/
│ ├── pages/
│ ├── styles/
│ ├── tsconfig.json
│ ├── next.config.js
│ └── package.json
├── packages/ # Shared packages (if any)
├── .gitignore
├── package.json
├── turbo.json # Turborepo configuration
└── yarn.lock

## Contributing

Contributions are always welcome! Please follow these steps to contribute:

1. **Fork the repository**.
2. **Create a new branch** (`git checkout -b feature/your-feature-name`).
3. **Commit your changes** (`git commit -m 'Add some feature'`).
4. **Push to the branch** (`git push origin feature/your-feature-name`).
5. **Open a Pull Request**.

## License

This project is licensed under the GNU General Public License. See the [LICENSE](LICENSE) file for details.
