# Rocketseat ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

1. Install the dependencies
```
npm i -D eslint @rocketseat/eslint-config
```

2. Create a `.eslintrc.json` file extending the config:
```
{
  "extends": "@rocketseat/eslint-config/react"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.

3. Create a script on `package.json`
```
"scripts": {
    "lint": "eslint src --ext .ts,.tsx --fix"
  },
```
