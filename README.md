# ts-aiagent-boilerplate

**ts-aiagent-boilerplate** is a TypeScript-based boilerplate designed to help developers quickly start developing custom modules and packages for [@ai16zdao's Eliza framework](https://github.com/ai16z/eliza). It provides a robust development environment with tools for linting, formatting, testing, and building scalable Node.js applications. This project is not a fork of the Eliza codebase, and is instead a complementary starting point for module and package development that follows the same practices as the core project.

## Features

- **TypeScript-first Development**: Type-safe and scalable codebase.
- **ESLint and Prettier**: Enforce consistent code quality and formatting.
- **Vitest Integration**: Fast and modern testing framework.
- **PNPM for Dependency Management**: Faster, more efficient package management.
- **Configurable Build System**: Ready for production deployment.

---

## Getting Started

### Prerequisites

- **Node.js 22+** (Use [NVM](https://github.com/nvm-sh/nvm) for version management)
- **PNPM** (Install via `npm install -g pnpm`)

### Installation

1. Clone the repository:

   ```bash
   git clone https://github.com/yourusername/ts-aiagent-boilerplate.git
   cd ts-aiagent-boilerplate
   ```

2. Install dependencies:
   ```bash
   pnpm install
   ```

### Development

1. Run tests:

   ```bash
   pnpm test
   ```

2. Lint the code:

   ```bash
   pnpm lint
   ```

3. Build the project:

   ```bash
   pnpm build
   ```

4. Start the project (for testing purposes):
   ```bash
   node dist/index.js
   ```

---

## Project Structure

```
ts-aiagent-boilerplate/
├── src/                   # Source code
│   ├── index.ts           # Entry point
│   ├── core/              # Core modules
│   ├── utils/             # Utility functions
├── test/                  # Unit tests
├── config/                # Configuration files
├── dist/                  # Compiled output
├── scripts/               # Helper scripts (build, clean, etc.)
├── package.json           # Project metadata and dependencies
├── tsconfig.json          # TypeScript configuration
├── .eslintrc.mjs          # ESLint configuration
├── .prettierrc            # Prettier configuration
├── .gitignore             # Ignored files
└── README.md              # Project documentation
```

---

## Attribution

This boilerplate is inspired by [@ai16zdao's Eliza framework](https://github.com/ai16z/eliza), a powerful foundation for developing #aiagents.

---

## License

This project is licensed under the MIT License. See the [LICENSE](./LICENSE) file for details.

---

## Contact

For any questions or feedback, please reach out to [@cottenio](https://x.com/CottenIO).

```◊

```
