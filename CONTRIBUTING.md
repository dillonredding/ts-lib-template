# Contribution Guidelines

Thank you for taking the time and consideration to contribute to this project!

This document outlines our guidelines for contributing to this repository.
Following these guidelines helps communicate that you respect the time of the
developers managing and developing this open source project. In return, they
should reciprocate that respect in addressing your issue, assessing changes, and
helping you finalize your pull requests. Check out the
[Code of Conduct](CODE_OF_CONDUCT.md) to learn about our core values and norms.

> First time contributing to open source? You can learn how from this _free_
> video series: [How to Contribute to an Open Source Project on GitHub][course].

[course]: https://kcd.im/pull-request

## Bugs and Feature Requests

If you find a bug or would like to request a new feature, be sure to check out
the current list of [issues]. If you can't find anything, feel free to
[create a new one][create-issue].

[issues]: https://github.com/{owner}/{repo}/issues
[create-issue]: https://github.com/{owner}/{repo}/issues/new

## Pull Requests

If you'd like to contribute a change, follow these steps:

1. Fork the repository.
1. Clone your fork.
1. Create a branch.
1. Make and commit your changes (see [Development](#development)).
   - Be sure to update the [changelog](CHANGELOG.md).
   - If you're making code changes, be sure to write tests!
1. Push your changes to your fork.
1. If your build is passing, create a pull request.
1. Wait for a review and make changes as requested.
1. Get merged!

## Development

This section helps you get your development environment set up for making code
changes.

First, you'll want to be sure [Node.js] is installed. You can either download
and install it directly from Node's website, or you can use a Node version
manager (recommended for testing on multiple versions of Node). There's [nvm]
for Mac/Linux and [nvm-windows] for Windows.

[node.js]: https://nodejs.org
[nvm]: https://github.com/nvm-sh/nvm
[nvm-windows]: https://github.com/coreybutler/nvm-windows

Next, `cd` into the directory of your cloned fork and run `npm install`.

Now you're ready to start coding! Here are a few NPM scripts to help with
development:

- `build` – Builds the project by running the `clean`, `compile`, `lint`, and
  `format:check` scripts
- `clean` – Removes the output directory
- `compile` – Compiles TypeScript files with `tsc`
- `format` – Formats files with Prettier
- `format:check` – Checks files for correct formatting
- `lint` – Lints the code with ESLint
- `lint:fix` – Attempts to fix problems found by the linter
- `test` – Runs tests (`*.spec.ts` files) with Jest
- `test:watch` – Runs tests in watch mode
