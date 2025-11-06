# AGENTS.md for GraveOffice.com

## Build, Lint, Test Commands
- `npm run build` : Build the project
- `npm run lint` : Check code style and formatting
- `npm test` : Run all tests
- `npm test -- --testNamePattern='TestName'` : Run a specific test by name

## Code Style Guidelines
- Use ES modules import syntax
- Maintain consistent indentation and formatting (Prettier recommended)
- Use TypeScript types for variables and function signatures
- Follow camelCase for variables and functions, PascalCase for components
- Handle errors gracefully with try-catch blocks
- Import statements should be grouped: external libraries first, then internal modules
- Keep functions small and focused

## Cursor and Copilot Rules
- Follow existing cursor rules in `.cursor/rules/` and `.cursorrules`
- Adhere to Copilot instructions in `.github/copilot-instructions.md`

Ensure all code adheres to these guidelines for consistency and quality.