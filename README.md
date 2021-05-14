# TypeScript NPM Package
Scaffold TypeScript npm packages using this template to bootstrap your next library.

This project includes:
- [TypeScript](https://www.typescriptlang.org/)
- [Rollup](https://rollupjs.org/)
- [Microsoft API Extractor](https://api-extractor.com/)
- [TypeDoc](https://typedoc.org/)


## Getting Started

Begin via any of the following:

- Press the "*Use this template*" button

- Use [degit](https://github.com/Rich-Harris/degit) to execute: 

    ```bash
    degit github:jasonsturges/typescript-npm-package
    ```
    
- Use [GitHub CLI](https://cli.github.com/) to execute: 

    ```bash
    gh repo create <name> --template="https://github.com/jasonsturges/typescript-npm-package"
    ```
    
- Simply `git clone`, delete the existing .git folder, and then:

    ```bash
    git init
    git add -A
    git commit -m "Initial commit"
    ````

Remember to use `npm search <term>` to avoid naming conflicts in the NPM Registery for your new package name.


## Usage

The following tasks are available for `npm run`:

- `dev`: Run Rollup in watch mode to detect changes to files during development
- `build`: Run Rollup to build a production release distributable
- `build:types`: Run Microsoft API Extractor to rollup a types declaration (`d.ts`) file 
- `docs`: Run TypeDoc for TSDoc generated in the "docs/" folder
- `clean`: Remove all build artifacts

