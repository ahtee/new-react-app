[![Build Status](https://bencotte.visualstudio.com/new-react-app/_apis/build/status/ahtee.scuffed-react-app?branchName=master)](https://bencotte.visualstudio.com/new-react-app/_build/latest?definitionId=2&branchName=master)

# [scuffed-react-app](https://www.github.com/ahtee/scuffed-react-app)

> :rocket: Start developing your React application with stress. :nail_care:

Boilerplate package for creating React apps with Redux built-in. :ship: **npm@5.2.0** or later is required to use this project with `npx`.

# Get Started

### Run this project locally

- Clone the repository and run `yarn`
- Run `yarn start` to run the `webpack-dev-server`
- Get Hacking!

## Goals

This project is intended to be a boilerplate for React, CSS-in-JS, and Redux. Most boilerplates today are extremely lean and rely on the developer to correctly setup and install all the modules and store. The goal is to have a good starting point for larger applications requiring a `store`, or central-state-management tool like Redux.

I want to be able to create a scalable React project that includes most popular, cutting-edge tools without the hassle of setting them up every time. The only outlying task would be to connect to a database.

- [x] React
- [ ] TypeScript compatibility
- [ ] Get started with `npx` command
- [ ] Publish package to npm

## Notes

> Feel free to tweak as you see fit. The project supports **TypeScript**. To remove them from your project, just type `yarn remove typescript @types/react @types/react-dom @typescript-eslint/eslint-plugin @typescript-eslint/parser ts-loader` to uninstall these modules. Don't forget to remove `tsconfig.json` and add **"parserOptions"** in your `.eslintrc`. If you need eslint, install the package with yarn `yarn add -D babel-eslint` and add it as the value in `.eslint`'s **"parser"** property.

> Typescript files are denotes as `.ts` **NOT** `.tsx` files.

### MIT License

See [LICENSE](./LICENSE.md)
