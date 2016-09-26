# node-range
An intelligible function for JavaScript that produces a range  

##Overview

The module can be used when you need a function that returns the range of some given numbers as arguments

##Installing 

```javascript
npm i node-range --save-dev
```

##Usage

Simply require the `node-range` module. The export function can be used in any module you desire:

`range(start, end, step)`

```javascript
const range = require('node-range');

range(1,10); //==> [1,2,3,4,5,6,7,8,9,10]

```

##TODO

* add more tests

##Tests

`npm test`

Uses mocha and chai's expect

```javascript
// need to add tests
```

##Related Modules

* [is-even-integer](https://github.com/ahadb/is-even-integer)
* [first-of-array](https://github.com/ahadb/first-of-array)
* [is-even-integer](https://github.com/ahadb/is-even-integer)

##Contributing

Feel free to file an issue or bug.