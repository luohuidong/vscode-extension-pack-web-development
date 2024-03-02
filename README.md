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
- Thunder Client
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

1. modify package.json `extensionPack` field.
1. modify CHANGELOG.md
1. modify README.md Extensions Included section.
1. use `pnpm version` to modify the package.json `version` field.
1. use `vsce package` to create a .vsix file.
1. use `vsce publish` to publish the extension pack to the marketplace.
