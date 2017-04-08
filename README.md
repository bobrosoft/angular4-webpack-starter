Based on [angularclass/angular2-webpack-starter](https://github.com/angularclass/angular2-webpack-starter).

*DISCLAIMER: All changes were made by my taste and you could be not agree with some of them :)*

## Quick start
**Make sure you have Node version >= 5.0 and NPM >= 3**

```bash
# clone this repo
# --depth 1 removes all but one .git commit history
git clone --depth 1 https://github.com/bobrosoft/angular4-webpack-starter.git

# change directory to our repo
cd angular4-webpack-starter

# install the repo with npm
npm install

# start the server
npm start

# if you're in China use cnpm
# https://github.com/cnpm/cnpm
```

## Differences from [angularclass/angular2-webpack-starter](https://github.com/angularclass/angular2-webpack-starter):
 - switched to **Angular 4** by default
 - cleanup, all unnecessary files removed, boilerplate-kind structure
 - webpack: fixed warnings
 - webpack: fixed Chrome Debugger issues with breakpoints not working properly
 - webpack: fixed `Critical dependency: the request of a dependency is an expression`
 - webpack is less verbose now and doesn't spam with lots of `delegated` strings
 - webpack now generates `stats.json` file in the root folder upon product build so you can analyze "what's in the bundle?" with tools like https://chrisbateman.github.io/webpack-visualizer/
 - less strict and better `tslint.json`
 - git-friendly `.editorconfig` settings
 - npm: `lint` task has tests excluded from linting process
 - npm: added `lint-fix` task if you want linter to auto-fix your linting issues (but be careful, it can break the code sometimes)
 - HMR is removed (you can add it back if you want)
 - npm: next packages removed: `@angularclass/conventions-loader`, `@angularclass/hmr`, `@angularclass/hmr-loader`

## Troubleshooting
 - `UNMET PEER DEPENDENCY @angular/animations@4.0.1` — not the issue, @angular/animations now is optional in Angular 4.

## More info
Check [angularclass/angular2-webpack-starter](https://github.com/angularclass/angular2-webpack-starter).