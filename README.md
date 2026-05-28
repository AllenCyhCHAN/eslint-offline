# eslint-config-offline

Shareable ESLint config for Node projects (based on `eslint:recommended`).

## Install

From GitHub (works well for internal/VNC environments):

```bash
npm i -D github:AllenCyhCHAN/eslint-offline
```

## Use

In your project’s ESLint config:

**`.eslintrc.cjs`**

```js
module.exports = {
  extends: ["offline"],
};
```

## Notes

- This package declares `eslint` as a peer dependency, so your project should also have `eslint` installed.

