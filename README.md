# nullfame/jsenv 👊

Adam Finlayson's JavaScript application environment



## Contents

* Logical defaults in package.json (devDependencies, scripts)
* Babel with the "env" preset
* ESLint+Prettier with AirBnB's default rules
* Precommit hook to format (auto-fixing where possible, failing otherwise)
* Jest test runner and the corresponding ESLint plugin
* A logical .gitignore
* A minimal .editorconfig



## Setup

1. Download a local copy (clone if you want to improve this repository)
2. Edit and customize to your liking:
  * package.json (name, version, description, license)
  * README.MD
  * Whatever else your heart desires
1. Run `npm install` to get a package-lock.json
1. Make your first commit



## Commands

* `npm start` runs src/main.js
* `npm run lint` runs ESLint, printing errors and warning in the code
* `npm run format` is the same as `npm run lint` but fixes errors when possible
* `npm test` runs the Jest test runner on src/

### Incomplete Commands

* `npm run build` should invoke a production build step
* `npm run deploy` should deploy this code



## License

Free as in speech.  Safe for use around pets.
