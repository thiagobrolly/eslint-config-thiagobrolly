# ThiagoBrolly ESLint config

## Whats included?

- Standard config base;
- React plugin;
- React Hooks plugin;
- JSX a11y plugin;
- Prettier;

## Setup

### React (with Next.js)

Install dependencies:
```
npm i -D eslint @thiagobrolly/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "@thiagobrolly/eslint-config/next", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint @thiagobrolly/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@thiagobrolly/eslint-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint @thiagobrolly/eslint-config
```
Inside `.eslintrc.json`
```
{
  "extends": "@thiagobrolly/eslint-config/node"
}
```

> You can also use a `.eslintrc.js` instead of JSON if you prefer.
