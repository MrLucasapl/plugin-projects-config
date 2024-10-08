# ESLint config

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
npm i -D eslint plugin-projects-config
```
Inside `.eslintrc.json`
```
{
  "extends": [
    "plugin-projects-config", 
    "next/core-web-vitals"
  ]
}
```

### React (without Next.js)

Install dependencies:
```
npm i -D eslint plugin-projects-config
```
Inside `.eslintrc.json`
```
{
  "extends": "plugin-projects-config/react"
}
```

### Node.js

Install dependencies:
```
npm i -D eslint plugin-projects-config
```
Inside `.eslintrc.json`
```
{
  "extends": "plugin-projects-config/node"
}
```