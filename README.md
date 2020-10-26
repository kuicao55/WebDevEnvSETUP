# Web Development Environment Setup
## Install ESLint Locally:
1. In VSCode terminal, cd to the current work space and type `npm init`. (keep hitting return and make everything default).
2. Type `npm install eslint --save-dev`
3. Config Eslint by typing `npx eslint --init`. (1.To check syntax, find problems, and enforce code style. 2. JavaScript modules (import/export), 3. if use react, choose react otherwise, choose none of these. 4. NO. 5. Check both. 6. use a popular style guide. 7. Airbnb. 8. JSON. 9. YES.)

## Set Prettier
1. Search Prettier in the VSCode Extensions, and install it.
2. In `Setting - Text Editor - Fromatting`, Check `Format On Save`.

## Integrating ESLint With Prettier
1. In termial run `npm install --save-dev eslint-config-prettier`
2. In `.eslintrc.json`file, add `"prettier"` in `"extends"`.

## Install yarn
1. `brew install yarn`.

## Setup React
1. In termial type `npx create-react-app <name_of_app>` to create a react app.
2. To run a react app, type `yarn start`.
3. Packages to install: `yarn add react-router-dom`, `yarn add react-test-renderer`.
