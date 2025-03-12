# Node.js Typescript Prettier and Eslint Template

[![Stack Technologies](https://skillicons.dev/icons?i=nodejs,npm,ts)](https://skillicons.dev)

Ready to use simple template to work with:

- [Node.js]()
- [Typescript](https://www.typescriptlang.org)
- [Prettier](https://prettier.io)
- [Eslint](https://eslint.org)

---

## Table of Contents

- [Installation](#installation)
- [Usage](#usage)
- [Contributing](#contributing)

---

## Installation

1. Clone the repository:

```bash
git clone https://github.com/SergioCzPz/node-typescript.git
```

2. Install dependencies:

```bash
npm install
```

3. Husky

To work with pre-commint hook

```bash
npm run prepare
```

---

## Usage

All the files to be transpile most to be inside `src/` folder and the entry point is `src/app.ts`

### Develope

To work in develope mode:

```bash
npm run start:dev
```

### Build

To build your project:

```bash
npm run start:build
```

### Run Compiled Project

```bash
npm start
```

This will execute `dist/app.js`

## Considerations

- Feel free to modify `.prettierrc`, you could also find [more configurations](https://prettier.io/docs/precommit) to format your code and pre-commit hook

- Working with [Express](https://expressjs.com) with Typescript, could make a little hard, consider use [Disable eslint rules](https://eslint.org/docs/latest/use/configure/rules#disabling-inline-comments) just disabling inline comments.

- This project uses [Commilint](https://commitlint.js.org) and pre commit hook with [Husky](https://typicode.github.io/husky)

## Contributing

1. Fork the repository.

2. Create a new branch: `git checkout -b <feature-name>`.

3. Make your changes.

4. Push your branch: `git push origin <feature-name>`.

5. Create a pull request.
