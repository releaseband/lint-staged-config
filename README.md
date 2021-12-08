# Installing

create [.npmrc](https://docs.npmjs.com/cli/v7/configuring-npm/npmrc) file in the **root project folder**:

```
echo @releaseband:registry=https://npm.pkg.github.com > .npmrc
```

```
npm i @releaseband/lint-staged-config
npx install-peerdeps --dev @releaseband/lint-staged-config
```

`lint-staged.config.js`:

```js
module.exports = require("@releaseband/lint-staged-config");
```
