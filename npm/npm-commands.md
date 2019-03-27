# NPM

#### List all packages versions

```sh
npm list
```

#### Only main packages

```sh
npm list --depth=0
```

#### View dependencies of a package

```sh
npm view [package] dependencies
```

#### See outdated packages

```sh
npm outdated
```

#### Versioning

`^` updates the minor version if available update

`~` updates the patches version if available update

#### NPM update

`npm update` only updates minor versions

#### Update Major versions
to achieve this must use the package `npm-check-updates`

run the command `npm-check-updates` to check for the available updates

and the command `ncu -u` to upgrade the available updates in package.json

followed by `npm install`

#### Publish NPM Package

If not account created at registry.npmjs.org 
```sh
npm adduser
```

Else, login
```sh
npm login
```

Inside the project, execute
```sh 
npm publish
```

Update package version before publish

```sh
npm version [major || minor || patch]
```