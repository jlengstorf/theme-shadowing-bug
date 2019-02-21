# Bug Reproduction — Theme Component Shadowing

This repo shows that a linear chain of themes does not resolve the shadowed component properly.

## Expected Behavior

Both the `foo.js` and `bar.js` components from `theme3` should be displayed.

## Actual Behavior

The `bar.js` component from `theme2` is displayed.

## To Run This Repo

```
git clone git@github.com:jlengstorf/theme-shadowing-bug.git
cd theme-shadowing-bug/
yarn
yarn workspace site develop
```
