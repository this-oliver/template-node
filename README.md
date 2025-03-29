# README

[![CI/CD](https://github.com/this-oliver/template-node/actions/workflows/cicd.yaml/badge.svg)](https://github.com/this-oliver/template-node/actions/workflows/cicd.yaml)

This is a template for javascript or typescript projects.

Apart from the usual stuff, the repo also includes:

- [git hooks for linting and formatting](package.json) with `simple-git-hooks` and `lint-staged`
- [typescript config](tsconfig.json)
- [github workflow with linting and security checks](.github/workflows/cicd.yaml)
- [github dependabot config](.github/dependabot.yml)

## Usage

```bash
# Install dependencies
pnpm install

# Build
pnpm build

# Run
node dist/index.js
```
