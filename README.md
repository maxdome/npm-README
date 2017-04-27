# How To publish a NPM package in the [@maxdome](https://www.npmjs.com/org/maxdome/) scope

1. Ensure you're a member of [maxdome](https://www.npmjs.com/org/maxdome/members) (if you get a ```Forbidden``` at this URL you're not a member)
2. Add the scope to the name in the ```package.json```:
   ```"name": "@maxdome/..."```,
3. The initial publish need the access option set to public:
   ```npm --access public publish```
