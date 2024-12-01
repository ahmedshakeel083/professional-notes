# Enabling the installation through NPM

  - Create a file called bin/cli.js (bin is the folder name)
  - cli,js contains the code for the installation
  - Add the name in package.json Eg. "name": "@username/reponame". Here username is the account holder username by which the acc exists in npm
  - Add this in package.json with "bin": "./bin/cli.js"
  - Change the version number in package.json every time u push the new change to npm
```
npm login
npm publish --access public
```
  - To check the package has been published successfully
```
npx @username/reponame
```