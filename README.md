# eslint-config-typescript-react

1. Install:

```bash
npm i -D @terrestris/eslint-config-typescript-react
```

2. Install peerDependencies

Can be omitted for allready existing dependencies.

```bash
npm i -D eslint@^9
npm i -D @typescript-eslint/eslint-plugin@^8
npm i -D eslint-plugin-react@^7
npm i -D eslint-plugin-react-hooks@rc
npm i -D @stylistic/eslint-plugin@^2
npm i -D typescript@^5
```

3. Use config in your `eslintrc.js`

```javascript
module.exports = {
  extends: '@terrestris/eslint-config-typescript-react'
};
```
