# stylelint-config

This package provides Capitol Information Group's base JS _**.stylelintrc**_ as
an extensible shared config.

## Usage

Our default export contains all of our Stylelint rules for CSS + SASS. It
requires `stylelint` and extends the base config from
`stylelint-config-standard-scss` and `stylelint-scss`.

Install the correct versions of each package by running:

```sh
npx install-peerdeps --dev @itcig/stylelint-config
```

2. Add `"extends": "@itcig/stylelint-config"` to your _**.stylelintrc**_.
