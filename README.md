# commons-validator-js

[![NPM version][npm-image]][npm-url]  ![Bower version](https://img.shields.io/bower/v/bootstrap.svg) [![Downloads][downloads-image]][npm-url]

JavaScript port of [Apache Commons Validator](https://commons.apache.org/proper/commons-validator/).

### Usage
Install the library with `npm install commons-validator-js`

```javascript
var EmailValidator = require('commons-validator-js').EmailValidator;

var validator = new EmailValidator();
validator.isValid('chuck.norris@gmail.com'); //=> true
validator.isValid('chuck.norris@gmail.con'); //=> false (can your validator do this?)
```
This library can also be installed using `bower install commons-validator-js`. Once you reference `bower_components/commons-validator-js/dist/commons-validator-js.js` you can then use the global variable `var EmailValidator = CommonsValidator.EmailValidator;` and proceed as shown in the npm example above.  

[downloads-image]: https://img.shields.io/npm/dm/commons-validator-js.svg

[npm-url]: https://npmjs.org/package/commons-validator-js
[npm-image]: https://img.shields.io/npm/v/commons-validator-js.svg

