# Automated Linter and Formatter CI

Automatically check code style (Linting) and formatting on every Pull Request before merging to main branch using GitHub Actions

Used [Super-Linter](https://github.com/marketplace/actions/super-linter) action.

I configured specific checks using its environment variables. Checks like using `Prettier Formatter` to format the JS, CSS and HTML files instead of the `Biome Formatter`.

This is a useful workflow that checks pull request code formatting and linting before even reviewing it and merging it to the production branch.
