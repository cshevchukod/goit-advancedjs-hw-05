# goit-advancedjs-hw-05

Homework for the TypeScript introduction topic.

## Description

This project contains a basic TypeScript setup with compiler configuration,
source maps, and npm scripts for building and running the compiled JavaScript
code.

## Technologies

- TypeScript
- Node.js
- Prettier

## Project structure

```txt
src/
  index.ts
dist/
  index.js
  index.js.map
```

The `src` folder contains the source TypeScript files. The `dist` folder is
generated after compilation and is ignored by Git.

## Scripts

Install dependencies:

```bash
npm install
```

Compile TypeScript:

```bash
npm run build
```

Run compiled JavaScript:

```bash
npm run start
```

Format files with Prettier:

```bash
npm run format
```

## Source maps

Source maps are enabled in `tsconfig.json`:

```json
"sourceMap": true
```
