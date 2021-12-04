# TypeScript Repository Template

Use this repository as a template for other TypeScript repos.
It includes boilerplate configuration for:

- [NPM](https://www.npmjs.com/)
- [TypeScript](https://www.typescriptlang.org/)
- [Jest](https://jestjs.io/) with [TypeScript support](https://kulshekhar.github.io/ts-jest/)
- [ESLint](https://eslint.org/) with [TypeScript support](https://typescript-eslint.io/)
- [Prettier](https://prettier.io/)
- [MIT license](https://choosealicense.com/licenses/mit/)

It also comes setup with NPM scripts:

- `build` – Builds the project by running the `clean`, `compile`, `lint`, and `format:check` scripts
- `clean` – Removes the output directory
- `compile` – Compiles TypeScript files with `tsc`
- `format` – Formats files with Prettier
- `format:check` – Checks files for correct formatting
- `lint` – Lints the code with ESLint
- `lint:fix` – Attempts to fix problems found by the linter
- `test` – Runs tests (`*.spec.ts` files) with Jest
- `test:watch` – Runs tests in watch mode
