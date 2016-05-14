# babel-jest

[Babel](https://github.com/babel/babel) [jest](https://github.com/facebook/jest) plugin

## Changes
see http://blog.dmbcllc.com/es2015-code-coverage-and-jest-react-js-unit-testing/ for why this is fork(ish)ed.

## Usage

If you are already using `jest-cli`, just add `babel-jest` and it will automatically compile JavaScript code using babel.

```
npm install --save babel-jest
```

If you would like to write your own preprocessor, uninstall and delete babel-jest and set the [config.scriptPreprocessor](http://facebook.github.io/jest/docs/api.html#scriptpreprocessor-string) option to your preprocessor.
