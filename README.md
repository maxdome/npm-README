# How To publish a NPM package in the [@maxdome](https://www.npmjs.com/org/maxdome/) scope

1. Ensure you're a member of [maxdome](https://www.npmjs.com/org/maxdome/members) (if you get a `Forbidden` at this URL you're not a member)
2. Add the scope to the `name` and the `publishConfig` in the `package.json` (see also: [@maxdome/npm-README](https://github.com/maxdome/npm-README/blob/master/package.json))
   ```json
   "name": "@maxdome/...",
   "publishConfig": {
    " access": "public"
   }
   ```
3. Publish
   ```bash
   npm publish
   ```
