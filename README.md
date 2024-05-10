# Full Stack open CI/CD

This repository is used for the CI/CD module of the Full stack open course

Fork the repository to complete course exercises

## Commands

Start by running `npm install` inside the project folder

`npm start` to run the webpack dev server
`npm test` to run tests
`npm run eslint` to run eslint
`npm run build` to make a production build
`npm run start-prod` to run your production build

## Commit Practicalities

When making commits, consider the following:
- Including `#skip` in a commit message will prevent automatic deployment for pull requests. This can be useful when you want to skip deployment for specific changes.
- Using `#major`, `#minor`, or `#patch` (default) in your commit messages will automatically determine the version update when creating tags using the `github-tag-action`. For example, `#major` will trigger a major version update, `#minor` will trigger a minor version update, and `#patch` will trigger a patch version update.
