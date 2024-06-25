# ES6 promise
## Description:
One simply does not use async/await without knowing promises!
- Promises (how, why, and what)
- How to use the `then`, `resolve`, `catch` methods
- How to use every method of the Promise object
- Throw / Try
- The await operator
- How to use an `async` function

## Resources:
Read or watch:
- [Promise](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Global_Objects/Promise)
- [JavaScript Promise: An introduction](https://web.dev/promises/)
- [Await](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Operators/await)
- [Async](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/async_function)
- [Throw / Try](https://developer.mozilla.org/en-US/docs/Web/JavaScript/Reference/Statements/throw)

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

### [0. Keep every promise you make and only make promises you can keep](./0-promise.js)

### [1. Don't make a promise...if you know you can't keep it](./1-promise.js)

### [2. Catch me if you can!](./2-then.js)

### [3. Handle multiple successful promises](./3-all.js)

### [4. Simple promise](./4-user-promise.js)

### [5. Reject the promises](./5-photo-reject.js)

### [6. Handle multiple promises](./6-final-user.js)

### [7. Load balancer](./7-load_balancer.js)

### [8. Throw error / try catch](./8-try.js)

### [9. Throw an error](./9-try.js)

### [10. Await / Async](./100-await.js)
