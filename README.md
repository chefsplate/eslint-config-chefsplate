# eslint-config-chefsplate
This package provides Chefs Plate's .eslintrc as an extensible shared config. It extends eslint-config-airbnb.

Our default export contains all of our ESLint rules.

----

## Making Updates
**Ensure your github user has write permission to this repo**
- Run `npm i` as usual
- Make code changes to `src/index.js`
- Increment `package.json` version <-- IMPORTANT
- Run `npm run build` to output to `dist/index.js`, which will be published with package.json to npm while all other files are ignored.
- Commit/Push your changes to new branch
- Merge pull request to `master` (via github)
- Run `npm publish` (User: `Chefs-plate/etalp-sfehc`)
