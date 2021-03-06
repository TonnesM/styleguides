# Style Guides

This repository is used to store style guides for Mozilla communities. All localization style guides and related documents are listed in [docs/SUMMARY.md](docs/SUMMARY.md).

If you’re reading these pages on GitHub, a version with improved readability and search capabilities is available [here](https://mozilla-l10n.github.io/styleguides).

## Updating the documentation

Simply open a pull request adding the new file or updating an existing document. Make sure to follow [these style guidelines](https://github.com/mozilla-l10n/documentation/blob/master/misc/documentation_styleguide.md), and note that all pull requests need to be reviewed before merging. The instructions for creating new community style guides are part of the [guidelines for community style guides](docs/guidelines/README.md). Please also run the following commands to ensure the files are correctly formatted.

```
$ npm install
$ npm test
```

If you want content to appear on GitBook, it needs to be listed in [docs/SUMMARY.md](docs/SUMMARY.md).

## GitBook

A version with improved readibility and search is built automatically via Travis using GitBook. Updates are pushed to the `gh-pages` branch and available via GitHub Pages [here](https://mozilla-l10n.github.io/styleguides).

If you want to build and preview the GitBook locally, [install npm](https://www.npmjs.com/get-npm) and and run the following commands from the root of the repository:

```
$ npm install
$ npm start
```
