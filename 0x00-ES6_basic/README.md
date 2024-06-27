# ES6 basic
## Resources:
Read or watch:

- [ECMAScript 6 - ECMAScript 2015](https://www.w3schools.com/js/js_es6.asp)
- [Statements and declarations](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements)
- [Arrow functions](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Arrow_functions)
- [Default parameters](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/Default_parameters)
- [Rest parameter](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Functions/rest_parameters)
- [Javascript ES6 — Iterables and Iterators](https://towardsdatascience.com/javascript-es6-iterables-and-iterators-de18b54f4d4)

## Requirements:
- Ubuntu 18.04 LTS using NodeJS 12.22.x
- Jest Testing Framework
- ESLint

### Install NodeJS 12.22.x
```console
$ curl -sL https://deb.nodesource.com/setup_12.x -o nodesource_setup.sh
$ sudo bash nodesource_setup.sh
$ sudo apt install nodejs -y
```
### Check version
```console
$ nodejs -v
v12.22.1
$ npm -v
6.14.12
```
### Install Jest, Babel, and ESLint
```console
$ npm install --save-dev jest
$ npm install --save-dev babel-jest @babel/core @babel/preset-env
$ npm install --save-dev eslint
```

## Files:

[0. Const or let?](./0-constants.js)

[1. Block Scope](./1-block-scoped.js)

[2. Arrow functions](./2-arrow.js)

[3. Parameter defaults](./3-default-parameter.js)

[4. Rest parameter syntax for functions](./4-rest-parameter.js)

[5. The wonders of spread syntax](./5-spread-operator.js)

[6. Take advantage of template literals](./6-string-interpolation.js)

[7. Object property value shorthand syntax](./7-getBudgetObject.js)

[8. No need to create empty objects before adding in properties](./8-getBudgetCurrentYear.js)

[9. ES6 method properties](./9-getFullBudget.js)

[10. For...of Loops](./10-loops.js)

[11. Iterator](./11-createEmployeesObject.js)

[12. Let's create a report object](./12-createReportObject.js)
