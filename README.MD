# Kwilio Editor

This repository was designed upon Serhii Havrylenko's [monorepo](https://github.com/serhii-havrylenko/monorepo-babel-ts-lerna-starter). It is worth reading the README.

## Prerequisites

Have [Yarn](https://classic.yarnpkg.com/en/docs/install/) installed.

Install Typescript:
```sh
yarn global add typescript
```

## Installation

Run `yarn` inside the repo dir to install all dependencies.

## Build
Run `yarn build` inside the repo dir.

This will:

1. Compile the project using `babel`;
2. Lint with `sylelint` and `eslint`;
3. Build declarations (`.d.ts`) files using `typescript` CLI;

## Running Storybook

Run `yarn start` inside the repo dir.

## Contributing

Create either a `feature/*` branch out of `develop` branch or `fix/*` branch out `develop` or `master` branches.

Always perform [conventional commits](https://www.conventionalcommits.org/en/v1.0.0/) with `yarn commit`.

Open Pull Requests to the [maintained repository](https://github.com/kwilio/kwilio-editor), targeting the correct branch.