# Web Development Extension Pack

A VS Code extension pack for web development.

## Extensions Included

### Language Support

- Astro
- CSS Variable Autocomplete
- GraphQL: Inline Operation Execution
- GraphQL: Language Feature Support
- GraphQL: Syntax Highlighting
- HTML CSS Support
- lit-plugin
- Prisma
- Svelte for VS Code
- Tailwind CSS IntelliSense
- TypeScript Vue Plugin (Volar)
- Vue Language Features (Volar)

### Tools

- Docker
- Dotenv
- EditorConfig for VS Code
- Error Lens
- ESLint
- Git History
- GitHub Actions
- GitHub Copilot
- GitLens
- i18n Ally
- Import Cost
- Kubernetes
- Live Preview
- Live Server
- npm Intellisense
- Pretter - Code formatter
- Quokka.js
- TODO Highlight
- Turbo Console Log
- Version Lens
- YAML

### Remote Development

- GitHub Repositories
- Remote - SSH: Editing Configuration Files
- Remote Development
- Remote Explorer

## Development Workflow

- modify package.json `extensionPack` field.
- modify CHANGELOG.md
- modify package.json `version` field.
- modify README.md Extensions Included section.
- use `vsce package` to create a .vsix file.
- use `vsce publish` to publish the extension pack to the marketplace.
