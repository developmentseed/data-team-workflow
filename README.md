# Data team workflow

A basic page that contains data-team workflow, for diferente annotation and mapping work

For the previous version of project-seed, that used browserify see [tag v4.0.0](https://github.com/developmentseed/project-seed/tree/v4.0.0).

## Development

```sh
nvm install
npm install
yarn build #clean & build everything and put it into dist folder
yarn serve #serve the pages and utilize live reload on changes to fonts, images, scripts and HTML.
```


### Configurations and environment variables

At times, it may be necessary to include options/variables specific to `production`, `staging` or `local` in the code. To handle this, there you can use `.env` files.
See Parcel documentation on [env variables](https://parceljs.org/features/node-emulation/#environment-variables).

## Github Actions for CI
Testing and deployment is taken care of by Github Actions. It is set up to:

1. run checks (test & lint) on every non-draft Pull Request
2. build and deploy the application on pushes to the `main` branch

To make sure that the site deploys with passing checks, branch protection should be set up for the `main` branch (`Require status checks to pass before merging`).

Deploy is not set up by default, but the project contains [sample workflows](.github/_workflow-samples/README.md) that can be used to set it up.

## Linting

Our [ESLint rules](.eslintrc) are based on `eslint:recommended` rules, with some custom options. To check linting errors run:

    yarn lint

## Coding style

File [.editorconfig](.editorconfig) defines basic code styling rules, like indent sizes. 

[Prettier](https://prettier.io) is the recommended code formatter. Atom and VSCode have extensions supporting Prettier-ESLint integration, which will help maintain style consistency while following linting rules.
