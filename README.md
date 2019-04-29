# Chromatic Demo

This project was bootstrapped with [Create React App](https://github.com/facebook/create-react-app).

## Quick start

```
npm i
npm run chromatic
```

The chromatic script runs Chromatic to diff the current code from the baseline.

## How I set this up

1. Run create-react-app `npx create-react-app chromatic-demo`
1. Add Storybook `npx -p @storybook/cli sb init`
1. Add Chromatic `npm install --save-dev storybook-chromatic`
1. Add `import "storybook-chromatic";` to `.storybook/config.js`
1. Log into Chromatic site and add project
1. Add `chromatic` npm script to this project's package.json (script with app-code is displayed when you setup project in previous step)
1. `npm run chromatic` - This generates baseline images and provides a URL to view the results.
