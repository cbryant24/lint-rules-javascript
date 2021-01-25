# Eslint and Prettier Setup

Run the following command to install and install peerDependencies as devDependencies for the current project

> npx install-peerdeps --dev @cbryant24/eslint-config

Create a `.eslintrc` file in the root of your project's directory (it should live where package.json does). Your `.eslintrc` file should look like this:

```javascript
{
  "extends": [
    "@cbryant24/eslint-config"
  ]
}
```
